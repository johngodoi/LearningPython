# Becoming a Pythoner

"No princípio era o Verbo..."

## Python x Scala x R x Java x JS
```
Três Anéis para os Reis-Elfos sob este céu,

Sete para os Senhores-Anões em seus rochosos corredores,

Nove para os Homens Mortais fadados ao eterno sono,

Um para o Senhor do Escuro em seu escuro trono

Na Terra de Mordor onde as Sombras se deitam.

Um Anel para a todos governar, Um Anel para encontrá-los,

Um Anel para a todos trazer e na escuridão aprisioná-los

Na Terra de Mordor onde as Sombras se deitam.
```
* Cada linguagem tem um propósito principal
  * https://www.educba.com/python-vs-scala/
  * https://www.pluralsight.com/blog/software-development/scala-vs-python
  * https://wrobstory.gitbooks.io/python-to-scala/content/variables/README.html

## Blogs with nice material
* https://realpython.com/
* https://jtemporal.com/
* https://leportella.com/
* https://pythonprogramming.net/

## Everything starts with python
* https://realpython.com/installing-python/

## Installing packages with pip
* Newest versions of Python come with pip installed as a default
* pip install '<'package'>'

## python virtual environment
* cada projeto tem seu repo de dependências
* sem venv todos projetos apontam para um rep global que não tem controle de versões de dependências
* pip install virtualenv (if python 2 - python 3 come with venv by default)
* creating an virtual environment
  * Python 2:
    * virtualenv env
  * Python 3:
    * python3 -m venv env
* activating venv
  * source env/bin/activate
* deactivating venv
  * deactivate
* Managing Virtual Environments With virtualenvwrapper
  * Organizes all of your virtual environments in one location
  * Provides methods to help you easily create, delete, and copy environments
  * Provides a single command to switch between environments
  * pip install virtualenvwrapper
    * workon - allows to list and activate venv
      * workon
      * workon venv     
    * deactivate - deactivates a venv
    * mkvirtualenv - creates and activate a new venv
    * cdvirtualenv 
    * rmvirtualenv - removes venv
  * Starting a new project  with vitualenvwrapper
    * mkvirtualenv my-new-project
* https://realpython.com/python-virtual-environments-a-primer/

## setuptools
https://pythonhosted.org/an_example_pypi_project/setuptools.html

## requirements.txt
* receita de bolo para as dependências que o precisa instalar para o projeto
* pip install -r requirements.txt (installing package requirements)
* pip freeze > requirements.txt (creating a requirements file)
* https://jtemporal.com/requirements-txt/

## Automated Unit Testing

* https://realpython.com/python-testing/

## Deploying

* Pyinstaller: https://realpython.com/pyinstaller-python/
* CI: https://realpython.com/python-continuous-integration/

## Documenting
* Documenting Python Code: A Complete Guide: https://realpython.com/documenting-python-code/

## Good Practices

* KISS, YAGNI, DRY: https://www.quora.com/How-can-I-go-from-writing-spaghetti-code-to-coding-like-professional
* SOLID principles: https://hackernoon.com/solid-principles-made-easy-67b1246bcdf
* simplicity, clarity, generality: http://ptgmedia.pearsoncmg.com/images/9780201615869/samplepages/020161586X.pdf
* Zen of python: https://www.python.org/dev/peps/pep-0020/
* Writing great python code: https://docs.python-guide.org/
* Refactoring Python Applications for Simplicity: https://realpython.com/python-refactoring/
* Python Code Quality: Tools & Best Practices: https://realpython.com/python-code-quality/
* Parameterization: https://hackernoon.com/4-ways-to-manage-the-configuration-in-python-4623049e841b

## Python in JnJ

## Community of Practice notes
* Enterprise Integration Patterns by Gregor Hoppe
* Designing Data-Intensive Applications by Martin Kleppmann
* Cater to Python development resources
    * Leverage Python Libraries
    * RxPy - The basis for the entire set of integrations
    * Arrow - Date parsing utility
    * Avro - Serialization library
    * langcodes - Standardizing language codes and country codes
    * pandas - A data analysis tool useful for loading information
    * numpy - A numerical processing library

