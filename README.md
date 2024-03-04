# DataWizVizExtra

Extra visualization types for DataWizJS, such as histograms and scatter plots.

## Installation

Install DataWizVizExtra with npm:

npm install datawizvizextra

## Usage

To use DataWizVizExtra, import the library and call its functions:

const DataWizVizExtra = require('datawizvizextra');

const data = [1, 2, 3, 4, 5];
DataWizVizExtra.visualizeHistogram(data, 'histogram.png').then(console.log);

Features
Extends DataWizJS with additional visualization types like histograms.

Replace placeholders such as `'username'`, `'apiKey'`, and `'Your Name'` with your actual Plotly account details and name. Also, ensure that you have the `fs` module required where needed, as it's used to write the image stream to a file.
