# Genomics plc coding test

This task relates to interpolating missing values in some raw data.
The data used in this task represents, for example, a set of measurements
of protein expression for individuals in a selection of cell types.
For the purpose of the task, it has been determined that a reasonable methodological
approach to interpolating missing data is to infer missing values as the average of all
non-diagonal neighbouring values. 

# Task

Write a script, using a programming language of your choice which performs the task as follows:

- Reads the supplied input file `./input_test_data.csv`
- Writes out a new file named `<your name>_interpolated_data.csv`
- The output file should be in csv format with the same values from the input data
  where these are present, and missing values (represented as `nan`) from the input file
  determined by taking the mean of all existing non-diagonal neighbouring values
- The resulting `interpolated_data.csv` file should be returned to Genomics plc for checking
- Please save and retain the code used to perform the task, as this may be used for discussion
  at interview if your application is taken forward
