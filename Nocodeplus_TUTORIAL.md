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
| "         | &amp;quot;       |
| \|        | &amp;sep;        |
| &lt;      | &amp;lt;         |
| &gt;      | &amp;gt;         |
| &amp;     | &amp;amp;        |

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
function-foo(text-str)/
    print(text).nocode
```

### Set a default value of a argument

SYNTAX:&nbsp;&nbsp;&nbsp;`arg_name`-`arg_datatype`=`arg_defaultvalue`

WARNING: All parameters with default values must come after those without default values.

### Comment a return type

SYNTAX:&nbsp;&nbsp;&nbsp;function-`function_name`(`args`)=`function_returntype`

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

## Comments

No syntax, just write into a file.

YEAH, that is stilllllllllll no code, isn't it?

### Comment a folder

Create a file, you can name it freely BUT the file extention cannot be ".nocode".

do U understand?

## Locate

Only files \(Not folders\) can use "locate", transform file to a folder and remove ".nocode" if this file has used "locate"

SYNTAX:

- `...`#{`token1`}`...`#{`token2`}`...`#{`token3`}`...`
- - `token1`
- - - `your_code`
- - `token2`
- - - `your_code`
- - `token3`
- - - `your_code`

### Example

before:
```
return(fibonacci(i-@sub-1)-@plus-fibonacci(i-@sub-2)).nocode
```

after:
```
return(#{a}-@plus-#{b})/
    a/
        fibonacci(i-@sub-1).nocode
    b/
        fibonacci(i-@sub-2).nocode

```

## More about Nocode+

Coming soon...
