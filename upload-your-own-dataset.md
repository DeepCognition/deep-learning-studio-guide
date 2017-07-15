## Data Format:

Deep Learning Studio can support any kind of data type. It has built-in support for number, strings and images. For other data types, it provides a way for user to encode and import.

For image data, it supports all the popular image formats. Each image needs to be given as a single file path.

For text data, it provides array format. User has to externally encode the text into sequence of indexes. This indexes can be concatenated into strings seperated by semicolon\(;\) \(e.g '687;23;4;2;2;6;3693;42'\)

For arbitrary data types, it supports numpy encoding. User can load single record of data into numpy and save the record in .npy\(uncompressed\) or .npz\(compressed\) format.

## Dataset Format:

Deep Learning Studio expects uploaded dataset in the following format:

A zip file containing train.csv \(or test.csv for test dataset\) under the top directory. All the files referenced in the CSV file should be present in the zip file in the respective folders \(relative to the CSV file\)

The CSV file has comma separated columns. A column can contain numbers, strings, arrays or file paths.

* Array data must be encoded as string separated using semicolon\(;\). 
* The file path must be relative to the directory containing the CSV file. 
* The column value can not be empty. 

A row in CSV file can contain any combination of data type.The CSV file should contains all the data or the reference to the files containing the data for training, validation and test\(optional\).

