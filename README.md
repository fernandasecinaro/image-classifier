# Dog breed classifier

WARNING! This project is meant to be used in systems based on MacOS.

## Steps to run project

### Environment Setup (Requirements)

Make sure you have homebrew and xcode installed.

### Tools Setup

With the tools mentioned above installed, you can now install the tools needed:<br> 3. Run `make install-tools`. This will install general tools<br> 4. run `source ~/.zshrc` or open a new terminal for the changes to take effect

### Project Setup

Run `make project-install`

## Usage

To predict a new image:

1. Add the image to "extra-images" folder

2. Go to "4-predict.ipynb" file

3. Change the argument of the "predict" call (second cell) to the filename you want to predict
