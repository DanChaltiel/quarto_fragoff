# FragOff Extension For Quarto

Fragments are a powerful tool for making presentations more dynamic and engaging.

However, they can sometimes get in the way when you need to focus on specific content.

Well, worry no more! This simple extension lets you toggle fragments on and off effortlessly.

## Installing

To install, run this command in your terminal (not your R console):

```bash
quarto add DanChaltiel/quarto_fragoff
```

This will install the extension under the `_extensions` subdirectory.
This subdirectory will be located in your current working directory.
If you're using version control (Git, SVN, etc.), you will want to check in this directory.

Then, add this to the root level of your quarto YAML header:

```yaml
revealjs-plugins:
  - fragoff
```

## Using

This extension will add a checkbox in the slide men: 
 - When **checked** (default), fragments are enabled
 - When **uncheckded**, they are disabled.

It's that simple!

## Example

Here is the source code for a minimal example: [example.qmd](example.qmd).

