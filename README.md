checksum
==
[![GoDoc](https://godoc.org/github.com/codingsince1985/checksum?status.svg)](https://godoc.org/github.com/codingsince1985/checksum)

Computing message digest in golang for potentially large files.

Install
--
`go get github/TranDuyThanh/checksum/md5`

Usage
--

	package main

	import (
		"fmt"
		"github/TranDuyThanh/checksum/md5"
	)

	func main() {
		file := "/home/jerry/Downloads/ubuntu-gnome-15.04-desktop-amd64.iso"
		md5sum, _ := md5.MD5sum(file)
		fmt.Println(md5sum)
	}