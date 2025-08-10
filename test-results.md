# Test Results

Since images are heavy files, we tried different variations to find the perfect balance between image quality and file size.

To find this balance, we tested it by putting all the images in an html file together and commented out the ones that either were not up to our quality standards, or weren't different enough to justify the file size.

We did the process of elimination in stages, with each stage getting more detailed into the acceptable range of the accepted images.

To make it more fun and clear, we'll proceed to talk about images as though they were participants in a competition that is slowly weeding out the weaker until eventually getting the winner.

## 1: Image resizing filter algorithms

The idea was to divide it into 3 categories: art, medium letter readability, and small letter readability. Each category would be independent from each other, referring to each image as a number so as to not show bias, and printing all the filters with each category.

The ones not passing would be commented out for each of 3 categories. And the finalists would be the ones that were not commented out for either of the 3, which would then be put into a competition of their own.

To see the best filter, the images were printed in various sizes.

**Results:**

Seeing them at different sizes, we concluded each filter were not different enough to compare and analyze 36 images 3 times. Also, since the images have both art and text, we noticed the ones with the clearer to read text were not necessarily the ones with the best art. The end image sizes were the real differentiator, so we couldn't bring ourselves to care enough to do the whole plan.

**Winner:**

- Lanczos
  - It is the most popular, and pretty well balanced, so good enough.


## 2: Image resizing final height

Here is the juicy stuff. With actual rounds and finalists for each round, we compared images at different sizes.

On the smaller end, an image was disqualified if it turned reading the medium text into any visual effort, and if the smaller text was unreadable even with zoom.

On the larger end, an image was disqualified if it wasn't that much of an improvement or difference related to its one-size-smaller sibling.

### Round 1: Rapidash red card

#### Round 1,2: 150 - 1200, 50 px steps

**Winner:**
- 450 - 900

#### Round 3: 450 - 900, 50 px steps

**Winner:**
- 600 - 750

#### Round 4,5,6: 600 - 760, 20 px steps

**Winner:**
- 640 - 740

