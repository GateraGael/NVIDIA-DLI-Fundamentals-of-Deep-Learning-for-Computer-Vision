# Biological Inspiration
Explained the limitations of step-by-step computer instructions, algorithms. 
This constraint limited computer scientists to only be able to solve:
1. Problems they understood clearly
2. Can describe the solution with step-by-step instructions that a computer can understand.

The course then challenges students to classifiy a handwritten "2"
1. Using pseudo-code
2. To a 2 year old just learning about numbers

My answers here:
#### Pseudo Code

All numbers until infinity have a specific score repesented by a tuple depending on the amount of color channels.
In other words, any arbitray number that is represented by an RGB image is meant to have (n score red in red channel, n score in green channel, n score in blue channel).
This example makes things a bit easier for us in the sense that it is a binary image.
So we have 2 dimensions where row, column combination is wither 0 (black) or 1 (white).

```stdin
black_pixels_score = 0
white_pixels_score = 0

for row_p in height_image:
   for column_p in width_image:
      if (row_p, colmn_p) == 0:
         black_pixels_score += 1
      else:
         white_pixels_score += 1

real_2 = (67, 83)

fake_2 = (black_pixels_score, white_pixels_score)

if fake_2 == real_2:
   correct_classification
else:
   false_classification

```


# Deep Neural Networks: GPU Task 1

