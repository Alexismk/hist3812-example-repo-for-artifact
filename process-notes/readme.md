# 3D Modelling Process Notes

Below I will detail my journey experimenting with 3D modeling for the first time. 


## Choosing the topic 

While initially trying to think about a topic and choose an artifact to work on, I was intimidated because I had a very loose concept of what this project would entail, and I knew that I would be working on this subject for the entirety of the course. After two failed attempts to attend two different museums, with no main artefact in mind, a specific idea occurred to me. Largely inspired by our discussions in class regarding artworks and reproductions, as well as Bruno Latour & Adam Lowe’s paper, “The migration of the aura or how to explore the original through its fac similes”, I decided to venture out to the National Gallery of Canada and scan their sculpture of Andy Warhol’s, “Brillo Soap Pad Boxes” in order to create my 3D model.
I chose to scan Warhol’s sculpture for two main reasons. 


First, I knew I wanted an object that would be easier to scan as to prevent problems down the line when it came to rendering the 3D model. For that reason, I wanted a model that was small enough so that I could get images from all angles. 
After some initial experimentation with 3D modeling programs, I knew that I would most likely have to photo mask my images in order to remove background objects. Therefore, and object with a simple form would make the photo shopping process easier. 
Lastly, keeping in mind that 3D programs do not recommend images that have poor lighting, I wanted to choice and object that did not have an glass encasing around it, and that had bright lighting all around. In my mind, “Brillo Soap Pad Boxes” was perfect because I remember it being positioned in the center of the room, so I could walk around it fully, it has straight edges all around it, making photo masking very easy, and it should be brightly lit under gallery lighting.  


I thought that Andy Warhol’s “Brillo Soap Pad Boxes” would make a fascinating subject because of the nature of the sculpture, and the controversy that surrounds it. The sculpture is essentially a copy of commercial packaging and because of this, its value as art has been disputed for years. More on this will be detailed in the Paradata.


## Acquiring the Images

The gallery had been closed for a month for renovation and only opened back up and January 22nd, preventing me to go earlier in the month. I managed to get there Thursday night and I found the sculpture located very conveniently right in the middle of the room, allowing me to make my way fully around the object. Unfortunately, the lighting was not as bright as I hoped or as I remembered, making some of the sides slightly more shadowed, although I am unsure whether or not this will affect the final outcome. Furthermore, getting an “aerial view” type image (from the top) was a lot more difficult considering that I am quite short, and attempts to get up as high as possible is quite challenging considering that I was in an art gallery under the confines of conduct rules and under the watch of security guards (in other words, getting on my friends shoulders were not an option in this case).  I managed to hold my camera up as high as possible to try to get images from above.
I took around 40 images in the end I hope that this will be enough (or better yet, too much) to form a digitized 3D model.


## Making the Model

### 1st Attempt

I downloaded regard 3D in order to make the 3D model. I first uploaded all of my images into the program to create an initial model in order to see what I was working with (see file). As expected, the program picked up all of the background points, creating a model of the room instead of the object itself. What I did not expect, was the amount of time each step took in the rendering process. Each step, from “computing matches”, to “triangulating” to “densification”, all took about thirty minutes to load, which was quite frustrating, especially when the 3D object does not turn out well in the end regardless.
In order to produce a better 3D model, I would have to edit out the backgrounds from all of my images. I did so using the program “Gimp” and photo masking each photo by selecting the object with the lasso select tool, inversing the selection and deleting the background. While tedious, I completed this step for all 35 images I decided to use. Thankfully, this process was not as painful as it could have been because I purposely chose an object that had flat edges which permitted me to select the object with more ease.  

### 2nd Attempt 
I imported the newly masked images into 3D Regard, hoping for a cleaner 3D model. Once again, the program took a very long time to render each step and in the end, the new model was not any better than the first. While all of the background objects were removed, the program seemed to confuse the sides, and I ended up with a model that was missing the backside completely. I decided to go ahead and render the surface of the model in hopes that it would fill in missing areas, however the program crashed and I was left no choice but to shut it down and start over.


### 3rd Attempt

I input the photos into 3D Regard once again, this time leaving out the top view images in hopes that the program does not become confused again. Once generated, the 3D model was completely missing one side two sides, and the other sides seemed to be mixed in such a way that they overlapped in an odd way with random portions sticking out. I tried to regenerate the surface and attempt to fix it and the program crashed once again, leaving me to start over. 


### 4th – 6th (?)Attempt

I tried a number of times to generate a 3D model, and varied the settings in the hopes of a better result. I tired changing some of the things I was doing in an attempt to pinpoint the problem. I left out the aerial view images, added more images, decreased the amount of images, used different settings under “Densification” and “Surface Generation”, and I unfortunately could not get a model I was remotely happy with. Attempts to generate the surface made the model look even worse and would make the system crash once again. 
I tried to save my work (without a surface textre), and compress the file so that I could upload it to Sketchfab as a test, in case I could not develop a better model. It turns out that my file was too large for Sketchfab even once it was compressed and I must have done something wrong.


### We Have a Winner! (Or the closest thing to it)

I finally gave up on 3D Regard and I tried out 3D Zephyr. The upload process was quite simple, and may have been slightly quicker than 3D Regard. This time, I left out a selection of my images in the hopes that the extra angles would not confuse the program. The final model, surface and all, was marginally better than any of the results that I got with 3D Regard. Unfortunately, a whole side of the model was missing just like in 3D Regard. What I like about this program is that you can click onto one of your images and be transported to the exact point of view that that image was taken, and see it overlaid with the actual model. This allowed me to understand why half of my model was not showing up. It seemed that the program misidentified and confused my images of the backside of the sculpture, with images that came from another angle. The result was an entirely missing side. I tried to look up ways that I could fix this, perhaps a way I can manual assign the point of view of the camera, but I could not find a way to do this. This problem is something I hope I can fix in the future.  
Fortunately, 3D Zephyr offers a function that allows you to compress the textures and layers, and export the model directly onto Sketchfab. Once obtaining my API, my model was uploaded right onto my account successfully, and so I don’t not need to be concerned about file size any longer. 

## Summary Review
### Problems and Difficulties:

My biggest problem during this process was the actual 3D modeling programs. This is all very new to me so I did not expect it to go well on the first attempt (or the second, or the third…). Specifically, I could not generate one side of my model because my images confused the software, and when generating the surface, the software was consistently crashing. The software also ran extremely slowly, which made the actual process of creating the model very tedious and time consuming. I was also concerned for a short while that I would not be able to upload my files because they were far too large, but 3D Zephyr fixed that problem for me.

### Solutions:

The only significant problem I was able to fix was the uploading to Sketchfab issue.
I found that 3D Zephyr worked best for my model, and created a much more consistent, even, and clear surface than 3D Regard did. I also found that editing on 3D Zephyr is much more flexible. 
Going forward, I would like to spend more time perfecting my model and I would like to find a way to fix the camera angles so that I can have a full and complete model without any massive holes.  I hope that I can find a tutorial that will teach me how to manipulate and clean up my model, because right now I am still very unsure of many of the functions that these programs offer.
It may also be worth my time to generate my model on a computer with more processing power, so that it will not take as much time to produce every single step of the model making. 
Finally, I think most of my model problems lie in my choice of subject. While the “Brillo Soap Pad Boxes” were very easy to edit on Gimp, I could not anticipate the fact that the repetitive, flat surfaces would cause the program to get confused and misplace the camera angles. In the future, I would chose a subject that did not have a simple, repetitive surface, that way the program would not confuse the faces.

## Going Forward
I am very eager to see where else this project will take me. I think that now I have a better sense of my subject, and course expectations, I can go forward and gather information and analyse readings with much more ease because I know what I am looking for and I can understand difficult concepts by keeping in mind my own experiences and my own project.

