Pre-req
=======
How I got setup on a windows 10 machine in WSL.

Install VSCode.

Install Go via instructions at...
https://golang.org/doc/install?download=go1.14.3.linux-amd64.tar.gz

And then remove existing go installs with instructions...
https://askubuntu.com/questions/720260/updating-golang-on-ubuntu

Then compile the source...
```
$ go build hello.go
```

You can now run...
```
./hello
```

Then read more go at...
https://golang.org/doc/code.html


Gotchas
=======
Not too many. Bit of permissions and trying sudo but then realising permissions were not set
on the hello.go file.

