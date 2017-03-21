# Basics

## `string` - Specific String
- can be any literal string

## `.` - Anything (except Newlines)
- ABC\nD -> ABCD

## `\d` - Any digit character
- he1o -> 1

## `\D` - Any non-digit character
- h310 -> h

## `\s` - Any whitrespace character
- X Y (single whitespace between X and Y) -> (whitespace)

## `\S` - Any non-whitespace character
- X Y (single whitespace between X and Y) -> X (X was the first mnatch)

## `\w` - Any word character (a-z, A-Z, 0-9, _)
- $$4$$ -> 4

## `\W` - Any non-word character (symbols, other than _)
- $var -> $

## `^` - Start of string (examble ^ABC)
- ABCDEFABC -> ABC (the first set)

## `$` - End of string (example XYZ$)
- XYZUVWXYZ -> XYZ (the last set)
