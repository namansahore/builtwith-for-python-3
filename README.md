# BuiltWith

Built With is a [pyhton package](https://pypi.python.org/pypi/builtwith/1.3.2) which detects differnt types technology used by a web application like javascript, server, blog or cms. And helps in reverse engineering.

 * Home Page : [builtwith](https://bitbucket.org/richardpenman/builtwith)
 * Author: [Richard Penman](richard@webscraping.com)
 * Current Version : 1.3.2


### Issue:

	Builtwith doesn't support python 3 (3.6.2) because it uses some libraries and functions that are slightly different in python 3 as compair to python 2.

### Fix:

[Download](https://pypi.python.org/pypi/builtwith/1.3.2) builtwith package and replace or rewrite it's __ init__.py file with above code.
This code behave in slightly different manner. 

Now you package will work as it should.

	It will return string having error message when an error occur
    And return dictionary having output on successful execution
 
Output can checked with simple conditional statement :
```
if output is str :
	print(output)
else 
	#Your code
```

#### By [Naman Sahore](https://github.com/namansahore)
