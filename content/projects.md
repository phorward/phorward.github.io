+++
title = "Projects"
weight = 20
+++

<img src="/formation.webp" title="Formation flight at Riesa" alt="Picture of a Discus 2b flying next to a Std. Libelle's wing">

This is a place where I would like to present some of my recent and older programming projects I've been involved.<br>
All of my projects are open source and you can find them on  [GitHub](https://github.com/phorward).<br>
Some very old projects can be found for download in the [museum](http://downloads.phorward-software.com/).

# Tokay

<img src="/tokay.svg" title="Tokay Logo" style="min-width: 300px; max-width: 35%; margin: 0 auto">

Tokay is my most recent project, and also my personal stick horse since 3 years.

It is an entire programming language that is dedicated to parsing, as parsing is a fundamental feature directly built into the language. Therefore, a program written in Tokay might look a little bit like a BNF-grammar specification with an awk-like syntax, but its an extended mix of both. My personal goal is to make Tokay an innovative, free product to be used for ad-hoc parsing, providing a versatile, quick, extendable and easy maintainable parsing solution for any kind of input.

I had the first ideas for this project in 2018. In 2019, I started to create the first specifications. In 2020, during the COVID pandemic, I started learning Rust and needed an exciting project to use it. With that, Tokay was finally born!

Visit [tokay.dev](https://tokay.dev) to get further information, or [https://github.com/tokay-lang](https://github.com/tokay-lang) on GitHub for details.

# UniCC

UniCC aims to be an *universal compiler-compiler*.

It is a LALR(1) parser generator, with the goal to generate parsers for different target programming languages. Currently, C, C++, JavaScript, Python, but also JSON and XML are supported. UniCC integrates a lexer-generator and defaults to scannerless parsers, where the lexical analysis becomes part of the grammar itself. This goal is reached, as the input grammar is automatically revised to become unambiguous.

A new version 2 of UniCC was planned, but abandoned for now. Its sources are inside of the repository linked below as well. Maybe this project will start over in a new iteration, with new goals and not C as its implementation language somewhere in the future.

Visit [https://github.com/phorward/unicc](https://github.com/phorward/unicc) for details.

# libphorward

libphorward is a library required by UniCC, but also many other projects I've formerly started. It contains some useful tools like linked-lists, hash-tables, dynamic arrays, a lexer generator and a regular expression engine with full Unicode support.

Visit [https://github.com/phorward/libphorward](https://github.com/phorward/libphorward) for details.

# RapidBATCH

Since 2000, the BASIC-like scripting language RapidBATCH was one of my most sucessful projects until version 5.1, which was sold commercially. Unfortunately, it didn't make it into the open source world, and was finally abandoned in 2015.

Already in 2008, I've started to develop the successor version 6 of it, but this version never got into a final product. The unfinished source code of this project was made available as open source in 2017, and can be found [on GitHub](https://github.com/phorward/rapidbatch).

<img src="/rapidbatch5.webp" title="RapidBATCH 5" alt="Screenshot of RapidBATCH 5 with its Windows XP-based IDE" style="min-width: 300px; max-width: 700px; margin: 0 auto">
