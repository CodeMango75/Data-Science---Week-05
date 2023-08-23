# If Else 

# Symbolic AI
What you can think and write through Computer Program is called **Symbolic AI** 

* Boolean is mainly used.
* Boolean is *True* or *False*, *Yes* or *No*, *On* or *Off*
* `and` , `or` , `not` 
* **Reserved Keywords** are keywords that cannot be used as variables. 
   * `if`
   * `else`
   * `elif`
* Syntax 
```
if LOGIC:
  True_Body
else:
  False_Body  
```   
**Note :** Logic = True|False

* Python interpreter will check logic after going through *if*. If true, then first block of above syntax and if false, then second block of above syntax.

## Elif 

* When more than 2 decisions are required, we use `elif` commands.
* Please note that, unlike **JavaScript** and other programming Languages, **`else-if`** commands are NOT valid in Python. 
```
if LOGIC1: 
  Statement1
elif LOGIC2:
  Statement2
elif LOGIC3:
  Statement3
else:   
```
* Also, be advised that a *colon (:)* is used to define block of code in Python. Use of Curly Braces `{}` will result in an ERROR as it is not applicable. 

### Comprehensive Style

```true_block `if` LOGIC `else` false_block``` 

* Recommended when only decision is used to be make out of 2 outcomes.
* It is used and there will be times when comprehensive style will be necessary.
* For more than 2 decision outcomes, use `elif` commands. 

