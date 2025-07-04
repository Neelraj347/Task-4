# Task-4
Name:NEEL RAJ GUPTA Company:CODETECH IT SOLUTION ID:CT04DF2936 Domain:C LANGUAGE Duration:5 JUNE 2025 TO 5 JULY 2025 Mentor:NEELA SANTHOSH KUMAR
Internship Report: Data Compression Tool in C Language
Introduction
During my internship, I developed a Data Compression Tool using C language to understand how data can be reduced in size for efficient storage and faster transmission. This project helped me learn the basics of data compression algorithms, file handling, and bitwise operations in C.

Objective
To understand data compression and its importance.

To implement a basic compression tool in C language.

To learn file handling and bitwise manipulation for compression.

To strengthen logical thinking and low-level programming skills.

What is Data Compression?
Data Compression reduces the size of data by eliminating redundancy, allowing:

Efficient storage on disks.

Faster data transmission over networks.

Reduced memory usage.

There are two types:

Lossless Compression: No data loss (e.g., ZIP, PNG).

Lossy Compression: Some data is lost for higher compression (e.g., JPEG, MP3).

In this internship, I implemented Lossless Compression using a simple Run-Length Encoding (RLE) algorithm.

Tools and Environment
Language: C

Compiler: GCC

Platform: Windows/Linux

Editor: Code::Blocks / VS Code

Implementation Details
1️⃣ Algorithm Used: Run-Length Encoding (RLE)
Run-Length Encoding compresses data by replacing repeated consecutive characters with a single character followed by its count.

Example:

makefile
Copy
Edit
Input:  aaabbbcc
Output: a3b3c2
2️⃣ File Handling
Used fopen, fgetc, fputc, and fclose for reading from and writing to files.

Handled file opening errors and end-of-file conditions safely.

3️⃣ Compression Logic
Read characters from the input file.

Count consecutive repeated characters.

Write the character followed by the count to the output (compressed) file.

4️⃣ Decompression Logic (Optional)
Read the compressed file.

Expand the character by repeating it according to the count.

Write the expanded data to a decompressed output file.

Sample Output
Input File:

nginx
Copy
Edit
aaaaabbccddd
Compressed File:

nginx
Copy
Edit
a5b2c2d3
Decompressed File:

nginx
Copy
Edit
aaaaabbccddd
Skills Learned
✅ Practical knowledge of data compression algorithms.
✅ File handling and buffer management in C.
✅ Use of bitwise and character manipulation for optimization.
✅ Debugging file-based programs.
✅ Understanding the importance of compression in data storage and transfer.

Challenges Faced
Handling special cases like single characters and large counts.

Managing file pointers and ensuring files are closed properly.

Maintaining data integrity during compression and decompression.

Conclusion
Through this internship project, I gained practical exposure to data compression concepts and implementation using C language, deepening my understanding of how systems manage and optimize data. This experience also prepared me for future work in systems programming, file systems, and low-level data processing.