# Identifying-Similar-Images-with-TensorFlow

You can launch this jupyter notebook in an executable environment by clicking on the button below.

[![Binder](https://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/shawngraham/bindr-test-Identifying-Similar-Images-with-TensorFlow/master)

[![DOI](https://zenodo.org/badge/132169566.svg)](https://zenodo.org/badge/latestdoi/132169566)

It's based on Douglas Duhaime's tutorial [identifying similar images with tensorflow](http://douglasduhaime.com/posts/identifying-similar-images-with-tensorflow.html) which is very clearly laid out and explained. In this notebook, I've compressed the steps. The 'images' directory only has 25 images in it for demo purposes. In Duhaime's post, the images folder (that you grab with `wget` has about 2000 images in it).

UPDATE
the `requirements.txt` file should list the python bits and pieces need to be installed, so that should save us from having to `!pip` install. There is a package called `RPy2` that can be loaded this way, that then lets us do bits and bobs of R mixed in with python - see [this post](https://medium.com/@mbussonn/baf064ca1fb6).

to get the R kernel so that I can have just an R notebook we need the `runtime.txt` file. Inside that, we have a single line that says `r-2018-04-01` (where the date stamp comes from [this](https://mran.microsoft.com/timemachine)).

to preload and R packages, put the name of the package in the `install.R` file in normal R syntax, like so: `install.packages("ggplot2")`.

And there we have it! Sometimes the binder fails to launch. Just reload. Keep reloading.

