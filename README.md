# cs6476-problem-set-3--introduction-to-ar-and-image-mosaic-solved
**TO GET THIS SOLUTION VISIT:** [CS6476 Problem Set 3- Introduction to AR and Image Mosaic Solved](https://www.ankitcodinghub.com/product/cs6476-problem-set-3-introduction-to-ar-and-image-mosaic-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123841&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6476 Problem Set 3- Introduction to AR and Image Mosaic Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (5 votes)    </div>
    </div>
NOTE: Please refer to the PDF file for instructions. GitHub markdown does not render formulae and algorithms correctly. The information is identical between the markdown and PDF, but the PDF renders more cleanly.

Assignment Description

Description

Problem Set 3 introduces basic concepts behind Augmented Reality, using the contents that you will learn in modules 3A-3D and 4A-4C: Projective geometry, Corner detection, Perspective imaging, and Homographies, respectively.

Additionally, you will also learn how to insert images within images and stitch multiple images together.

Learning Objectives

Learn how projective geometry can be used to transform a sample image from one plane to another. Address the marker recognition problem when there is noise in the scene.

Implement backwards (reverse) warping.

Implement Harris corner detection to identify correspondence points for an image with multiple views. Address the presence of distortion / noise in an image.

All tests in the autograder generate random scenes each time you submit your ps3.py script. Your functions should only return the information specified in each method’s description located in ps3.py. FAQs can be found in FAQ.md and instructions in README.md and README.pdf.

Part 2:

draw_box: A blank image and four random marker points are generated. Your output should return just the rectangle perimeter with a line thickness of 1. The number of nonzero pixels in this image should be close to the euclidean distances of each rectangle side: – dist(top_left,

bottom_left) + dist(top_left, top_right) + dist(bottom_right, top_right) + dist(bottom_right, bottom_left) Part 3:

get_corners_list: Your output is checked to see if it returns the right type and complies the ordering specified in the ps3.py documentation. find_four_point_transform: Random points are generated and, from these, a reference transformation matrix H is calculated. Your output is used to transform the reference points and verify them with a reference solution using the matrix H.

project_imageA_onto_imageB: Two random images are generated one with all zeros and the second one with a random gradient color configuration. The gradient image is then projected to the black image plane using a reference homography. Your output is then compared to a reference solution using the same similarity function provided in ps3_test.py.

video_frame_generator: A video path is passed to this function. The output is then verified for type and shape. After this, the number of frames counted by repeatedly calling the next() function is compared to the original number of frames.

We want to reiterate our advice about using Numpy indexing methods that can speed up your code. Nested for loops tend to be very slow in Python so try to avoid them whenever you can. Think about how you can implement these methods using linear algebra operations. This will be particularly useful for parts 3 – 6 in your report.

Remember that you should not post code on Piazza. Also, make sure you search this forum to see whether your question has been answered already before posting.

There are certain openCV functions that are not allowed. So far this is the preliminary list of banned function calls: cv2.findHomography

cv2.getPerspectiveTransform cv2.findFundamentalMat cv2.warpPerspective cv2.goodFeaturesToTrack cv2.warpAffine

The autograder is set to timeout after 60 seconds, which is plenty of time for these small tests to complete (~20 seconds total). If you receive a timeout message it means you need to optimize your code. Additionally, Gradescope has a global quota that is max 10 submissions in a 1h.
