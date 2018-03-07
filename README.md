# pandc
Producers and Consumers Sample Solution

Please bear in mind that this is a work in progress. Right now it certainly isn't complete, and what actually *is* there might be wrong.

# Instructions
* Clone the repository:
```
$ git clone https://github.com/mikebradytcd/pandc.git
```
This will create a subdirectory called `pandc`.
* `cd` into the subdirectory:
```
$ cd pandc
```
* Configure the files and directories needed for `autotools` to run properly:
```
$ autoreconf -fi
```
* Now generate the `Makefile` needed to build the application:
```
$ ./configure
```
* Finally, make the application:
```
$ make
```
Now, whenever you make changes to the source file `pandc.c` you can simply enter `$ make` to recompile and relink the application.
