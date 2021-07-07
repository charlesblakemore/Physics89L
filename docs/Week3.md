# Notes and materials for Week 2

Topics covered:

* Announcements and information
  * "Answers" to questions from week 2 Lab.  Comments [here](Week2_after.md)

* Course material
  * [Data analysis topics](#Data%20analysis,%20topics)
  * [Scientific context](#Scientific%20context%20and%20resources)
  * [Python functions and tools reference](#Python%20functions%20reference)
  * [Template for "report" questions](null)

## Data analysis topics

This week we are going to be discussing how to interpret and estimate
measurement uncertainties. 

The statistical technique that will well cover is error propagation.

These topics are covered in chapters 3 and 4 of: "Measurements and Their Uncertainties : A Practical Guide to Modern Error Analysis" which is available online via the Stanford bookstore.  You don't need to read those chapters, but you may find them a useful reference, and they present the material in a somewhat different way than we will be presenting it, which you might find more intuitive.


## Scientific context and resources

We will also be measuring the area of the desk or table that we are
working at using a rather complicated (and inaccurate) technique that
captures some of the difficulty in measuring the Hubble constant, and
in particular the ["distance ladder"](https://en.wikipedia.org/wiki/Cosmic_distance_ladder) that is used to calibrate the
distances to faraway galaxies.

We will also briefly mention the gamma-ray pulsar, Vela, which we will be seeing more of next week.

## Python functions reference

| Function Name            | What it does |
| - | - |
| numpy.var                | Compute the variance of the values in an array |
| numpy.random.normal      | Generate random numbers from a normal or 'Gaussian' distribution |
| array.size               | return the number of elements in an array |
| array.shape              | return the shape of an array, i.e., arrays can have more that one dimension and this function tells you  the shape of the array.  The size of the array is the product of the size of all the axes of the array |
| plt.imshow               | Plot a 2-dimensional array of values as a color image |
| plt.colorbar             | Attach an color axes label to a figure |
| plt.legend               | Attach a legend to a figure |

<!--  LocalWords:  numpy.var plt.imshow plt.colorbar plt.legend
 -->