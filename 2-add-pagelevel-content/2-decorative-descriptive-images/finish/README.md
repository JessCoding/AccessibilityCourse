# 2. Decorative And Descriptive Images
For vision impaired users every image needs to provide a text alternative, which is a way for the user to understand what the image is describing. But if the image is decorative, this description is not required, in both instances though the ALT attribute is required.

## Activity
1. Add `ALT` text to images you think require a description and null `ALT` text to images you think should be ignored

## Solution
* Images which assist a user understanding the page have descriptive `ALT` text whilst decorative images have blank `ALT` text
```
<img class="card-img-top card-img-front correct" src="../../../assets/img/site/sandals.png" 
width="253" height="300" alt="open toe sandals">
```

## Live Demo
Decorative And Descriptive Images