# Srcset demonstration
---
## Demonstration of using srcset for adaptive images.
Srcset is necessary in case we have adaptive web-page to reduce internet traffic for better UX.
***
## How it works.
Img tag contains media query, so we can easily change image's size witch depending on window width, so smallest image takes low traffic.
***
## How can i check it?
Check it out on [GitHub Pages](https://oddyhater.github.io/srcset-project/) of this repo, open a devtools and go to network tab. Set window's width at 769px+, reload the page, next set width at 768px - 426px range, look at the sources downloaded, repeat for <425px range.
***
## My results:
* >769px+
  * adaptive and non-adaptive images have the same options(76,7kB and 322ms download time)
<br/>

* >768px - 426px
  * adaptive: 34.0kB and 196ms download time)
  * non-adaptive: 76.7kB and 237ms download time)
  (~55% data less)
<br/>

* ><425px
  * adaptive: 15.7kB and 113ms download time)
  * non-adaptive: 76.7kB and 595ms download time)
  (~80% data less)
<br/>
Don't forget to reset your browser's cache before each try.

Hope you enjoed.
