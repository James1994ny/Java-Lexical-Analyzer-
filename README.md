# Java Lexical Analyzer 

The goal of the project is to implement a lexical analyzer that accepts the token categories plus the following keywords, all in lowercase letters only:
class, if, null

The lexical analyzer program reads in an input text file, extracts tokens in the text file, and write them out one by one on separate lines. Each token is flagged with its category. The output is sent to an output text file. Whenever invalid tokens are found, error messages are printed, and the reading process continues.

The following is a DFA to accept the 20 token categories.
The implementation is based on the DFA below.

 


![dfasp16](https://cloud.githubusercontent.com/assets/17654819/13732216/8e4a1192-e953-11e5-9aaf-4949cd239a76.jpg)
