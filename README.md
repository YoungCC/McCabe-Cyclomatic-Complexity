# McCabe-Cyclomatic-Complexity

Project description: Modified the scanner and parser in MyPy to compute McCabe’s complexity. The metric results matched exactly with those provided by the flake8 McCabe module. I wrote 6 test cases and added some other python files from the directory Python-2.7.2 to test my complexity tool. All of them passed. I also handled the memory leak problem and avoided double free error.  

Problems that I had in completing this project: How to improve MyPy for fitting more cases.