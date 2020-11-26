## Configuration for Competitive Programming

### download_prob.py
Listens to a port of your local machine for json data of Competitive Companion
And downloads samples and copies files from your .template directory

### make_prob.sh
Copies all the files of .template and runs setup, which runs `bear -- make` to
generate a compile_commands.json to use clangd

### Makefile
Compiles and runs your code with all testcases and diffs the result and shows the output;

If you run `make test` in your terminal, it will test the result;
Or if you run `make` then it compile the programme with a lot of debugging flags

