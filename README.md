# CPPTester
CPPTester is a command-line program for testing C++ programs against input/output examples. It's useful for automating the testing process of C++ projects and ensuring that the code behaves correctly in a variety of situations.

## Usage

To use CPPTester, navigate to the directory containing the `cpp-tester.cpp` file and compile it using a C++ compiler of your choice. Here's an example of how to compile it using g++:

```shell
g++ -std=c++17 cpp-tester.cpp -o cpp-tester
```

Once compiled, you can run CPPTester by passing the name of the folder containing your C++ program and the test cases as a command line argument. Here's an example:

```shell
./cpp-tester <folder>
```
Where <folder> is the name of the folder containing your C++ program and the test cases. The folder should contain a `main.cpp` file, which is the program you want to test, and a `tests` folder, which should contain input and output files for each test case. The input files should have the `.in` extension, and the output files should have the `.out` extension.

## How it works
CPPTester works by iterating over all the files in the tests folder and running the program specified in main.cpp with the input from each .in file. It then compares the output of the program with the contents of the corresponding .out file and reports whether the test passed or failed.

If a test fails, CPPTester outputs the expected output and the actual output side by side so you can easily compare them.

## License
CPPTester is released under the MIT License.
