# unicode-list

## How to install

```
tyler@nasaelite:~/packages/unicode-list$ zef install .
===> Testing: unicode-list:ver<1>
===> Testing [OK] for unicode-list:ver<1>
===> Installing: unicode-list:ver<1>

1 bin/ script [unicode-list] installed to:
/home/tyler/.perl6/bin
```

## Help menu

```
tyler@nasaelite:~/packages/unicode-list$ unicode-list
Usage:
  unicode-list <lower> <higher>
  
    <lower>     the lower bound of Unicode characters to print
    <higher>    the upper bound of Unicode characters to print
```

## Example usage

```
tyler@nasaelite:~/packages/unicode-list$ unicode-list 32 0xFF
Prop Dec   Hex   Chr  Name
Zs   32    20         SPACE
Po   33    21    !    EXCLAMATION MARK
Po   34    22    "    QUOTATION MARK
Po   35    23    #    NUMBER SIGN
Sc   36    24    $    DOLLAR SIGN
Po   37    25    %    PERCENT SIGN
Po   38    26    &    AMPERSAND
Po   39    27    '    APOSTROPHE
Ps   40    28    (    LEFT PARENTHESIS
Pe   41    29    )    RIGHT PARENTHESIS
Po   42    2A    *    ASTERISK
Sm   43    2B    +    PLUS SIGN
Po   44    2C    ,    COMMA
Pd   45    2D    -    HYPHEN-MINUS
Po   46    2E    .    FULL STOP
<snip>
```