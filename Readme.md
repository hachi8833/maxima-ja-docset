# maxima-ja-docset

Docset for Maxima (a symbolic computation system):

- Base html: [Maxima Document in Japanese v5.37.2.1](https://osdn.jp/projects/maxima/releases/63925)
- Tool: [html2dash](https://github.com/xuelangZF/html2Dash)

# Requirement
- [Dash](https://kapeli.com/dash)

# Usage for Dash on Mac OS X

Just download the docset file and double click to install.

# html2dash usage

1. Prepare python environment including [pip](http://www.lifewithpython.com/2012/11/Python-package-setuptools-pip.html)
2. `pip install BeautifulSoup4`
3. `git clone https://github.com/xuelangZF/html2Dash.git; cd html2Dash`
4. Obtain the latest version of Maxima HTML document from [OSDN](https://osdn.jp/projects/maxima/). Assume that the directory name is `'ja'`.
5. Replace the string 'maxima.html' within all html files to 'index.html'
6. Change the filename 'maxima.html' to 'index.html'
7. `./html2dash.py -n maxima ja`
