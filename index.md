# Markdown assignment
## Overview
This document is for the GitHub Classroom markdown assignment.

## Octo cat-nobi
Here is a picture of obi-wan kenobi, but as a octopus-cat
![Image of Octobi Wan Catnobi](https://octodex.github.com/images/octobiwan.jpg)

## Code block
This code demonstrates converting a color image to grayscale in Python
``` python
def grayscale(img):
    """Converts image to grayscale"""

    gray = lambda v: 0.114 * v[0] + 0.587 * v[1] + 0.299 * v[2]
    return np.apply_along_axis(gray, 2, img)
```
