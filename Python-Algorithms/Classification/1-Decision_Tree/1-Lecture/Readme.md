# Decision Tree

## Guide

* Graphviz (Ubuntu Installation)

You need to install the pydotplus package to be able to see the graph.

```
python -m pip install pydotplus
```

* Graphviz (Windows Installation)

First, you need to install the `pydotplus` package

```
pip install pydotplus
```

```
pip install pydot
```

```
pip install graphviz
```

Second you need to download the msi file:

Install [Graphviz](https://graphviz.org/download/)

and then add the following command in your python code.

```
import os     
os.environ["PATH"] += os.pathsep + 'C:/Program Files (x86)/Graphviz2.38/bin/'
```

