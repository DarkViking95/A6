# A6
Saturday, May 2 11:59 p.m.
Assignment 6
By: Ethan Bohling

Functions done:
sort(); // Implements an O(N) Counting Sort to efficiently group the sample records by their 5 unique species codes.
searchSample(); // Seeks into the binary file to find a specific sample and checks if it is a valid (non-deleted) record.
p_index(); // Populates the index array by finding the starting index for each of the 5 species codes in the sorted array.
p_displayResearcher(); // Retrieves and displays the researcher name for a specific gene sample record directly from the binary file.
p_updateResearcher(); // Modifies and saves a new researcher name for a specific record directly in the binary file.
p_deleteSample(); // Performs a logical deletion of a record in the binary file by setting its sampleID to -1.
p_printRange(); // Reads and prints a specified range of valid sample records for a given species code.

How to compile/run program
To compile: type make in terminal
To run: type ./a.out
