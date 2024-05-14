# Work records / plan for hand-sizing project.

# One month plan. 
1. Week 1
   - Train the coco-annotate model initially for the palm pictures first, calculate the distance between different key points.
3. Week 2
   - Find a way to embed the model into an APP. Need contact Dr. Baskar.
   - if the previous model performs well, train the model for other two groups of pictures of hand in different angles. 
5. Week 3
7. Week 4


# Week 1. (May 13 - 19th)

## Monday 
1. Meet together with Chandan and Sadegh.
   - Introduce the hand sizing project.
   - Brainstormed the methods we could use:
     - **Key point detection** -- same as the method we used before.
     - **Color point detection** -- key point detection is better than this.
     - **SAM** -- need fine-tuning, which takes time (needs proof).
     - **Edge detection after using the SAM** -- since edge detection was previously used and ineffective, we don't consider it yet.
   - Determined first to use the COCO-annotation key point detection, aiming to get a usable model quickly. 

## Tuesday 
1. View the method of using COCO-annotation key point detection.
   - https://github.com/FanZhouVictor/Custom-keypoint-detection?tab=readme-ov-file
3. Learning to annotate the key points of the palm images with sequences.
   - https://www.youtube.com/watch?v=OMJRcjnMMok&t=186s
## Wednesday 
1. Meet and discuss the way to annotate the pictures. Define the sequence of the key points. 



## Thursday. 
1. Annotate some number of pictures. (Number to be determined)
2. learn how to train the model.


## Friday. 
1. Understand how to train the model based on the Github Repo.
2. Try to train the model and check if the results are good.
   - If the model performs well, annotate all palm images and train the model based on the whole dataset. 
2. Discuss the method to calculate the distances between the predicted key points.

# Week 2.(May 20 - 26th)
## Monday 
1. find the way to calculate the distance between different key points. 
