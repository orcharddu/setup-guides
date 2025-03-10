# Setup Guides

## Installing Go
To help you get started here are some setup guides for Go:

**You will need a go installation before installing most editors.**

- [Linux Lab Machines](go-install/lab-machines.md)
- [Personal Linux PCs](go-install/linux.md)
- [MacOS](go-install/mac.md)
- [Windows](go-install/windows.md)
- [AWS](go-install/aws.md)

## Working From China

Commands such as `go get` will not work since `proxy.golang.org` is currently blocked in China. You can fix this by running the following commands to set up a Go module proxy:

```
go env -w GOPROXY=https://goproxy.cn,direct
```

## Editors

There are also some setup guides for popular IDEs:

- [VSCode](editors/vscode.md)
- [IntelliJ Ultimate with Go plugin](https://www.jetbrains.com/help/idea/go-plugin.html)

## Using AWS

You will receive an email from AWS Academy to setup your account. Complete the application to get access to your account and $100 of credit.

**It is important that you look after this credit! Once it's gone it's gone! Don't run instances when you aren't using them.**

Currently AWS academy is limited to t1/t2.micro instances and some medium instances (2 vCPU) and m5 large instances (probably) When you want to run benchmarks on your Game of Life coursework you should use the largest instances available. **Stick to the micro instances for regular development and testing, you will likely run out of credit if you don't!**

These are some guides that we have created to help you setup your AWS instances. 


- [Creating an instance](aws/create-instance.md)
- [Accessing an instance](aws/access-instance.md)
- [Opening ports](aws/ports.md)

## Detailed set up guides with videos

- Install Go on Ubuntu via Snap [video](https://www.ole.bris.ac.uk/bbcswebdav/courses/COMS20008_2022_TB-1/CONTENT_2022/tuts/InstallGoOnUbuntuViaSnap/Install_Go_on_Linux_via_Snap.mp4),[transcript](https://www.ole.bris.ac.uk/bbcswebdav/courses/COMS20008_2022_TB-1/CONTENT_2022/tuts/InstallGoOnUbuntuViaSnap/snap.htm)
- Install Go on Linux Via a Binary Release [video](https://www.ole.bris.ac.uk/bbcswebdav/courses/COMS20008_2022_TB-1/CONTENT_2022/tuts/InstallGoOnLinuxViaABinary%20Release/Install_Go_on_Linux_via_a_binaryRelease.mp4), [transcript](https://www.ole.bris.ac.uk/bbcswebdav/courses/COMS20008_2022_TB-1/CONTENT_2022/tuts/InstallGoOnLinuxViaABinary%20Release/binary.htm)

## Debugging Help

- Tracing in Go [video](https://www.ole.bris.ac.uk/bbcswebdav/courses/COMS20008_2022_TB-1/CONTENT_2022/tuts/TracingInGo/HowToMakeAtraceOfMultipleThreads.mp4),[transcript](https://www.ole.bris.ac.uk/bbcswebdav/courses/COMS20008_2022_TB-1/CONTENT_2022/tuts/TracingInGo/tracing.htm)
- Debugging with Delve [video](https://www.ole.bris.ac.uk/bbcswebdav/courses/COMS20008_2022_TB-1/CONTENT_2022/tuts/DebuggingWithDelve/debugging_with_delve_1.mp4),[transcript](https://www.ole.bris.ac.uk/bbcswebdav/courses/COMS20008_2021_TB-2/CONTENT_2022/tuts/DebuggingWithDelve/delve.htm)

