# Project: What are Sine, Cosine, and Tangent?

This is an individual project done in groups.  You are going to measure the sides and angles of right triangles.  Then, you will do calculations to see how close your calculations are to your measurements.  It will be done in two parts.  Part 1 is the measuring of triangle sides and angles.  Part 2 is calculating the three trigonometry functions and comparing the calculated to the measured.

Tools needed:
* Paper
* Writing utensil
* Tape measure for the group
* Protractor for the group
* Calculator (for part 2)

## Part 1 - Measuring and calculating ratios (10)

You need to split your paper into three columns as shown below.

Sketch, Lengths, and Angles | 3 Ratios of angle A and angle B (6 total ratios) | Sine, Cosine, Tangent of A and B (6 calculations) | How close? (Percent Difference)
--------------------------- | ------------------------------------------------ | ------------------------------------------------- | ---------------------------------
Draw and label 5 right triangles | Calculate the ratios for angle A: a/c (sine), b/c (cosine), and a/b (tangent) and the ratios for angle B: b/c (sine), a/c (cosine), and b/a (tangent) | Calculate the sine, cosine, and tangent for angle A and for angle B (make sure to label so that you know which is which) | Calculate the percent difference for each of the six calculations using the calculated values as your standard

You will measure the three sides and three angles of 5 right triangles.  Measure to the distances to the nearest 1/8" and the angles to the nearest half degree.  There may be several triangles with the same side lengths or very close, do not two that are within an inch of side length measures.

You can use a figure like the following.  Notice that the longest side is labeled c.  (Remember that this is called the hypotenuse.)  The angles are labeled with capital letters and are the same as the side opposite them.  Angle C is the right angle (at least it is very close to a right angle - remember that a right angle has a measure of 90 degrees).

          |\
          |A\
          |  \
     b    |   \   c
          |    \
          |     \
          |C    B\
          --------
              a

After you measure all the sides and angles, calculate ratios.  Remember that ratios are just divisions.  Make sure to label your ratio calculations using the sides that you divide.  This will help you to know which trigonometry function to compare it to.  You could even label the ratio with sine and cosine and tangent to help you remember.  You can make a table like the following in your table to show these calculations.

Trig function | ratio | ratio calculation | trig calculation (part 2)
------------- | ----- | ----------------- | -------------------------
sine A | a/c = measure a / measure c | actual calculation of a/c | actual calculation of sin(A)
cosine A | b/c = measure b / measure c | actual calculation of b/c | actual calculation of cos(A)
tangent A | a/b = measure a / measure b | actual calculation of a/b | actual calculation of tan(A)
sine B | b/c = measure b / measure c | actual calculation of b/c | actual calculation of sin(B)
cosine B | a/c = measure a / measure c | actual calculation of a/c | actual calculation of cos(B)
tangent B | b/a = measure b / measure a | actual calculation of b/a | actual calculation of tan(B)


## Part 2 - Calculations and Comparisons (20)

Use your calculator to calculate sine A, cosine A, tangent A, sine B, cosine B, and tangent B.  These are usually notated as sin(A), cos(A), tan(A), etc.  Depending on your calculator, you will either press the function first and then input the angle value or you will input the value of the angle first and then press the function key.

Now, to find out how close we are, we need to consider which is our standard and subtract and divide from it and convert this to a percentage.  This will be done in a few steps below.  But first a couple conventions on notation.

We will use the calculated sine, cosine, and tangent values as the standards.  So sin(A<sub>m</sub>) will represent the measured value of sine of the measured angle A.  We are comparing the sine, cosine, and tangent values to the ratios of our measured sides.  (You could argue that your measurements for lengths are more accurate, so you could use the ratios you calculated as the standard values.  And you may do this in your lab if you indicate you want to do that.)

If you would like to make a table for the values and calculations, you could make something like the following (shown only for sine):

sin(A<sub>m</sub>) | a/c | difference (diff) | normalized decimal difference | % difference
------------- | ------------- | ----------------- | ------------------ | ------------
The calculated sine sin(A<sub>m</sub>) | a/c | diff = sin(A<sub>m</sub>) - a/c | diff<sub>n</sub> = diff / sin(A<sub>m</sub>) | %diff = diff<sub>n</sub> * 100%

An example

```
          |\
          |A\
          |  \
     b    |   \   c
          |    \
          |     \
          |C    B\
          --------
              a

A = 30°       a = 2.500 inches
B = 60°       b = 4.500 inches
C = 90°       c = 5.125 inches
```

trigFn(Angle<sub>m</sub>) | side1/side2 | difference (diff) | normalized decimal difference | % difference
--------------------- | ----------- | ----------------- | ----------------------------- | ------------
sin(30°) = 0.500 | a/c = 0.488 | diff = 0.500-0.488 = 0.012 | diff<sub>n</sub> = diff / sin(A<sub>m</sub>) = 0.0120/0.500 = 0.024 | %diff = diff<sub>n</sub> * 100% = 0.024 * 100% = 2.4%
cos(30°) = 0.868 | b/c = 0.878 | diff = 0.868-0.878 = -0.012 | diff<sub>n</sub> = diff / cos(A<sub>m</sub>) = -0.012/0.866 = -0.0139 | %diff = diff<sub>n</sub> * 100% = -0.0139 * 100% = -1.39%
tan(30°) = 0.577 | a/b = 0.556 | diff = 0.577-0.556 = 0.021 | diff<sub>n</sub> = diff / tan(A<sub>m</sub>) = 0.021/0.577 = 0.0364 | %diff = diff<sub>n</sub> * 100% = 0.0364 * 100% = 3.64%
sin(60°) = 0.868 | b/c = 0.878 | diff = 0.868-0.878 = -0.012 | diff<sub>n</sub> = diff / sin(B<sub>m</sub>) = -0.012/0.866 = -0.0139 | %diff = diff<sub>n</sub> * 100% = -0.0139 * 100% = -1.39%
cos(60°) = 0.500 | a/c = 0.488 | diff = 0.500-0.488 = 0.012 | diff<sub>n</sub> = diff / cos(B<sub>m</sub>) = 0.0120/0.500 = 0.024 | %diff = diff<sub>n</sub> * 100% = 0.024 * 100% = 2.4%
tan(60°) = 1.732 | b/a = 1.800 | diff = 1.732-1.800 = -0.068 | diff<sub>n</sub> = diff / tan(B<sub>m</sub>) = -0.068/1.732 = -0.068 | %diff = diff<sub>n</sub> * 100% = -0.068 * 100% = -3.93%

One note about using a calculator to find %diff.  When you find the percent difference, the percent sign (%) in the equation is not used in your calculator.  It is just a symbol you use when recording your findings.  If you multiply any number in your calculator by 100%, it is the same as multiplying by 1.  So make sure that when you multiply on your calculator you just multiply by 100 and when recording the value, put the percent sign (%) behind it.  You can make sure you did not make this error by looking at the diff<sub>n</sub> and %diff and making sure they are not the exact same number.

Some of the same notes about % difference are on the [linked page](https://github.com/MichaelTMiyoshi/AppliedMathWithMiyoshi/blob/main/AppliedAlgebra2/Projects/03-PercentDifferenceExplanation.md), but that page is in a more general form.
