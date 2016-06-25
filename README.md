# spotteddick
Prudish image recognition

![Spotted Dick](images/spotteddick.jpg)

## Background

**Make sure you use the [GIT LFS](https://git-lfs.github.com/) extension before pulling this repo**

I plan to use Google Cloud Vision to screen for inappropriate content, but it seems a bit weak at spotting male organs. Unfortunately Google's SafeSearch is not open to additional training, so this project hopes to create one more "dickishness" score to supplement Google's SafeSearch.

Eventually I also want to flag suggestive dick pics, such as a well placed eggplant, banana, etc.

## Plan

1. Collect training sets (dicks / not_dics)
2. Use some learning library to build a model
3. Have a quick-and-dirty dick/not_dick classifier

## Libraries

I'm completely new to this, but I'll be considering the following libraries:

- [Numenta's Nupic](https://github.com/numenta/nupic)
- [Google's Tensorflow](https://www.tensorflow.org/versions/r0.9/tutorials/image_recognition/index.html#image-recognition)
