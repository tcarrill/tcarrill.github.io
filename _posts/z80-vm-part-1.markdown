---
layout: post
title:  "Z80 Virtual Machine - Part 1"
date:   2017-01-24 00:19:05 
categories: z80 vm asm
---
This will be a series of short articles with the intent to build a functioning Z80 VM.  We will start out small, implementing only a few of the registers and opcodes which operate on them.  Calling this a VM may be a bit of a misnomer, we will be reproducing just the processor and its whopping 64K of addressable memory in software.  We will not (to start) be building any other hardware (hard disk, I/O systems).  It is more akin to something like the Java VM, our little software Z80 should be able to run any valid Z80 binary.  We will utilize this fact by periodically building a Z80 binary and running it though the VM to test new functionality.
