# shell-scripts
Collection of shell scripts to customize what I can do with the command line and also to learn cool things in the process

## Steps to create a custom command


1. Create a directory say "bin" under your home directory.
2. Update your path variable to include this bin directory. Put this in `.profile` or `.bash_profile` file to make it permanent.
   `export PATH=$PATH":$HOME/bin"`
3. Create a script say, "hello" and keep it in your bin directory. Give execute permission to the hello script<br>
   `$ chmod +x hello`
4. Wirte the contents to the script<br>
   `#!/bin/bash`    
   `echo My first program`
5. Reload `.profile` or `.bash_profle:`<br>
   ` $ source ~/.bash_profile`
6. From any directory, you simply type:<br>
   `$ hello`<br>
   `My first program`


