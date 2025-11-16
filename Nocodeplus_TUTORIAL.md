# Nocode+

Yeah that is still no code BUT that is FILENAME!!!

## Print hello, world

FILETREE
```
print('Hello, world!').nocode
```

## Standard datatypes

- str
- int
- float
- bool
- list
- dict

## String escaping

As we know, you can't insert `* \ / : " ? | < >` in name of files.

So you can:

| plaintext | escape character |
| --------- | ---------------- |
| *         | &amp;ms;         |
| \\        | &amp;as;         |
| /         | &amp;ds;         |
| :         | &amp;colon;      |
| ?         | &amp;quem;       |
| "         | &amp;dquom;      |
| \|        | &amp;sep;        |
| &lt;      | &amp;lt;         |
| &gt;      | &amp;gt;         |

## Define a variable

SYNTAX:&nbsp;&nbsp;&nbsp;$`variable_name`=`variable_value`.nocode

like this:

FILETREE
```
$his_favourite_game='minecraft'.nocode
$todays_Celsius_temperature=26.nocode
$debug=true.nocode
$shopping_list=['apple','banana'].nocode
$styled_text={'text'='hello','color'='#ffff00'}.nocode
$chat_record=[{'name'='Xiaoming','message'='Nice_to_meet_you'},{'name'='Xiaohong','message'='Nice_to_meet_you_too'}].nocode
```

## Define a function

Function should be a folder.

SYNTAX:&nbsp;&nbsp;&nbsp;function-`function_name`(`arg1_name`-`arg1_datatype`,`arg2_name`-`arg2_datatype`,`...`,`argN_name`-`argN_datatype`)



like this:
```
[FOLDER] function-foo(text-str)
    print(text).nocode
```

### Set a default value of a argument

SYNTAX:&nbsp;&nbsp;&nbsp;`arg_name`-`arg_datatype`=`arg_defaultvalue`

WARNING: All parameters with default values must come after those without default values.

## Operators

| Meanings  | Syntax        |
| --------- | ------------- |
| a + b     | a-@plus-b     |
| a - b     | a-@sub-b      |
| a * b     | a-@multi-b    |
| a ** b    | a-@pow-b      |
| a / b     | a-@div-b      |
| a % b     | a-@mod-b      |
| a == b    | a-@equals-b   |
| a &lt; b  | a-@lt-b       |
| a &gt; b  | a-@gt-b       |
| a &lt;= b | a-@lte-b      |
| a &gt;= b | a-@gte-b      |
| !a        | @not-a        |
| a && b    | a-@and-b      |
| a \|\| b  | a-@or-b       |
| a xor b   | a-@xor-b      |

## Execution in order

When there are many ~~lines of codes~~ filenames, they become difficult to order. So you can:

SYNTAX:&nbsp;&nbsp;&nbsp;`your_code`^`token`.nocode

According to the alphabetical order of the tokens, the "sequential execution" function can be implemented, like this:

```
$pi=3.14159265358979^a.nocode
print(pi)^b.nocode
```
## More about Nocode+

Coming soon...
