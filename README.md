# AI_for_Industry_4.0
This project was created as a solution to a recruitment task. It contains a model used for predicting characteristing of fibre optic sensors in different enviroments based on measurements done in air.

A presentation offering an insight into the values of this implementation is included in the PDF document.

Task: https://drive.google.com/file/d/1WGQ8H6_l07yqe1JIQC1hQ6RWutZqqJbn/view

## Input
The input is a file containing wavelengths and amplitudes, in this order. These should represent a sensors measured characteristics in air.

## Usage 
Load the desired model in a ipynb or python interactive console using the load() function provided by the pickle library. Then use the model's predict(X) method on a compatible dataset, as described in the input section. Save results as needed.
