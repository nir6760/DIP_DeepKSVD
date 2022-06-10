# DIP_DeepKSVD
DIP Course Project - On Deep KSVD Paper

# Deep K-SVD Denoising
Created for DIP Course, small improvement and changes for the original code (link below), a review and explanations are attached in the PDF file.<br /> 
Original code and credit - Code of the paper by Meyer Scetbon, Michael Elad and Peyman Milanfar <br /> 
on https://github.com/meyerscetbon/Deep-K-SVD

## Intro: A Differentiable version of the K-SVD Denoising algorithm
This work considers noise removal from images, focusing on the well known K-SVD denoising algorithm. The approach that was taken here  is to redesign the algorithm to operate in a supervised manner. The implementation is an architecture with the exact K-SVD computational path and with Deep-Learning methods involved.<br />
Citation from the original : Adopting a broader context, this work touches on themes around the design of deep-learning solutions for image processing tasks, while paving a bridge between classic methods and novel deep-learning-based ones. 

## Structure of the Code
src/DeepKSVD.ipynb - Main training and testing notebook.<br />
src/Deep_KSVD_NirOren.py - Implementation of the algorithm and our changes.<br />
src/gray - The photos folder (train and test).<br />
src/train_gray.txt - List of the train images.<br />
src/test_gray.txt - List of the test images.

## Repository Running Instructions-
1. Clone the repository and open DIP_DeepKSVD.ipynb with google colab notebook (or a local one).<br />
2. Upload all the other files to the same folder (use a zip file to load gray folder) and run DeepKSVD.ipynb (First training section, then loading and testing).

