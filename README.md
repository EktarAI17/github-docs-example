# Writing good documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste and share** code.

- A good __Cloud Engineer__ uses Codeblocks whenver possible,
- Because it allows others to copy and paste their code to replicate or research issues.
- Below is the way to input a codeblock in your readme file.

  - When you can you should attempt to apply syntax highlighting to your codeblocks
```python (works for yaml, terraform)
# Example Python script: example_script.py

def divide_numbers(a, b):
    return a / b

result = divide_numbers(10, 0)
print(result)
```
- Play some sport when you are not coding

<img width="200px" src="https://github.com/user-attachments/assets/28829420-d34f-4558-b72f-8e3fecde66d3" />

- Good cloud engineers use codeblocks for both Code and Errors that appear in the console.
```bash
Traceback (most recent call last):
  File "example_script.py", line 4, in <module>
    result = divide_numbers(10, 0)
  File "example_script.py", line 2, in divide_numbers
    return a / b
ZeroDivisionError: division by zero
```
> Here is an example of using a codeblock for an error that appears in bash

- above is for quoting block/ breaking formatting

## Step 3 - Use Github Flavoured Markdown(GFM) Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [] Finish Step 2
- [x] Finish Step 3

## Step 4 - Use Emojis (Optional)

GFM supports  emoji shortcodes.
Here are some examples:

| Name  | Shortcode | Emoji |
| --- | --- | --- |
| Cloud  | `:cloud:`  | :cloud: |
| Cloud with lightning  | `:cloud_with_lightning:` | 🌩️ |

## Step 5 - how to create a table 

You can use the following markdown format to create tables (can use 'markdown' or 'md'(shortcut)):

```md
| Name  | Shortcode | Emoji |
| --- | --- | --- |
| Cloud  | `:cloud:`  | :cloud: |
| Cloud with lightning  | `:cloud_with_lightning:` | 🌩️ |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options.
[<sup>[2]</sup>](#external-references)

## External References
- [GitHub Flavored Markdown Spec](https://github.github.com/en/get-started/gfm)
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables)<sup>[2]</sup>
