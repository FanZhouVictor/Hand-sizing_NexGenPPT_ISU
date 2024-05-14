# Work records / plan for hand-sizing project.

# One month plan. 
1. Week 1
   - Train the coco-annotate model initially for the palm pictures first, calculate the distance between different key points.
3. Week 2
   - Find a way to embed the model into an APP. Need contact Dr. Baskar.
   - if the previous model performs well, train the model for other two groups of pictures of hand in different angles. 
5. Week 3
7. Week 4


# Week 1. (May 14 - 18th)

## Monday 
1. Meet together with Chandan and Sadegh.
   - Introduce the hand sizing project.
   - Brainstormed the methods we could use:
     - **Key point detection** -- same as the method we used before.
     - **Color point detection** -- key point detection is better than this.
     - **SAM** -- need fine tuning, which takes time (needs proof).
     - **Edge detection after using the SAM** -- since edge detection was previously used and not effective, we don't consider it yet.
   - Determined to first use the COCO-annotation key point detection, aiming to quickly get a usable model. 

## Tuesday 
1. View the method of using COCO-annotation key point detection.
2. Learning to annotate the key points of the palm images with sequences.

## Wednesday 
1. Meet and discuss the way to annotate the pictures. 
2. Annotate 90 palm pictures, 30 pictures each, with key points in sequence.
3. Understand the model setting.

## Thursday. 
1. training the model based on the understanding from Wednesday and check if the results are good.
2. If the model performs well, annotate all palm images and train the model based on the whole dataset. 
3. Consider the method to calculate the distances between different key points.

## Friday. 
1. find a way to calculate the distance between different key points. 
