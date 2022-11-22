## Exercise

Given a string, you have to return a string in which each character (case-sensitive) is repeated once.

Examples (Input -> Output):

```bash
* "String"      -> "SSttrriinngg"
* "Hello World" -> "HHeelllloo  WWoorrlldd"
* "1234!_ "     -> "11223344!!__  "
````

# Solution
```bash
  def double_char(s):
    result = ''
    for c in s:
        result = result + c*2
    return result
```



