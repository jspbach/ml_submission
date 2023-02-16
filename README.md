# Submission package for COMP3020 final project

## Project structure

There are 3 folders: `clevr_processing`, `new_basic_vqa`, and `new_vqa`.

Folder `clevr_processing` contains the conversion module and the result of that conversion, stored as two annotation files in `clevr_processing\Annotations`.

Folders `new_basic_vqa` and `new_vqa` are modifications of their respective original repositories, designed to run with CLEVR dataset. Note that we have purposefully left out the .\datasets folder, since it is not necessary for the running of the model itself - the model only needs the two Annotation files. This will render the two folders impossible to run, however.

To run the two folders, download the CLEVR dataset to ./clevr_processing. Then, run the clevr_data_convert.py file and fix the dataset path in train.py.
