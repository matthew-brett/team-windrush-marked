# Team-Windrush - an example project - marked

This is an example project from the [2018-19 Data Science for Everyone
class](https://matthew-brett.github.io/dsfe).

The project is by:

* Elise de Wildt
* Edward Pinder
* Zaid Bangee

Elise kindly agreed to allow the files to be public.

## Example

See some marking markup in the notebook `READ_ME_PROJECT_SUBMISSION.ipynb`.

## Marking markup

Give comments as you read through the text.

Marking comments in text cells look like this:

**marking** This is a marking comment.  It can go on for several lines, and include *Markdown* markup.  It finishes with **end**.

Note the start and end markers are typed `**marking**` and `**end**`.

Marking comments in code look like this:

```{python}
##marking
# Here are some comments on the code, in the code.
# The comments can be several lines.
# They end with:
##end
```
## Marking procedure

* Run the notebook.
* Comment on the notebook as you go in the text and code cells, with markup as
  above.
* Fix any errors in the code that you find.
* Record the fixes in the comments.

Example:

```{python}
# Original
print something
```

```{python}
# Marked
##marking
# The code here causes an error.
# print something
# I've replaced it with what I think you meant.
print('something'
##end
```
