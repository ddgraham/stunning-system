Copy the header information from one file:
> sed -n 1p some_file.csv > merged_file.csv

Copy all but the last line from all other files:
> sed 1d other_files.csv >> merged_file.csv 
