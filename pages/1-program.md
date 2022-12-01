---
title: Programme
nav: Programs
---

9 Dec 2022, Perth, Australia

**Opening speech**: A/Prof Guodong Long

**Session 1: Invited talks for federated learning and its applications.**

Perth time 10:00 - 12:30 am\
Sydney/Canberra/Melbourne time: 13:00 - 15:30

10:00 - 10:30 am (Perth time)\
Title: Healthcare Analytics and Federated learning\
Presenter: Dr Allison Clarke, Commonwealth Department of Health, Australia

10:30 - 11:00 am (Perth time)\
Title: The rise of machine learning and federated learning in space and astronomy\
Presenter: Dr Aidan Hotan, CSRIO, Australia

11:00 - 11:30 am (Perth time)\
Title: Adversarial Attacks and Defenses in Deep Learning: from a Perspective of Cybersecurity\
Presenter: A/Prof Tianqing Zhu, University of Technology Sydney, Australia

11:30 - 12:00  (Perth time)\
Title: Federated causal learning and reasoning\
Presenter: Dr Mingming Gong, University of Melbourne, Australia

12:00 - 12:30  (Perth time)\
Title: Privacy Preservation in Collaborative Learning\
Presenter: Dr Guandong Bai, University of Queensland, Australia


**Session 2: Invited presentation for research papers on federated learning** (15 minutes for each: 15 minutes presentation, 5 minutes Q&A)

Perth time 13:30 - 15:10\
Sydney time: 16:30 - 18:10


13:30 - 13:50 (Perth  time)\
Title: Federated learning for noise labels.\
Presenter: Zhuowei Wang (offline)\
Paper in TMLR

13:50 - 14:10 (Perth  time)\
Title: Federated Learning from Pre-Trained Models: A Contrastive Learning Approach\
Presenter: Yue Tan (online)\
Paper in NeurIPS 2022

14:10 - 14:30 (Perth  time)\
Title: Personalized Federated Learning With A Graph\
Presenter: Fenwen Chen (online)\
Paper in IJCAI 2022

14:30 - 14:50 (Perth  time)\
Title: On the convergence of clustered federated learning\
Presenter: Jie Ma (online)\
Paper in TNNLS 2022

14:50 - 15:10 (Perth  time)\
Title: Confined gradient descent: Privacy-preserving optimization for federated learning\
Presenter: Yanjun Zhang (online)


<!--### To be decided soon 

To create your own materials using `workshop-template-b`, please create a free [GitHub account](https://github.com/join) if you do not have one already.
Basic familiarity with the GitHub web interface will be helpful.

For a quick introduction check out GitHub's [Hello World guide](https://guides.github.com/activities/hello-world/), or the extensive [GitHub Learning Lab](https://lab.github.com/).

It is possible to create a website with this template using only GitHub's web interface--in fact, it works great!
However, for more advanced uses you will want Git, Ruby, and Jekyll installed on your computer to do local development.

{% capture text %}
1. Have a [GitHub](https://github.com) account.
2. Optional: have [Git](https://git-scm.com/), [Jekyll](https://jekyllrb.com/), and a nice [text editor](https://code.visualstudio.com/) installed.
{% endcapture %}
{% include card.html text=text header="Setup Overview" %}

-------------

## Local Jekyll Setup [very optional]

### Install Git

[Git](https://git-scm.com/) is a [free](https://www.gnu.org/philosophy/free-sw.en.html), [distributed](https://en.wikipedia.org/wiki/Distributed_version_control) version control system. [GitHub](https://github.com/) is a Git repository hosting service, a place to store and sync your work in the cloud--your Jekyll and GitHub Pages projects will be under Git version control, so you need the software on your machine. 

- Windows: install [Git for Windows](https://git-for-windows.github.io/) using the default options. This will give you Git, Git Bash, and Git GUI. Git Bash is a great terminal that lets you use UNIX style commands on Windows.
- Mac: check if Git is already installed by opening terminal and typing `git --version`. If you do not have it, download the official [Mac installer](https://git-scm.com/downloads).
- Linux: check if Git is already installed by opening terminal and typing `git --version`. If you do not have it, install from your distribution's software center or package manager (for Ubuntu `sudo apt install git`).

If you are interested in using a visual GUI application integrated with GitHub, Windows and Mac users should also install [GitHub Desktop](https://desktop.github.com/) using the default options.
You can install GitHub Desktop in addition to other versions of Git.

There are other [GUI apps available](https://git-scm.com/downloads/guis) for managing and visualizing Git repositories, including Linux options.

### Install Ruby

[Ruby](https://www.ruby-lang.org/en/){:target="_blank" rel="noopener"} is a open source programming language popular with web applications.
**_You do not need to know anything about Ruby_**, but you do need it to run Jekyll on your system!

Jekyll requires a Ruby version 2.4.0 or greater.
Below are quick start steps, but you may want to refer to Jekyll's official [installation guides](https://jekyllrb.com/docs/installation/) for tips.

- **Windows:** Use [RubyInstaller for Windows](https://rubyinstaller.org/){:target="_blank" rel="noopener"}.
    - First, [download](https://rubyinstaller.org/downloads/) the suggested stable version "WITH DEVKIT" (as of this writing, Ruby+Devkit 2.7.X (x64)) and double click to install. Use the install defaults, but make sure "Add Ruby executables to your PATH" is checked. On the final step, ensure the box to start the MSYS2 DevKit is checked.
    - Second, the installer will open a terminal window with options to install MSYS2 DevKit components. Choose option 3, "MSYS2 and MINGW development toolchain", or simply press ENTER to install all the necessary dependencies. The installer will proceed through a bunch of steps outputting a bunch of text in the terminal window. *Eventually*, this will conclude and you should see a message with the word `success` in it. If the window doesn't close, press `Enter` again or manually close it. (The installer can be restarted by typing `ridk install` into a command prompt).
- **Mac:** OS X has a version of Ruby installed by default. Check the version with `ruby -v`. If it is > 2.4.0 you can use the system Ruby. However, a newer version can be installed using [Homebrew](https://brew.sh/), `brew install ruby`, or a manager such as [rbenv](https://github.com/rbenv/rbenv) or [RVM](http://rvm.io/). Check the official Jekyll [Mac install docs](https://jekyllrb.com/docs/installation/#macOS) for tips.
- **Linux:** Even though the version will not be the most up-to-date, the simplest method is to use your distro's repositories. For example on Ubuntu, `sudo apt install ruby-full`. Make sure the repository version is > 2.4.0. You will also need the build tools Make and GCC, on Ubuntu get them with `sudo apt install build-essential`. For a more up-to-date version, use a manager such as  [rbenv](https://github.com/rbenv/rbenv) or [RVM](http://rvm.io/).

### Install Jekyll

Jekyll is a Gem, a software package installed via Ruby's management system called RubyGems (similar to Python's Pip). 
Open a terminal and type:
`gem install jekyll bundler`

This will take a minute as Gem installs all the dependencies and builds extensions. 

### Install Text Editor

When working with code you should have a good text editor.
Windows notepad does not handle UTF-8 encoding or UNIX line endings that are standard for cross platform applications. 
For basic editing, Windows [Notepad++](https://notepad-plus-plus.org/), Mac TextEdit, or Linux Gedit are sufficient.
However, a more complete code editor will be helpful for managing Jekyll projects.

Open-source cross platform suggestions:

- [Visual Studio Code](https://code.visualstudio.com/)
- [Atom](https://atom.io/)

Tip: you can click `.` on any GitHub repository to [open the web editor](https://docs.github.com/en/codespaces/the-githubdev-web-based-editor) (which is a light version of VS Code)!
-->
