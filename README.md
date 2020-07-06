# animan.doc
Source of the Documentation of animan.doc

https://github.com/sgsbucket/animan.doc.git

## Install
* install python3
* add path to python\python37\Scripts
* pip install -U sphinx
* easy_install sphinx-intl
* pip install sphinx_materialdesign_theme

## Commands

* make gettext
* sphinx-intl update -p build/gettext
* sphinx-intl build
* make -e SPHINXOPTS="-D language='fr'" html

## Gulp Tasks
* **gulp intl** *build translations*
* **gulp build** *build the site*
* **gulp open** *open local homepage of the build*
