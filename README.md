# pynw-open-source-contribution-workshop

The idea of this workshop is to introduce newcomers to open-source contribution with a focus on Python of course. This repository contains a Python script yt_happy_or_sad.py that takes a Youtube url as an argument and counts the happy and sad words. The script is quite rough and there's several issues to fix that have been reported in the issues [tab](https://github.com/c-rhodes/pynw-open-source-contribution-workshop/issues). The focus is less on the code and more on the overall process of contributing. The bottom of this README contains some useful links to guides and other projects that can be contributed to. 

Contributing
------------
Setup Git if you haven't already: https://help.github.com/articles/set-up-git/

First create a fork of this repository by clicking the Fork button at the top right of this Github page. This will create a copy of this repository under your user account.

More information on forking [here](https://help.github.com/articles/fork-a-repo/)

Clone the repository, you should be able to find the link by clicking the Clone or Download button:

    $ git clone https://github.com/YOUR-USERNAME/pynw-open-source-contribution-workshop.git
    
Install requirements:

    $ pip install -r requirements.txt

If you're using Python 2 >=2.7.9 or Python 3 >=3.4 then pip should already be installed, if not you can get pip from [here]( https://pip.pypa.io/en/stable/installing/)

Once everything is setup you can begin contributing, a list of issues can be found [here](https://github.com/c-rhodes/pynw-open-source-contribution-workshop/issues)

After fixing an issue you can commit your changes:

    $ git commit am -"Fixed XXX"
    
Once committed the changes can be pushed:

    $ git push

The final step is to create a [pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/)

Usage
-----
Example:
  
    $ python yt_happy_or_sad.py "https://www.youtube.com/watch?v=dQw4w9WgXcQ"

List of projects to contribute to and useful links:
----------------------------------
* https://github.com/vinta/awesome-python
* https://github.com/servo/servo
* https://openhatch.org/

From Dave Jones:
* https://github.com/waveform80/compoundpi/issues
* https://github.com/PiNet/PiNet/issues
* https://github.com/RPi-Distro/python-gpiozero/issues
