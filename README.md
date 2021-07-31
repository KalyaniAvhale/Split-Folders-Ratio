# Split-Folders-Ratio
Split folders with files (e.g. images) into train, validation and test (dataset) folders.

## Install
pip install split-folders

## Usage
You can use split-folders as Python module or as a Command Line Interface (CLI).

If your datasets is balanced (each class has the same number of samples), choose ratio otherwise fixed. NB: oversampling is turned off by default. Oversampling is only applied to the train folder since having duplicates in val or test would be considered cheating.

## Reference 
https://pypi.org/project/split-folders/ 
