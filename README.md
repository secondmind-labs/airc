
# Instructions


### Step 1: Extract the ZIP file

Extract the ZIP file into a directory on your computer. The directory should contain a file called `UV.exe`. If this is missing (or if you are running on a platform other than Windows) you can download it from https://github.com/astral-sh/uv/releases or (if you already have Python installed) install it with `pip install uv`.


### Step 2: Start Jupyter

In a command prompt, navigate to the directory and run:

```
uv run jupyter-notebook
```

The first time you run this, it will install Python (if necessary) and the relevant dependent packages, and create a virtual environment. Subsequent times will not require this and so will be much quicker.
