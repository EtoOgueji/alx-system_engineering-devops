# Regular Expressions in Ruby
A regular expression (regex) is a powerful tool for pattern matching and manipulation of text. In Ruby, regular expressions are implemented using the Regexp class.

## Syntax
A regex is enclosed in forward slashes (/regex/). The regex pattern itself can include a variety of special characters and syntax.

## Character classes
Character classes match any one character within a set of characters. They are enclosed in square brackets ([ ]).

For example, the regex pattern /[abc]/ matches any string that contains the letters "a", "b", or "c".

## Quantifiers
Quantifiers specify how many times a pattern should be matched. Some common quantifiers include:

+ *: Matches zero or more occurrences of the preceding character or group.
+ +: Matches one or more occurrences of the preceding character or group.
+ ?: Matches zero or one occurrence of the preceding character or group.
+ {n}: Matches exactly n occurrences of the preceding character or group.
+ {n,}: Matches at least n occurrences of the preceding character or group.
+ {n,m}: Matches between n and m occurrences of the preceding character or group.

## Anchors
Anchors match the position of a string, rather than a specific character. Some common anchors include:

+ ^: Matches the beginning of a line.
+ $: Matches the end of a line.
+ \b: Matches a word boundary (the position between a word character and a non-word character).
+ \B: Matches a position that is not a word boundary.
+ Alternation
+ Alternation (|) matches one of several alternatives. For example, the regex pattern /cat|dog/ matches either the string "cat" or the string "dog".
