# Plain C/C++ API Fuzz Test
The file [API_Fuzz_Test.cpp](https://github.com/ci-fuzz/CI-Fuzz-Playground/blob/main/c_cpp/api_fuzzing/plain/fuzz_targets/API_Fuzz_Test.cpp) is 
an example for a C/C++ API fuzz test where with every input generated by the fuzzer, one function is called and the data coming from the fuzzer 
is used as parameters for this function.

To make this example easier to understand the code of the target software is also included in the same file as the fuzz test.