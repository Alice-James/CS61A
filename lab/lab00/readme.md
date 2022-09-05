# 1.终端指令

1. `ls`: **l**i**s**ts all files in the current directory
2. `cd <path to directory>`: **c**hange into the specified **d**irectory
   1. `cd ..` (two dots). The `..` means "the parent directory".
   2. `cd ~` (the tilde). Remember that `~` means home directory
   3. `cd` (`cd` on its own). Typing just `cd` is a shortcut for typing `cd ~`.
3. `mkdir <directory name>`: **m**a**k**e a new **dir**ectory with the given name
4. `mv <source path> <destination path>`: **m**o**v**e the file at the given source to the given destination
5. `python3`:进入`python`
6. `exit()`:退出`python`

# 2.表达式

1. `**`指数

   ```
   >>> 2**4
   16
   >>> 2**6
   64
   ```

2. `//`除法的商

   ```
   >>> 7//4
   1
   ```
   
3. `"""`注释
   The lines in the triple-quotes `"""` are called a **docstring**, which is a description of what the function is supposed to do. 

4. `>>>`结果展示
   The lines that begin with `>>>` are called **doctests**. Recall that when using the Python interpreter, you write Python expressions next to `>>>` and the output is printed below that line. Doctests explain what the function does by showing actual Python code. It answers the question: "If we input this Python code, what should the expected output be?"

   ```
   def twenty_twenty():
       """Come up with the most creative expression that evaluates to 2020,
       using only numbers and the +, *, and - operators.
   
       >>> twenty_twenty()
       2020
       """
       return ______
   ```

   - The docstring tells you to "come up with the most creative expression that evaluates to 2020," but that you can only use numbers and arithmetic operators `+` (add), `*` (multiply), and `-` (subtract).
   - The doctest checks that the function call `twenty_twenty()` should return the number 2020.

