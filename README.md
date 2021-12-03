# Encryption Coding

## SNHU CS-405 5-2 Activity: Encryption Coding

[Encryption Coding](https://github.com/rowland007/Encryption-Coding) by [Randall Rowland](https://randyrowland.me) is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1) <img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1">

# Overview

You are a senior software developer on a team of software developers who are responsible for a large banking web application. Your manager has recently discovered that none of the data is encrypted. She is panicking and now wants to put encryption into everything. However, she wants some proof of how it works. Another developer on the team started creating the application to show encryption, but cannot figure out how to load and save files or to do encryption. The task has fallen to you to finish the work.

# Prompt

You will learn to do the following:
- Implement XOR-based encryption character by character across a file of data
- Implement loading data from a text file into a string
- Save a string to a text file

The source code has been commented on using `TODO` to explain the detailed rules you must follow. When implementing XOR encryption, you will need to account for the length of your password key. See the example file in the module resources section. The file format that is loaded and saved is defined in the source code. You must use the format specified for the program to work. You are provided a sample input file to test your program, and you will need to change the data file to complete the assignment. Use the file names defined in the source code file, and don’t forget that you can leverage capabilities provided by the standard C++ library to help you achieve success.

Specifically, you will need to complete the following:
- **Code XOR Encryption**: Complete the coding acti vity by successfully implementi ng XOR encrypti on, accounti ng for key lengths.
- **Code the Loading of a Text File**: Complete the coding acti vity by successfully implementi ng the logic to read a text file in the specified format into a string in the `read_file` method.
- **Code the Saving of a Text File**: Complete the coding acti vity by successfully implementi ng the logic to save a text file in the specified format in the `save_data_file` method.
- **Data Files**: Create an original data file in the specified data format, produce the encrypted and decrypted data files, and ensure all file names match the source code defined file names.
- **C/C++ Program Functionality and Best Practices**: Demonstrate industry standard best practices, including in-line comments and appropriate naming conventions to enhance readability of code. Develop functional C/C++ code that illustrates a software design pattern approach.
- **Process Summary**: Provide a summary of the debugging that is thorough and systematic, including specific types of bugs, and accurately describe the corrections.