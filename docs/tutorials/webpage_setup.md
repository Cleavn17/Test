# How to set up

* Using markdown
* How to do math using latex
* How to put images
  * <figure markdown>
    <!-- ![Cone map](media/image1.png){ width=600 loading=lazy } -->
    <figcaption>Figure 1: Cone clustering output from the VLP-16.</figcaption>
  </figure>

or 
![Nano](https://s3.amazonaws.com/cms.ipressroom.com/219/files/20192/jetson-nano-family-press-image-hd.jpg) {width = 500}

* how to embed videos
  * youtube videos
    * <div class="video">
  <iframe
    src="https://www.youtube-nocookie.com/embed/VIDEO_ID?rel=0"
    title="Demo"
    loading="lazy"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen></iframe>
</div>
  * Online mp4
  <video controls preload="metadata" width="100%" playsinline>
  <source src="https://example.com/path/video.mp4" type="video/mp4">
  Your browser doesn’t support HTML5 video.
</video>

with auto play
<video controls autoplay width="50%" playsinline>
  <source src="https://terra-1-g.djicdn.com/65c028cd298f4669a7f0e40e50ba1131/Download/Avia/avia-%E5%AE%89%E8%A3%85-v3.mp4" type="video/mp4">
  Your browser doesn’t support HTML5 video.
</video>

 

* link other md files locally
  * as well as link to sections of different folders
* code blocks 
  * use ``` then new line and put ur code in it and the new line ```

make ur file in the folder that u want, and make sure to link it in the nav section in the mkdocs.yml file




Test run locally running mkdocs serve

make sure there is no warnings  or all pages are linked in the mkdocs.yml before pushing to git