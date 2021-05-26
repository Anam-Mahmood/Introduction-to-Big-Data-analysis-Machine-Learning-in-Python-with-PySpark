![Build](https://github.com/fawazsiddiqi/slides_to_pages/workflows/deploy-slides/badge.svg?branch=master)

# Convert your slides and host it to GitHub Pages (Repo Template)

**NOTICE:** Please make sure you edit your readme & files to the content of the workshop as appropriate, since this is just a template to be used.

#### Steps to host your slides:

1 - Use the "use template" option on this repo and create a new repo with your desired name.

2 - Once done wait for the initial GitHub Action to complete 

3 - Export your PPTX into images (PNG) and add those images into ```images/slide_images```

**Notice**: please remove the existing pictures in the directory they're just there for reference.

4 - Once your pictures are in the slide_images directory, go to the repo and get the image link by opening the image on GitHub and then right click and ```Copy image address```

It should look something like this: https://github.com/fawazsiddiqi/slides_to_pages/blob/master/images/arch.jpg?raw=true

5 - Once the image URL is there, head to the ```slides``` directory in the repo and edit the ```README_slides.md```  

**Notice**: Please do NOT delete the kernel specs in the ```README_slides.md``` file, you may edit the file after ```+++ {"slideshow": {"slide_type": "slide"}}```

6 - Import your images as into the file by ```![center](https://github.com/<USERNAME>/<YOUR REPO NAME>/blob/master/images/<IMAGE_NAME?raw=true)``` 

Luckily PowerPoint exports the slides with the slide numbers at the end so you can replicate the links within no time.

7 - 

```+++ {"slideshow": {"slide_type": "slide"}}``` is used to create a slide

```+++ {"slideshow": {"slide_type": "subslideslide"}}``` is used to create a a subslide to a particular slide 

8 - You can see how a slide and how a subslide looks like by going to https://fawazsiddiqi.github.io/slides_to_pages/

9 - Last but not the least, push your changes into your repo, go to the ```settings``` tab of your repo, in the ```Options``` tab, go to the ```GitHub Pages``` section and select the source as ```gh-pages``` and keep the directory as ```/ (root)```

10 - Once saved ypu can go to ```https://<GITHUB USERNAME>.github.io/<REPO_NAME>``` to access your slides

11 - Now you can easily share the slides with the attendees of your webinars, cheeers!