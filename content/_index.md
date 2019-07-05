---
title: "Structured Packet Analysis"
date: 2019-03-12T12:44:45Z
author: Ross Jacobs
description: "Using the Wireshark CLI for Packet Analysis"
---

## About this guide

[Wireshark](https://en.wikipedia.org/wiki/Wireshark) is a tool used to visualize network issues.
It is well documented with the [Official Documentation](https://www.wireshark.org/docs/),
the [manpages](https://www.wireshark.org/docs/man-pages/), and the [Wireshark Forums](ask.wireshark.org), among others.
In addition to a GUI version, Wireshark comes with many command-line utilities like tshark.
This guide explores packet analysis using these tools. Examples and direction are provided as well as pitfalls to avoid.

This is a living, breathing guide. If you’d like to contribute, [fork me on GitHub](https://github.com/pocc/tshark.dev)!

### Philosophy

* Add examples so they exist
* Articles should be short and help you find information as fast as possible
* If X has already been written, link to it instead of writing the same article twice
* Use `bash` examples with ones in `powershell` as appropriate

## Table of Contents

{{% children depth="4" %}}
