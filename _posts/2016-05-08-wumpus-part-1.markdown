---
layout: post
title:  "Hunt the Wumpus in Clojure: Part 1"
date:   2016-05-08 00:17:13 
categories: clojure games
---
<i>Hunt the Wumpus</i> is a simple, early text-based computer game.  Being simple and early it seems fitting to write it in a language 
that is also simple and early, Lisp.  Now, to say something is written in Lisp is a bit on the vague side, it's like saying this article is 
written in a Germanic language.  While technically true, it doesn't tell you if the article is in Swedish, German, English, Icelandic or some other Germanic language (spoiler alert: it's in English).  

So we need to pick a specific dialect of Lisp and I bet you already know which dialect that is (spoiler alert: it's Clojure, it's in the title).
Clojure is a recent dialect of Lisp that compiles to Java bytecode, allowing it to run anywhere there's a JVM.