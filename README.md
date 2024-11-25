
# Instructions


### Step 1: Extract the ZIP file

Extract the ZIP file into a directory on your computer.

> [!NOTE]  
> The resulting directory should contain a file called `UV.exe`. If this is missing (or if you are running on a platform other than Windows) you can download it from https://github.com/astral-sh/uv/releases: simply select the correct platform and extract the uv executable into the AI-RC directory.

### Step 2: Install the Microsoft C++ runtime libraries

If using Windows, download and install the latest Microsoft Visual C++ runtime libraries from https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist.

### Step 3: Start Jupyter

In a command prompt, navigate to the directory and run:

```
uv run jupyter-notebook
```

> [!NOTE]  
> If using PowerShell or bash, you may need to specify the path to uv by typing `./uv` intsead of `uv`.

The first time you run this, it will install Python (if necessary) and the relevant dependent packages, and create a virtual environment. Subsequent times will not require this and so will be much quicker.
