# conan

This was created in an assignment.

DOI: 

The goal of this project is to visualize international tourism expenses of countries.

Using a SIPRI dataset, milspend can visualize military spending of up to four countries.

The dataset is downloadable from:

https://api.worldbank.org/v2/en/indicator/ST.INT.RCPT.CD?downloadformat=excel

The number of the vertical axis indicates the US dollars in millions.![Figure_1conan_Japan](https://user-images.githubusercontent.com/103731249/171558533-ea57dbcf-de1b-4ce0-bdcc-fb7d27504834.png)

# How to install conan on Linux, MacOS, or WSL on Windows

You may need matplotlib library.

$ pip install matplotlib

$ pip install conan

# ow to install conan if you have a trouble

$ pip install conan --force-reinstall --no-cache-dir --no-binary :all:

# How to run conan

The following command can display international tourism of Canada.
$ conan Canada

![Figure_1conan_Canada](https://user-images.githubusercontent.com/103731249/171560020-d6fe68ee-4c42-40f6-a465-31b32ea1f23f.png)
