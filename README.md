# Texture Generator
Copyright (c) 2019 Liam Wynn

Using varational autoencoders to generate textures

# Overview
This is an attempt to build a texture generating system for [raycore](https://github.com/wynnliam/raycore).

The textures that are generated have the following properties:
* All textures are 64 x 64 pixels
* All textures are currently grayscale

## Running a model
To use any model, navigate to `src/` and choose a model of your interest. Next,
grab the folder of your choosing (right now, there is only 'honeycomb'), and upload it
to your Google drive.

Then go to your google drive, and navigate to `[texture_model]/model/model.ipynb`. Open
this file up with Google Colab. Now run each of the blocks of python code top to bottom.
The last block should generate 10 examples based on the inputs you give it.

# Licensing
This program is licensed under the "MIT License". Please see `LICENSE` in the source distribution of this
software for license terms.
