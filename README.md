# HelloCommandLine
A variety of language examples for creating the ubiquitous "Hello, World!" command line program.

## HelloBashShell
Written using Visual Studio Code in the bash shell programming language, this is the minimal code you might find in a command line program and how to run it.

### Running the program
```
$ cd ~/oca/HelloCommandLine/HelloBashShell/
$ chmod +x HelloBashShell.sh
$ ./HelloBashShell.sh
Hello, bash shell
```

![HelloBashShell](https://user-images.githubusercontent.com/15971213/34274569-0829fbdc-e64e-11e7-8308-bc8f9a03aeb0.png)

## HelloJavascript
Written using Visual Studio Code in the Javascript programming language, this is the minimal code you might find in a command line program and how to run it. Here, I assume that you have Node already installed.

### Running the program
```
$ cd ~/oca/HelloCommandLine/HelloJavascript/
$ chmod +x HelloJavascript.js
$ ./HelloJavascript.js
Hello, Javascript
```

If this doesn't run, trying running `which node` to determine where your Node is installed and then update the first line of the script as necessary.

![HelloJavascript](https://user-images.githubusercontent.com/15971213/34272156-0d21a98c-e644-11e7-8f4d-50b61aef1b14.png)

## HelloGo
Written using Visual Studio Code in the Go programming language, this is the minimal code you might find in a command line program and how to compile it.

### Running the program
```
$ cd ~/oca/HelloCommandLine/HelloGo/dist/
$ ./HelloGo
Hello, Go
```

### Installation

You would need to install the [Go language compiler](https://golang.org) on your workstation in order to compile this project. Having done so, proceed.

```
$ cd HelloCommandLine/HelloGo
$ code .

```

![HelloGo](https://user-images.githubusercontent.com/15971213/34271713-60f097aa-e642-11e7-860d-cb6c42239314.png)

1. Edit the `main.go` program file, as necessary
2. In the Terminal window of VS Code, enter `go run main` to execute it
3. Again in the Terminal window of VS Code, enter `go build` under the project folder to build it into an executable program
5. Copy the `HelloGo` program file to somewhere in your path for the sake of convenience when you're finished

## HelloC
Written using XCode in the C programming language, this is the minimal code you might find in a command line program and how to compile it.

### Running the program
```
$ cd ~/oca/HelloCommandLine/HelloC/dist/
$ ./HelloC
Hello, C (OS X)
```

### Installation

You would need to install XCode on your workstation in order to compile this project. Having done so, proceed.

```
$ cd HelloCommandLine/HelloC
$ open HelloC.xcodeproj

```

![HelloC](https://user-images.githubusercontent.com/15971213/34271234-406a94a6-e640-11e7-893e-4a5b6529cb46.png)

1. Edit the `main.c` program file, as necessary
2. Press the Run button to compile/run it
3. Select the `HelloC` entry under Products, copy the Full Path as seen in the Identity and Path panel on the right
4. In Finder, press Shift-Cmd-G and paste everything from this path except for the filename
5. Copy the `HelloC` program file to somewhere in your path for the sake of convenience when you're finished

## HelloObjectiveC
Written using XCode in the ObjectiveC programming language, this is the minimal code you might find in a command line program and how to compile it.

### Running the program
```
$ cd ~/oca/HelloCommandLine/HelloObjectiveC/dist/
$ ./HelloObjectiveC
Hello, ObjectiveC (OS X)
```

### Installation

You would need to install XCode on your workstation in order to compile this project. Having done so, proceed.

```
$ cd HelloCommandLine/HelloObjectiveC
$ open HelloObjectiveC.xcodeproj

```

![HelloObjectiveC](https://user-images.githubusercontent.com/15971213/34270894-c0a1470c-e63e-11e7-8f80-3bd82d437343.png)

1. Edit the `main.m` program file, as necessary
2. Press the Run button to compile/run it
3. Select the `HelloObjectiveC` entry under Products, copy the Full Path as seen in the Identity and Path panel on the right
4. In Finder, press Shift-Cmd-G and paste everything from this path except for the filename
5. Copy the `HelloObjectiveC` program file to somewhere in your path for the sake of convenience when you're finished

## HelloCPlusPlus
Written using XCode in the C++ programming language, this is the minimal code you might find in a command line program and how to compile it.

### Running the program
```
$ cd ~/oca/HelloCommandLine/HelloCPlusPlus/dist/
$ ./HelloCPlusPlus
Hello, C++ (OS X)
```

### Installation

You would need to install XCode on your workstation in order to compile this project. Having done so, proceed.

```
$ cd HelloCommandLine/HelloCPlusPlus
$ open HelloCPlusPlus.xcodeproj

```

![HelloCPlusPlus](https://user-images.githubusercontent.com/15971213/34276225-502bdb06-e655-11e7-96b6-76750eae6aa7.png)

1. Edit the `main.cpp` program file, as necessary
2. Press the Run button to compile/run it
3. Select the `HelloCPlusPlus` entry under Products, copy the Full Path as seen in the Identity and Path panel on the right
4. In Finder, press Shift-Cmd-G and paste everything from this path except for the filename
5. Copy the `HelloCPlusPlus` program file to somewhere in your path for the sake of convenience when you're finished

## HelloC#
Written using VS Code in the C# programming language and compiled using the MonoDevelop version of Xamarin, this is the minimal code you might find in a command line program and how to compile it. Note that running .Net programs in OS X isn't really *native* and this requires a wrapper program called `mono` which provides that framework. 

### Running the program
```
$ cd ~/oca/HelloCommandLine/HelloC#/dist/
$ mono HelloC#.exe
Hello, C# (Mono/Xamarin)
```

### Installation

You would need to install XCode and VS Code on your workstation plus the [Xamarin Studio IDE from MonoDevelop](http://www.monodevelop.com/download/) in order to compile this project. Note that you can code in either Xamarin or VS Code but only the former can compile these files. (Note that this is at least 1.5GB of files.) I will describe the code-in-VSCode version here.

![Xamarin and Mono](https://user-images.githubusercontent.com/15971213/34277473-b8457080-e65a-11e7-8075-c7bcf9c962f4.png)

Having installed the prerequisites and any necessary prompted Mono framework file(s) and closed all terminals that were previously open, proceed.

```
$ cd HelloCommandLine/HelloC#
$ code .

```

![HelloC#](https://user-images.githubusercontent.com/15971213/34278486-fb1f3f4e-e65f-11e7-8a68-95669da8774c.png)

1. Edit the `main.cs` program file, as necessary
2. In the terminal area, enter `mcs -out:dist/HelloC#.exe main.cs` to compile the code
5. Copy the `HelloC#.exe` program file to somewhere convenient for the sake of convenience when you're finished, noting that the `mono` command line needs to find it

## HelloSwift
Written using XCode in the Swift programming language, this is the minimal code you might find in a command line program and how to compile it.

### Running the program
```
$ cd ~/oca/HelloCommandLine/HelloSwift/dist/
$ ./HelloSwift
Hello, Swift (OS X)
```

### Installation

You would need to install XCode on your workstation in order to compile this project. Having done so, proceed.

```
$ cd HelloCommandLine/HelloSwift
$ open HelloSwift.xcodeproj

```

![HelloSwift](https://user-images.githubusercontent.com/15971213/34269815-b003bc6c-e63a-11e7-9f8e-601054787e09.png)

1. Edit the `main.swift` program file, as necessary
2. Press the Run button to compile/run it
3. Select the `HelloSwift` entry under Products, copy the Full Path as seen in the Identity and Path panel on the right
4. In Finder, press Shift-Cmd-G and paste everything from this path except for the filename
5. Copy the `HelloSwift` program file to somewhere in your path for the sake of convenience when you're finished

## HelloPython
Written using Visual Studio Code in the [Python programming language](https://www.python.org/downloads/), this is the minimal code you might find in a command line program and how to run it. Having done so, proceed.

### Running the program
```
$ cd ~/oca/HelloCommandLine/HelloPython
$ chmod +x HelloPython.py
$ ./HelloPython.py
Hello, Python
```

### Installation

You would need to install the [Python language](https://golang.org) on your workstation in order to run Python scripts. Since these scripts aren't compiled, just run them as shown above. 

![screen shot 2017-12-21 at 3 39 00 pm](https://user-images.githubusercontent.com/15971213/34279338-2fe18084-e665-11e7-9e09-7926a6d0802b.png)
