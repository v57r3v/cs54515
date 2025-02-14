java c
STATS 101/108 - Chapter 2 Classification | Whakarōpū: Task
Introduction
Satellite images can be used to detect features of cities. Watch this video about how the French tax authority uses an automated analysis of such images to find unconsented additions to buildings, such as swimming pools.
In this task, we will explore how we can use digital image data (i.e. the pixels of satellite images) to classify satellite images into two groups.
Q1


For this question, you need to describe a visual difference between parts of a satellite image of different suburbs.
Green spaces are parts of a city that are mainly made up of grass, trees and other vegetation, rather than being built-up with roads or buildings. For simplicity, we will also consider bodies of water as green space. As part of this investigation you will develop and evaluate a classification model for urban green spaces in an Auckland suburb.
Head to this Wikipedia page to get a list of Auckland suburbs. You can select a suburb close to where you live or one that you particularly like for this investigation. Head to Google maps (use the browser version rather than the app) and type in the name of this suburb (this should look like this: [your_suburb], Auckland).
Use the + button on the Zoom slider in the bottom right until the scale is set to 100 m.





Click on the Layers button in the bottom left and select Satellite.


Look at the satellite image. As this investigation is about building a classification model for built-up and green space areas, you need to make sure that the proportion of both area types is at least 20% based on what you see on the map. If this isn’t the case, search for a different suburb and repeat the steps.
Write down the name of the suburb. Take a screenshot (snip) of the map and paste it into your answer.
Repeat the process for a second suburb.
Write one sentence about what feature of the satellite image is most helpful when deciding whether a part of the satellite map is built-up or green space.




Construct your answer using the following structure. Copy and paste it into the template and complete your answers accordingly.
Suburb 1 (you will use this for training):
The screenshot of the satellite image of Suburb 1:
Suburb 2 (you will use this for testing):
The screenshot of the satellite image of Suburb 2:
The sentence about the visual feature:
Q2
For this question, you need to create a decision rule for a classification model.
Head to the The grass is always greener? app and use Suburb 1 from Q1.
Press the Get satellite photos for training button. You will get 40 random satellite images for your suburb.
Sort ALL of the images into one of the two levels “built-up” and “green space”. There should be at least five images in each group and no images left over.
Take a screenshot of the first few rows of the sorted images and the labels. It is OK if your screenshot doesn’t contain all of the images, but you need to sort all of them.
Scroll down to the bottom of the page and press the Generate link to training data button. Copy the link.
The app creates variables using the pixels in the satellite image. In addition to the image-data-related variables you’ve seen in the notes and lectures (e.g. mean_grayscale ), there are also variables that give the percentage of red, blue, or green pixels (e.g. percentage_red ) in the image, the number of different hues used ( num_hues ) in the image, and the average difference in contrast between neighbouring pixels




( mean_gradient ).
Use the link to iNZight Lite with your training data to choose a numeric variable that will help you to sort the images into the two groups (built-up or green space). You might need to try代 写STATS 101/108 - Chapter 2 Classification | Whakarōpū: TaskR
代做程序编程语言 out a few variables to see which is best.
Use iNZight Lite to make a plot of your chosen numeric variable and area_type . Copy the plot from iNZight Lite.
Write down your decision rule. Use the following structure: If A is less than B, classify the image as C, else classify the image as D. In this structure, A is the numeric variable, B is the cutoff value, C is one of the area types and D is the other area type.
Construct your answer using the following structure. Copy and paste it into the template and complete your answers accordingly.
The screenshot of the sorted satellite images:
The link to your training data set through iNZight Lite:
The plot you created to develop your classification model:
Your decision rule:




Q3
For this question, you need to justify a decision rule for a classification model.
Write one sentence explaining how you determined the “cutoff value” for the decision rule used in your classification model, in terms of classification (or misclassification) rates.
Construct your answer using the following structure. Copy and paste it into the template and complete your answers accordingly.




One sentence justifying the decision rule for your classification model:
Q4
For this question, you need to evaluate your classification model.
Go back to the The grass is always greener? app and use Suburb 2 that you identified in Q1. Press the Get satellite photos for testing button and sort the 40 satellite images for this suburb. Sort all images for this suburb according to the same criterion based on a visual feature as in Q2.
Identify the baseline model (the kind of area type that has more images in it) and calculate its PCC.
Scroll to the bottom of the page and enter your decision rule from Q2.
Click the “Use decision rule with testing data” button. All incorrectly classified images have a red frame.
Take a screenshot that shows all sorted images with red frames (if any).
Calculate the PCC for your classification model.
Use the PCC of the “baseline model” and the PCC of your classification model to write one sentence to evaluate how well your model classified the satellite images.
Construct your answer using the following structure. Copy and paste it into the template and complete your answers accordingly.
The PCC and area type for your baseline model:
The screenshot of the sorted images:
The PCC for your classification model:
One sentence evaluating your classification model:
Q5




For this question, you need to consider the appropriateness of a data based approach to classification.
In the beginning of this task you used a feature of the satellite image to classify/label the areas on the map of the suburb. You then used image data (pixels) to build a classification model to automate the process, and evaluate it with data from a different suburb. Imagine you had to classify a large number of satellite images for all Auckland suburbs. Explain in two to three sentences to what extent your classification model would be appropriate for this purpose.
Construct your answer using the following structure. Copy and paste it into the template and complete your answers accordingly.
Your explanation:
Q6
For this question, you need to reflect on the learning focus for this chapter (Classification).
Describe in your own words ONE important idea from this topic. Do not just copy one of the learning objectives or something from the notes or other learning resources. One sentence is enough, but you must write about your own personal reflection.
Construct your answer using the following structure. Copy and paste it into the template and complete your answers accordingly.






         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
