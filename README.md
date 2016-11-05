# My Python learning pack!
Here you find a list of resources which might be for your help in learning Python, as well as a virtual environment where many tools are readily available for you.

## Setting up a Python environment
This repo contains a virtual environment set up for easy installation. You can start using Python without learning how to install Python and modules, which is not always straightforward and might even require some system administration knowledge. Of course later you can learn these, but now we provide a little help for a quick start.
To install this environment to your own computer follow [the description](https://github.com/fazekasda/MyPythonLearnPack/tree/master/JupyterEnv).

## Where to start?
* https://www.python.org/ - The home of Python
* http://stackoverflow.com/documentation/python/topics - In 2016 StackOverflow started their Documentation project, which aims to be a community developed schoolbook and knowledgebase. This rapidly developed to one of the best Python learning resources on the web.
* https://www.codecademy.com/learn/python - Interactive platform to learn Python (as well as many other languages). Start here if you have never wrote code before.
* https://www.youtube.com/watch?v=HBxCHonP6Ro&list=PL6gx4Cwl9DGAcbMi1sH6oAMk4JHw91mC_ - Long Python video tutorial for the very beginners
* https://github.com/mshang/python-elevator-challenge - Beginner tutorial with programming an elevator in Python

## Non Python specific but important resources
* http://stackoverflow.com/ - This very important resource worths special mention. As you will se if you google for any programming issue, in 90% you will end up on this site. SO is a Q&A (question and answer) site where anybody can ask programming related questions and answer or comment others questions. Users collect reputation points for their contributions which made it a very efficient platform for community building around mutual help. Your question likely will be answered very quickly, but be careful not to ask something already answered by answers for other questions.
* https://bitbucket.org/ - We suggest you to familiarize yourself as soon as possible with version control frameworks. Nowdays the most popular is **git**. Version control helps you to keep track of changes, keep your project files in order, backup your work often, avoid data loss, to collaborate and to share your code in a standard and convenient way. BitBucket allows you to to create more private repos than the most well known git server, [http://github.com/](github.com).
* https://maryrosecook.com/blog/post/git-from-the-inside-out - If you write code please start using git. Sooner is better, even your random exercises you can commit to a git repo. Here is an in depth introduction to git starting from the basics.

## Interactive learning platforms
* https://www.codecademy.com/learn/python - Interactive platform to learn Python (as well as many other languages)
* http://www.learnpython.org/ - Lots of tutorials from the basics
* https://www.datacamp.com/courses/intro-to-python-for-data-science - Interactive tutorial focusing on Data Science applications
* https://www.datacamp.com/courses/intermediate-python-for-data-science - Interactive tutorial focusing on visualization with matplotlib

## Exercises
When you write code with the aim of learning it is often difficult to find a task, you want to code, but don't know what to code. In Euler Problems you find hundreds of small mathematics problems, each of them you can solve just in a few lines of code, ideal even if you have only half hour for practicing. As you develop you can return to already solved problems, and find out better and nicer implementations.
* https://projecteuler.net/archives
* http://www.ling.gu.se/~lager/python_exercises.html - 46 very simple exercises for completely beginners 

## Tutorials
* https://imgur.com/WRuJV6r - Debugging workflow for beginners
* https://automatetheboringstuff.com/ - Python for beginners, a different way, whit a lots of tutorials
* http://python.swaroopch.com/ - Learn Python from beginning by tutorials
* https://www.codementor.io/python/tutorial - Useful tutorials from experts
* https://github.com/faif/python-patterns - Programming patterns in Python
* http://www.python-course.eu/ - A full Python course for beginners, covering all important basic topics
* https://maryrosecook.com/blog/post/a-practical-introduction-to-functional-programming - This is a very nice introduction to functional programming in Python.

## Resources
Here we list blogs and assays which are not primarily tutorials, but give an introduction or insight into specific topics
* https://julien.danjou.info/blog/tags/Python - Python related articles from Julien Danjou's blog. You can find excellent pieces here, for example about testing, profiling, exception handling, pep8 standard, etc.
* https://jakevdp.github.io/ - Interesting insights into specific topics.

## Massive Open Online Courses (MOOCs)
* https://www.coursera.org/specializations/python - A Coursera specialization for learning Python

## Environments
* http://www.bpython-interpreter.org/ - Nice, colorful command line environment with smart autocompletion and built in help functions.
* https://gist.github.com/lonetwin/5902720 - You can easily customize your Python shell with editing your **~/.pythonrc** file. For example, copy the one in this git repo into yours, and you will have a colored shell with autocompletion.
* https://www.pythonanywhere.com/ - A full Python environment in the cloud with lots of [libraries](https://www.pythonanywhere.com/batteries_included/) and many Python versions available. You can write Python scripts in the browser, and even deploy your application as a webpage. Free plan is available.
* https://jupyter.org/ - Interactive Python environment in the browser: Python runs in the background on your machine, and you write the code and get the output in the browser, in so called notebooks. Note: this is the same as IPython was, they just renamed when it became language agnostic (originally it was only for Python, but now can be used also with other languages).
* https://www.continuum.io/why-anaconda - Python environment intended for science and data analysis, with easy availability of relevant modules (at least in theory: eventually installation 
might be more complicated).

## Modules for data analysis
* http://www.numpy.org/ - Computationally efficient handling of multidimensional numeric arrays (i.e. matrices of numbers). 
* https://www.scipy.org/ - Collection of many stats and science methods, like regression, statistics tests.
* http://pandas.pydata.org/ - Built on top of numpy, pandas provides a more convenient handling of data tables, i.e. here you can have row and column names, methods for convenient rearranging and filtering your data. You can imagine a programmable excel sheet, or something like data frames in R.
* https://jupyter.org/ - Interactive Python environment in the browser: Python runs in the background on your machine, and you write the code and get the output in the browser, in so callednotebooks. Note: this is the same as IPython was, they just renamed when it became language agnostic (originally it was only for Python, but now can be used also with other languages).
* https://boltons.readthedocs.org/en/latest/ - Many useful tools for advanced Python programming

## Visualization, plotting
* http://matplotlib.org/ - The "grandmother of all Python plotting applications", extremely customizable, but complex plotting module. Note: you can use matplotlib either by its object oriented interface or by the matlab inspired pylab interface, be aware of the differences.
* http://seaborn.pydata.org/ - Module built on matplotlib, providing simple methods and nice default styles. And you can still access the low level matplotlib interface, in case you need it.
* https://plot.ly/python/ - An easy way to make interactive html plots in IPython notebook. Note: it is not obvious from their webpage, but you don't need to register even for the free plan to use this library locally and generate html plots; you can install by pip and use it just like any other module.
* http://bokeh.pydata.org/en/latest/ - Alternative to plot.ly.
* http://pygal.org/en/stable/ - Similar to the 2 above, creates interactive plots.
* https://mpld3.github.io/index.html - Here you create the plots with matplotlib, and transform them to d3.js objects, so they remain interactive in the browser, independently from Python.
* https://github.com/vega/vega/wiki/Documentation - A generic visualization grammar (i.e. a declarative language to describe visualizations).
* https://vega.github.io/vega-lite/ - A simplified version of Vega.
* https://vincent.readthedocs.io/en/latest/ - A tool to define plots in Python and translate them to Vega.
* https://altair-viz.github.io/ - A declarative visualization module for Python using Vega in the background.
* http://vispy.org/gallery.html - This creates and renders dynamic visualizations using the graphic card of your computer.
* http://ggplot.yhathq.com/ - An attempt to make the famous R ggplot visualization library available in Python. Does not provide all the features and exactly the same interface, but still a nice library.
* https://github.com/dgrtwo/gleam - Creates interactive visualizations for browser; Python needs to run in the background.
* https://dansaber.wordpress.com/2016/10/02/a-dramatic-tour-through-pythons-data-visualization-landscape-including-ggplot-and-altair/ - An amusing and detailful comparison of matplotlib, pandas, seaborn, ggplot and altair, with 5 examples and analysis. If you want to make an informed decision about which library to use, don't skip this.
* http://pbpython.com/visualization-tools-1.html - Another overview of tools, but with less details and less examples.
* https://lisacharlotterost.github.io/2016/05/17/one-chart-code/ - A wider but less detailed comparison.
* http://matplotlib.org/style_changes.html - Good material about color maps.

## Graphs (networks) 
* http://igraph.org/ - Powerful graph analysis package with full featured Python interface and great visualization module.
* https://graph-tool.skewed.de/ - A high-performance graph library with Python interface.
* https://networkx.github.io/ - A network analysis module written purely in Python, recently with more features and better visualization.
* https://pygraphviz.github.io/ - Python interface for [graphviz](http://www.graphviz.org/), the graph visualization library known from its greate layout algorithms.

## Statistics
These are not Python related but generic.
* http://simplystatistics.org/ - Nice blog from statistics teachers of John Hopkins University and Harvard University
* http://varianceexplained.org/ - Another nice blog from data sciencist David Robinson

## IDEs (integrated development environments)
IDEs help you to keep track of files in your project, their history, dependencies, testing, outputs, etc.
* https://www.pythonanywhere.com/ - A full Python environment in the cloud with lots of [libraries](https://www.pythonanywhere.com/batteries_included/) and many Python versions available. You can write Python scripts in the browser, and even deploy your application as a webpage. Free plan is available.
* https://www.yhat.com/products/rodeo - Python IDE similar to RStudio, focusing on data analysis
* https://www.jetbrains.com/pycharm/ - One of the best IDEs for python, with many tools and complex interface
* https://www.continuum.io/why-anaconda - Python environment intended for science and data analysis, with easy availability of relevant modules

## Books
### Must read
* https://automatetheboringstuff.com/ - Python for beginners, a different way, whit lots of tutorials
* http://docs.quantifiedcode.com/python-anti-patterns/ - How NOT to use Python. Advanced level
* https://thehackerguidetopython.com/ - A very nice book both for beginners and advanced Python coders. Hint: subscribe for the free chapter on the webpage, and you will get weekly mail with interesting and very useful blog posts from Julien.
* http://file.allitebooks.com/20160830/Python%203%20Object-Oriented%20Programming,%20Second%20Edition.pdf - In depth material for object oriented programming in Python.

### Advanced Python
* http://www.effectivepython.com/
* http://shop.oreilly.com/product/0636920032519.do
* http://learnpythonthehardway.org/book/
* http://book.pythontips.com/en/latest/

### Other Books
* http://www.obeythetestinggoat.com/ - Python testing

## Lectures
* https://www.youtube.com/watch?v=2NSbuKFYyvc

## Podcasts
* https://talkpython.fm/
* http://podcastinit.com/
* http://frompythonimportpodcast.com/

## Miscellanous
* http://pythontips.com/2016/02/27/learning-python-for-data-science/
* http://pep8.org/ - Standard coding style guide. You will be expected to follow these simple rules in any serious project, so better to familiarize yourself from the beginning. Tools are available to autocheck and in limited cases autocorrect pep8 violations: https://flake8.pycqa.org/en/latest/, https://fangpenlin.com/posts/2014/02/05/auto-post-commit-pep8-correction/

## Fun
* https://quantifiedcode.github.io/code-is-beautiful/ - Visualization of Python code
