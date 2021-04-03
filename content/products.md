+++
title = "Products"
description = "Products"
weight = 2
+++

# Tokay

**Tokay** is a programming language for ad-hoc parsing-related issues inspired by awk, Python and Rust.

# UniCC

**UniCC** is a universal LALR(1) parser generator, targetting C, C++, Python, JavaScript, JSON and XML.

## Overview

UniCC (UNIversal Compiler-Compiler) compiles an augmented grammar definition into a program source code that parses the described grammar. Because UniCC is intended to be target-language independent, it can be configured via template definition files to emit parsers in almost any programming language.

UniCC comes with out of the box support for the programming languages C, C++, Python (both 2.x and 3.x) and JavaScript. Parsers can also be generated into JSON and XML.

UniCC can generate both scanner-less and scanner-mode parsers. The more powerful scanner-less parsing is the default, and allows to break the barrier between the grammar and its tokens, so tokens are under full control of the context-free grammar. Scanner-less parsing requires that the provided grammar is internally rewritten according to whitespace and lexeme settings.

# v0.3.0 - 2020-07-17

- Rename css filename to avoid conflicts.
- Replace sass variables with css variable.
- Add `--toc-highlight-text-color` variable.
- Add normalize.css.

# v0.2.0 - 2020-06-28

- Add extra extra_menu config.
- Add color customization CSS variables.
- Improve docs and blockquote style.
- Support customize logo and name.

# v0.1.0 - 2020-06-21

- First release!
