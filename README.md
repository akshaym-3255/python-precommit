# Object Oriented Programming

This repository contains the setup for python formatter black and linter flake8 can directly be used in any project.
## Run Locally

Clone the project

```bash
git clone https://github.com/akshaym-3255/python-precommit.git
```

Go to the project directory

```bash
cd python-precommit
```
Install pre-requisite
```bash
pip3 install requirements.txt
```
modify content in file test.py
```python
a = {"a": 4, "b": "hgfjgskjdfakjdfhlkjhdkjnkfdjkkdjhdfkjfkjf", "c": "isfgajfdfdkjfhijhjkbkjgbsjkbsjbsjshbksjhsgkjghskg"}
print("hello world")

b = [1, 
2,
3, 
4]
```

add file to git 
```bash
git add test.py
```

commit files
```
git commit -m "your message"
```
and see the magic black will format the files according to rules.
updated test.py will look like 
```python
a = {
    "a": 4,
    "b": "hgfjgskjdfakjdfhlkjhdkjnkfdjkkdjhdfkjfkjf",
    "c": "isfgajfdfdkjfhijhjkbkjgbsjkbsjbsjshbksjhsgkjghskg",
}
print("hello world")

b = [1, 2, 3, 4]
```


