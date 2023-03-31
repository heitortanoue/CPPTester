# CPPTester
CPPTester is a command-line program for testing C++ programs against input/output examples. It's useful for automating the testing process of C++ projects and ensuring that the code behaves correctly in a variety of situations.

## Usage
To use CPPTester, you need to provide the name of the folder where your project is located as an argument. The folder should contain a main.cpp file, which is the program you want to test, and a `tests` folder, which should contain input and output files for each test case. The input files should have the `.in` extension, and the output files should have the `.out` extension.

Here's an example of how to use CPPTester:

```shell
$ ./CPPTester /path/to/my/project
```
Dependencies

## How it works
CPPTester works by iterating over all the files in the tests folder and running the program specified in main.cpp with the input from each .in file. It then compares the output of the program with the contents of the corresponding .out file and reports whether the test passed or failed.

If a test fails, CPPTester outputs the expected output and the actual output side by side so you can easily compare them.

## License
CPPTester is released under the MIT License.
