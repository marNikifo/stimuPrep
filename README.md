# stimuPrep
Eventual home of a full set of scripts to prepare stimulus sets (namely, headshots/faces) for use in social cognition research. Stimuli in this literature are a bit all over the place in terms of quality, which complicates any attempt to make inferences based on the results. Some of that could be alleviated by making stimulus creation more consistent across the set, especially when it comes to the experiment's central manipulation. There's plenty of open source tools and projects out there that can help, but I haven't encountered many meant for psych researchers. We have the benefit of working from pre-normed stimulus sets as a base, but we also tend to be pretty new to the finer points of computer vision.

Since I've been learning about this stuff for my own work, I figure it might be helpful to upload it in case someone else is in the same boat. My ultimate goal is to be able to take a normed database (e.g. the Chicago Face Database), use its attached codebook to extract the faces relevant to my design, and apply a consistent set of treatments to all of the extracted files as a batch. 

For now it's just an alignment script, I intend to have scripts for denoising, normalizing parameters like contrast and lightness throughout the set, and eventually generating set of morphs that stick as closely as humanly possibly to the original images---otherwise the norming data wouldn't be applicable anymore, which would defeat the purpose of normed databases in the first place! These goals aren't unique by any means, of course, but having all the little components you need in one place can go a long way (especially when you're still getting the hang of things).

A lot of this is going to be me kludging together bits from various very nice computer vision tutorials. Thus far, I've used:

https://github.com/mataktelis/face-morphing-algorithms

https://github.com/Miahi21/Face-Alignment-Cropping

https://woteq.com/how-to-rotate-images-in-python-using-opencv-cv2
