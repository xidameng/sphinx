# How to use

0. Install all necessary tools and environment
**Tools needed:**

- Python3

	https://www.python.org/downloads/

- sphinx

	```Python
	pip install -U sphinx
	```

- sphinx rtd theme
	
	```Python
	pip install sphinx-rtd-theme
	```

- pandoc

	https://pandoc.org/installing.html


1. Clean the directory
```Makefile
make clean
```

2. Copy the rst file to the correct path

3. Update index.rst and fix heading issue in every rst file

4. Fix media path issue

5. Create html page
```Makefile
make html
```
6. Push changes to github

7. Build docs using Readthedocs online hosting service
	https://readthedocs.org/
