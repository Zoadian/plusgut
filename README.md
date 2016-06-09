# Introduction
This is the reference manual for the Plusgut programming language.

Plusgut is a strongly typed language. It is influenced mainly by D, Rust, Go, Swift.


# Notation
The syntax is specified using Extended Backus-Naur Form

# Source code representation
## Characters
## Letters and digits

# Lexical elements
## Comments
## Tokens
## Identifiers
## Keywords
## Operators and Delimiters
## Integer Literals
## Floating-point literals
## Character literals
## String literals

# Constants

# Variables

# Types
## Non types
    void

## Boolean types
    bool        

## Numeric types
    byte        signed  8-bit integers (-128 to 127)
    ubyte       unsigned  8-bit integers (0 to 255)
    short       signed 16-bit integers (-32768 to 32767)
    ushort      unsigned 16-bit integers (0 to 65535)
    int         signed 32-bit integers (-2147483648 to 2147483647)
    uint        unsigned 32-bit integers (0 to 4294967295)
    long        signed 64-bit integers (-9223372036854775808 to 9223372036854775807)
    ulong       unsigned 64-bit integers (0 to 18446744073709551615)
    cent        (reserved for future use)
    ucent       (reserved for future use)
  
    float       IEEE-754 32-bit floating-point numbers
    double      IEEE-754 64-bit floating-point numbers
    real        (reserved for future use)

## Character types
    char        UTF-8 code unit
    wchar       UTF-16 code unit
    dchar       UTF-32 code unit
  
## Array types
## Slice types
    [int]
## String types
    string      short for [char]
    wstring     short for [wchar]
    dstring     short for [dchar]
## Struct types
## Pointer types
## Function types
    fun()
    fun(a int) int
## Interface types
## Map types

# Templates
## Templated functions
    fun!(T)()
    fun!(T)(a int) int

# Blocks

# Declarations and scope
## Type declarations
## Variable declarations
## Function declarations


