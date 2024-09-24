---
title: 'Introduction to Jupyter Notebooks'
documentId: 1B6jwll2zgKFOcXszeFNmT0vpaH-07a45chnLKJjHYGE
revisionId: ALBJ4Lt69L1cCokXaFjP8088EX4yZyAw2IN8B8odoebJf9Rga2kiGxYVeF4k7uc1fkCveXqqIVVE8R34cISAGA
documentLink: https://docs.google.com/document/d/1B6jwll2zgKFOcXszeFNmT0vpaH-07a45chnLKJjHYGE/
---
  
<a id="h.y26bwnrg7bsd" name="h.y26bwnrg7bsd"></a>

## Introduction to Jupyter Notebooks

_Suzanne Little, suzanne.little@dcu.ie_&nbsp;

→ Video introduction of Jupyter and Colab \(2020\): [https://drive.google.com/file/d/1hUZHVY2qMUmv3gLjeuqM\_PQk3ThTU9kZ/view?usp=drive\_link](https://drive.google.com/file/d/1hUZHVY2qMUmv3gLjeuqM_PQk3ThTU9kZ/view?usp=drive_link)  

You may have seen Jupyter Notebooks, eg: hosted on Google Colab, in previous courses. Here we are going to have a brief introduction to how they can be used to document a data management process.

“<span style="font-size:12pt;"><mark style="background: rgb(252.0000015, 252.0000015, 252.0000015)!important">The Jupyter Notebook is an </mark></span>**<span style="font-size:12pt;"><mark style="background: rgb(252.0000015, 252.0000015, 252.0000015)!important">interactive computing environment</mark></span>**<span style="font-size:12pt;"><mark style="background: rgb(252.0000015, 252.0000015, 252.0000015)!important"> that enables users to author notebook documents that include: \- Live code \- Interactive widgets \- Plots \- Narrative text \- Equations \- Images \- Video.</mark></span>” \([https://jupyter\-notebook.readthedocs.io/en/stable/notebook.html](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html)\)

Note: Jupyter was previously called iPython and the backend for running python notebooks is still called this so be aware that older tutorials may use this name. 

To refresh your memory on how notebooks operate, read the [introduction](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#introduction) from the [official Juypter documentation](https://jupyter-notebook.readthedocs.io/en/stable/index.html). If you are unfamiliar with notebooks then complete the tutorial provided at [datacamp.com](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook) \(there are many other good ones\). You can install the notebook system on your personal computer but you can also use them through [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb) which we will be using to show example notebooks throughout this programme. 

Video: Introduction to Google Colab \- [https://www.youtube.com/watch?v=inN8seMm7UI](https://www.youtube.com/watch?v=inN8seMm7UI)

![image](../../../images/Introduction_to_Jupyter_Notebooks/1.png)

Fig: Main components in the Jupyter notebook interface \(From [https://jupyter\-notebook.readthedocs.io/en/stable/notebook.html](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html)\) 

To really get the most from Jupyter notebooks you can also learn to use “magic” features \- [https://www.dataquest.io/blog/jupyter\-notebook\-tips\-tricks\-shortcuts/](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/). 

<a id="h.3yjsui56hle7" name="h.3yjsui56hle7"></a>

### Using notebooks for data\-driven projects

Notebooks are especially useful for data\-driven projects such as the data management, data analytics, machine learning or artificial intelligence work that is intended to be supported by the data management and visualisation module. They provide a reproducible, documented, platform\-neutral record of the data analytics process from gathering to presentation. 

Example of a data\-driven journalism article written in a notebook \(long read\) \- [https://nbviewer.jupyter.org/github/brianckeegan/Bechdel/blob/master/Bechdel\_test.ipynb](https://nbviewer.jupyter.org/github/brianckeegan/Bechdel/blob/master/Bechdel_test.ipynb)

Key features and functionality of notebooks that relevant to the data analytics workflow are: 

<!---->
1. Document your work using [markdown cells](https://www.datacamp.com/community/tutorials/markdown-in-jupyter-notebook).

   &nbsp;&nbsp;&nbsp;Just like putting comments in code, you should also document your data analytics processes. Jupyter cells can be used for text in the simple markdown format to include headings, text, lists, maths, hyperlinks, tables and images. For example, you could have a text cell with information and linking to the source and metadata for a dataset that you are importing. 

   &nbsp;&nbsp;&nbsp;

2. Display graphs embedded in your work.

   &nbsp;&nbsp;&nbsp;When you create exploratory or explanatory visualisations, jupyter allows you to display the resulting graph directly in the notebook. See some [examples](https://colab.research.google.com/notebooks/charts.ipynb) using Google Colab. 

   &nbsp;&nbsp;&nbsp;![image](../../../images/Introduction_to_Jupyter_Notebooks/2.png)

   &nbsp;&nbsp;&nbsp;_Fig: Example showing an embedded line plot in a Google Colab notebook \(from:_&nbsp;_[here](https://colab.research.google.com/notebooks/charts.ipynb)\)_&nbsp;

   &nbsp;&nbsp;&nbsp;

3. Embed [mathematical function](https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Working%20With%20Markdown%20Cells.html#LaTeX-equations) descriptions using MathJax \(a subset of LaTeX\).

   &nbsp;&nbsp;&nbsp;If you are working with mathematics for machine learning then documenting your functions is important. Using maths options in markdown you can include all sorts of mathematics directly in your text cells. Some more complicated examples can be seen in [this notebook](https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Typesetting%20Equations.html). 

   &nbsp;&nbsp;&nbsp;![image](../../../images/Introduction_to_Jupyter_Notebooks/3.png)

   &nbsp;&nbsp;&nbsp;_Fig: Example of using MathJax to embed functions in a Jupyter notebook \(from:_&nbsp;_[here](https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Working%20With%20Markdown%20Cells.html#LaTeX-equations)\)_&nbsp;

   &nbsp;&nbsp;&nbsp;

4. Use [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb) \(interactive, shared, online, backed up\).

   &nbsp;&nbsp;&nbsp;The ability to work on notebooks using Google Colab means that you don’t need to install anything on your local computer and can work on your notebooks from almost any device. This is also great for collaboration as you can share notebooks in the same way as other documents on Google Drive.

   &nbsp;&nbsp;&nbsp;

5. Use [Github](https://github.com/) \(displays notebook but not interactive, version control\).

   &nbsp;&nbsp;&nbsp;For larger or longer term projects with more team members and different data to be managed then using a source code version management system like Git on Github provides extra functionality. Notebooks are json format stored as .ipynb files. Therefore version control can be applied but Github will [render the notebooks](https://help.github.com/en/github/managing-files-in-a-repository/working-with-jupyter-notebook-files-on-github) for static display in the browser when viewed on Github. You can’t run this notebook and interactive features won’t work but it is useful to be able to view the outputs. Local installations like Gitlab will also do this. See also [nbviewer](https://nbviewer.jupyter.org/) for sharing and displaying your notebooks. 

   &nbsp;&nbsp;&nbsp;

6. You can use [widgets](https://jupyter.org/widgets) to turn your notebook into an interactive dashboard.

   &nbsp;&nbsp;&nbsp;Widgets will allow you to integrate user interface components or extra functionality.

   &nbsp;&nbsp;&nbsp;Also see an [example interactive notebook](https://nbviewer.jupyter.org/github/bokeh/bokeh-notebooks/blob/master/tutorial/06%20-%20Linking%20and%20Interactions.ipynb) using the Bokeh visualisation library.

7. You can export notebooks as code, pdf, html and more.

   &nbsp;&nbsp;&nbsp;Either from the notebook menu or using the [nbconvert](https://nbconvert.readthedocs.io/en/latest/) tool. nbconvert will convert your notebook \(the .ipynb file\) into various formats including HTML, PDF, executable code, LaTeX and markdown.

   &nbsp;&nbsp;&nbsp;

8. You can [convert your notebook](https://nbconvert.readthedocs.io/en/latest/usage.html#reveal-js-html-slideshow) to display as slides to present your work.

   &nbsp;&nbsp;&nbsp;Not only will nbconvert generate static versions of your notebook but if you are running this on your local computer then you can use Reveal.js and a local server to make a dynamic presentation from your notebook\! 

Consider using two types of notebooks: one is a traditional lab\-style notebook with your workings, reasoning, plans and experiments \(the “exploratory” notebook\). The second is a “deliverable” for communicating your results clearly \(the “explanatory” notebook\).

Which feature of Jupyter notebooks do you think is the most useful?

<a id="h.nlskaqrwygc" name="h.nlskaqrwygc"></a>

### Exercise: Using a Notebook

Using a general scripting language like Python or R to read and format your data is often a convenient method. 

For structured datasets, these are often stored as data frames \(Pandas library in Python and data.frame in R\). In this notebook, we read data in various formats into a Pandas dataframe and explore some simple methods. 

The aim of this task is to:

<!---->
1. Learn how to open and run a Jupyter notebook in Colab.

2. Learn how to edit and write simple markdown documentation.

3. Learn how to read simple data in one of the three common file formats into a pandas dataframe.

4. Run simple checks that the data has been read correctly.

You can access the Google Colab for this exercise at [https://github.com/suzannelittle/ca682i/blob/master/notebooks/2\_1\_6\_Reading\_and\_formatting\_data.ipynb](https://github.com/suzannelittle/ca682i/blob/master/notebooks/2_1_6_Reading_and_formatting_data.ipynb). You can open the notebook in your Colab by clicking on the button \(image below\) and then save a copy to your own account to work on the exercise

![image](../../../images/Introduction_to_Jupyter_Notebooks/4.png)

<a id="h.h8uqturhr3wy" name="h.h8uqturhr3wy"></a>

### Learn more about reading and exploring data in Jupyter notebooks 

If you would like to try more exercises reading and exploring data in notebooks then take a look at [Github: guipsamora/pandas\_exercises](https://github.com/guipsamora/pandas_exercises/blob/master/01_Getting_%26_Knowing_Your_Data/Occupation/Exercises.ipynb). You can access a copy of the notebook on [Colab here](https://colab.research.google.com/drive/1JAQdWFdMFAbZlWtw8Oid0YpkfXsQUfSa) with questions to try or you will need to download the .ipynb file and run it locally or upload the file to your Google Drive account to open it in Colab. The solutions to the exercises can be found at [https://github.com/guipsamora/pandas\_exercises/blob/master/01\_Getting\_%26\_Knowing\_Your\_Data/Occupation/Exercise\_with\_Solution.ipynb](https://github.com/guipsamora/pandas_exercises/blob/master/01_Getting_%26_Knowing_Your_Data/Occupation/Exercise_with_Solution.ipynb).

<!--
<style>
th {
  font-weight: normal;
}
td {
  border: 2px solid black;
}
ol ol { 
  list-style-type: lower-alpha; 
}
ol ol ol { 
  list-style-type: lower-roman; 
}
img {
  max-width: 100%;
  height: auto;
  object-fit: contain;
}
</style>
-->
