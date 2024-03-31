<!-- @format -->

- Python used: 3.10.12.
- OS: linux, can use wsl for windows.
- Install requirements: `python3 -m pip install -r ./requirements.txt`
  or `python -m pip install -r ./requirements.txt` or
  `pip install -r ./requirements.txt` (Same for requirements2.txt)
- Recommended: lifehack to not fail when failing to install a
  dependency:
  `cat requirements.txt | xargs -n 1 python3 -m pip install` (does not
  work for requirements2.txt)
- For wsl. Edit code: `code .` -> Will open a visual studio code
  server instance in the current directory.
- Dataset from: https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification/data