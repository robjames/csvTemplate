#CSV Template

A simple html page to take csv data and merge it with a predefined template.

##Usage

Simply add your CSV data.

Then build your template. The `{{0}}` will be replaced with the index in that data set.

`<name>{{0}}</name><age>{{1}}</age>`

Optionally add "wrapping" markup to your template and ignore rows of the dataset.