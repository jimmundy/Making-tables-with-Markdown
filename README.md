# Making-tables-with-Markdown
In Data Science projects, sharing a notebook or making a quick presentation using simple tables can become necessary. This gets handy at the start of project meetings or later. Even though structured and unstructured data can be viewed nicely in tabular forms with libraries such as Pandas, creating a quick table with markdown (or HTML) is an easy task.

We only need:

Notebook: Jupyter Notebook
Kernel: Python 3
The text to create a table in a markdown cell is shown below. Copy the code into a Markdown cell (last cell) and run to see the table.

Just for explanation purposes, ‘%%capture‘ takes the stdout/stderr of a cell. With this magic command, you can discard the stream and simply show the code and not display the table.
