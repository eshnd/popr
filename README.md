<p align="center">
  <h1 align="center">Popr</h1>
</p>
<p align="center">A package manager for the Popcorn language<br>(by <a href="https://eshnd.github.io/">@eshnd</a>)<p>
  
### [Read the Popcorn docs →](https://github.com/eshnd/popcorn/wiki/Documentation)
## About
This package manager allows you to install local AND online libraries to your Popcorn kernel development projects.
## Install
You have to have popcorn installed before installing Popr. Once you have done so, this Popr install script works on *NIX (and WSL): `sudo wget -O /usr/local/bin/popr https://raw.githubusercontent.com/eshnd/popr/refs/heads/main/popr && sudo chmod +x /usr/local/bin/popr`
## Run
```
usage: popr [-h] [-s SET] [-a ADD [ADD ...]] [-i INSTALL [INSTALL ...]] [-c COMPILER]
            [-o OUTPUT] [-asm ASSEMBLY]
            [{run}]

positional arguments:
  {run}                 run the program

options:
  -h, --help            show this help message and exit
  -s, --set SET         sets your main file
  -a, --add ADD [ADD ...]
                        installs bundles to project
  -i, --install INSTALL [INSTALL ...]
                        installs online bundles to project
  -c, --compiler COMPILER
                        sets compiler
  -o, --output OUTPUT   sets output file
  -asm, --assembly ASSEMBLY
                        sets assembly output file
```
