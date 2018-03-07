# PandC
Producers and Consumers Sample Solution

Please bear in mind that this is a work in progress. Right now it certainly isn't complete, and what actually *is* there might be wrong.

# Instructions
1. Clone the repository:
```
$ git clone https://github.com/mikebradytcd/pandc.git
```
This will create a subdirectory called `pandc`.

2. `cd` into the subdirectory:
```
$ cd pandc
```
3. Configure the files and directories needed for `autotools` to run properly:
```
$ autoreconf -fi
```
4. Now generate the `Makefile` needed to build the application:
```
$ ./configure
```
5. Finally, make the application:
```
$ make
```
Now, whenever you make changes to the source file `pandc.c` you can simply enter `$ make` to recompile and relink the application.

If the github repository is updated, all you have to do is:
```
$ git pull
```
to download the updates. You may have to repeat steps 2 to 5 to recompile the application correctly.

To keep the code nicely formatted, I suggest you use `clang-format`:

```
clang-format -i pandc.c
```
