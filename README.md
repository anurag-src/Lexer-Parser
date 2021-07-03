# Lexer-Parser

### :busts_in_silhouette: The Team
* Varun Naryanan
* Anish Sai Mitta
* Himnish Kapoor
* Anurag Sidharth Aribandi

### 🔎 About
* The project consists of a lexer and a parser, both compatible with each other.
* The language syntax is similar to that of C and C++ syntax, instead of semicolons to end statements, colons are used.
* The language supports any variable or function name other those with special characters like '@'.
* Before every function name and after its return type the keyword 'fun' must be specified and the last statement of the function must be followed by the keyword 'endfun'.
* The language similarly supports loops and if statements.
* The language supports in built print and scan functions.
* See the test codes in the "Test_Codes" folder to get a better idea.
* The parser is an LL Parser.
* The CFG is provided in the pdf and the parsing table is provided in the Parser folder.
* Synch, Skip and Terminal errors are handled by the parser and the line number that causes the error is specified.

## Lexer

### :key: Run the Project
* Ensure that the header file, driver,lexer and code txt input files are in the same folder.
* Compile the code with the command "g++ lexer.cpp driver.cpp -o main".
* Run the code with the command "./main test_case1.txt output.txt", the first file name is the code txt file, the second is the output file name that will be generated

### :star: Output
* The output a file that contains the lexemes and their corresponding token pairs.
* The line number of hte lexeme is also specified
* The "Lex_Output" folder contains outputs corresponding to the code test cases (output1 corresponds to the test_case1 txt file)
