# robotic-pizza-automation
Robotic Pizza Automation with Robotic Process Automation

All credits to [@kensoh](https://github.com/kensoh)

## Setup Instructions
[TagUI setup](https://github.com/kelaberetiv/TagUI#set-up)

## Visual Automation
1. Check that Java JDK [64-bit](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) is installed (entering java -version returns your Java version)
2. Download [sikulix.jar](https://raiman.github.io/SikuliX1/sikulix.jar) and save it into src/sikulix folder. You need this to interact with desktop applications.

## Usage
1. copy the files into /tagui/src folder and cd into /tagui/src
2. Replace your Dominos login details.
3. Replace the email details with your own if you wish to send email notifications.
4. Replace Pushed app_key and app_secret if you wish to send Pushed notifications.
5. Run the following code in the command line.

```sh
$ ./tagui robotic-pizza-automation
```
6. Alternatively, [create a bash script(MacOS)](https://www.hastac.org/blogs/joe-cutajar/2015/04/21/how-make-simple-bash-script-mac) or [batch script(Windows)](https://www.howtogeek.com/263177/how-to-write-a-batch-script-on-windows/) to run the code.

TagUI can be run with various [command line options](https://github.com/kelaberetiv/TagUI#to-use). 

If everything goes well, you should be able to order pizza right away!


## License
**MIT License**

Copyright (c) [2019] [Terence Lucas Yap]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
