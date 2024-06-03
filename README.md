# Data Loading and Preprocessing

Through three different datasets (Adult, Beijing, and Solar), I address common data handling problems and demonstrate effective and efficient solutions.

## Datasets and Problems

### 1. Adult Dataset

The Adult dataset contains demographic information about individuals. This problem is tackled using two text files: `data` and `names`.

- **Problem**: The `names` file contains column names and descriptions in a general and extensive text format. We need to extract these names and convert the data into a DataFrame.
- **Solution**: We use regular expressions to extract the column names and then transform the data into a Pandas DataFrame.

### 2. Beijing Dataset

The Beijing dataset contains weather station information in compressed files.

- **Problem**: The data is in a zip file that needs to be downloaded, decompressed, and concatenated into a single DataFrame.
- **Solution**: We download the zip file using Python commands, decompress it into a folder, and concatenate all files in the folder into a single DataFrame. Subsequently, we clean the null values and remove duplicates to prepare the data for analysis.

### 3. Solar Dataset

The Solar dataset includes data from two separate sources (`Data1` and `Data2`) and a descriptive file of the variables.

- **Problem**: `Data1` and `Data2` are space-separated files, and the `names` file contains the possible variable names.
- **Solution**: We use regular expressions to extract relevant information from the `names` file. Then, we access `Data1` and `Data2`, transform them into DataFrames, and combine them to obtain a unified dataset.

## Skills Demonstrated

This repository is an excellent demonstration of my skills in:

- **File and Directory Handling**: Downloading and decompressing files, reading multiple files, and concatenating data.
- **Regular Expressions**: Extracting information from complex texts and structuring data.
- **Data Manipulation with Pandas**: Creating DataFrames, cleaning data, handling null values, and removing duplicates.
- **Process Automation**: Using loops and functions to automate repetitive tasks in data processing.

## Conclusion

This repository demonstrates how to tackle common data processing problems using Python. Through these examples, I showcase my skills in data manipulation and cleaning, as well as task automation, which are crucial for any data analysis project.