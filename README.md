# Hopfield neuro network

## Description

This project is naive (and, therefore, simple!) implementation of Hopfield neural network.
The goals for this project are:

1. Keep implementation simple, easy to understant and free for further experiments
2. Show basics how neural network work and learns
3. Follow strong math basics described by G.G. Matinetsky (see links)

## How to run

There are 3 'reference' images and 2 'noisy' images. See 'images_to_learn' and 'noisy_examples' folders for details.

Example:

$ ./hopfield 10 10 ../noisy_example/src.txt ../images_to_learn/*.txt

## How to build

This project is based on CMAKE build system (cmake version 3+). So, just execute:

### Ubuntu

$ mkdir build ; cd build

$ cmake ..

$ make

### Windows (Visual Studio)

1. Download and install CMAKE
2. Open console at repository folder
3. $ mkdir build ; cd build
4. $ cmake ..
5. Open generated solution with Visual Studio and compile it ordinal way

## Links:

1. Г.Г. Малинецкий. Математические основы синергетики. Москва, URSS, 2009 [In Russian]
