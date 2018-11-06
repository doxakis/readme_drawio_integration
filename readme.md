# draw.io integration in readme file
According to https://github.com/jgraph/drawio-github, there is multiple GitHub integration. One of them is SVG file with embedded PNG data. This format give us the possibility to use `<img src="..." />`

Here is an example :

![Diagram workflow](diagram-workflow.svg)

# Steps

Make sure to install "draw.io Desktop". (So, you can keep your graph offline.)

![Step 1](step1.png)

![Step 2](step2.png)

In the readme.md file, you can use `![Diagram workflow](diagram-workflow.svg)`.

This is not specific to GitHub. For example, it works fine for bitbucket. You could use it everywhere. You can version control the graph and reference diagrams.

# Copyright and license
Code released under the MIT license.