# File Format

Each document should contain both the code needed to run the program as well as the explanation for the code.
A chunk of code, even if it runs perfectly, is of no use to anyone if you don't know what it does. 
Explanation goes beyond just adding comments to your code, though those should be included as well.
There should be a written description of what the code is doing and why it would be run such that someone new to bioinformatics is able to understand it.

To this end, code should be uploaded as part of a R markdown file as well as the HTML output.
This way someone can download the HTML and view it in an easily readable format.
They can also download the R markdown file (.rmd) to have the code they can easily modify and run.
A template of the R markdown format to use for making these workflows is included in this folder.

Because code should have explanation around it, longer scripts will likely have to be broken up into smaller chunks within the notebook document.
If this is the case, you may also the full script without explanation in the usual format for that language (such as .sh or .R).
Script files are **in addition** to the markdown and HTML files, not as a replacement for them.

# Directory Structure
Files in the repository should be stored in folders corresponding to the program they're for. 
If you use multiple programs in an analysis pipeline, each program should still have it's own format, but you should outline the entire pipeline in a file in the pipelines folder.
If there are multiple sets of documents for a program, such as two different uses of the same program, make a subfolder labeled with the use case.

