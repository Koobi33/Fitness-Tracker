# Fitness Tracker project

## The goal
To help people complete sport exercises without pro coach using machine learning.

## Train model
We need to understand which exercise person do now and level of quality of moves.

On this step this video used as reference squat.

![](./media/example.gif)
 
This video cutted into short parts to produce little steps, which will become  classical machine learning problems.

![](./media/1_step.gif)
![](./media/2_step.gif)
![](./media/3_step.gif)
![](./media/4_step.gif)

Now here 4 steps which must follow one by one from first to last and from last to first. This give opportunity to count exercises and understand quality of person moves.
Lets teach our model. ([Teachable Machine](https://teachablemachine.withgoogle.com) was used for this task). 

Every step will be an own class. Each video should be divided into frames, and they should be uploaded according to their classes.


Result of model: 

![](./media/teached_model.gif)

## Result
Using algorithms and a trained model, you can do everything you need with a camera and canvas.

![](./media/result.gif) 

Also you can [try it](https://koobi33.github.io/visionHack/) yourself.

## Next steps
You can use more data to train powerful model for best results and train it for another exercises.  


