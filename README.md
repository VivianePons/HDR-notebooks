# HDR-notebooks

This repo contains some Sage Jupyter notebooks related to my *Habilitation à diriger des recherches*.

This has been built using SageMath version 9.5

## Installation

Most of the code can be run using only SageMath.

For certain pictures, you also need `graphviz`, `imagemagick`, and `dot2tex`

    sudo apt-get -qy install imagemagick
    sudo apt-get -qy install graphviz
    sage -pip install dot2tex
    
For showing LaTex built images into Jupyter notebooks, you would need to replace the imageMagick policy file found in `/etc/ImageMagick-6/policy.xml` by the file provided in this repo.
