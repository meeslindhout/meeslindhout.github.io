---
layout: single
permalink: /Resources/
title: "Resources"   
toc: true
toc_label: "On this page"
---


## People that inspire me
- Paul Graham's [blog](https://www.paulgraham.com) (Paul Graham is the founder of Y Combinator, a startup accelerator in Silicon Valley. He has written many essays on startups, programming, and life. His essays are insightful and thought-provoking.)

- Chris McCormick's [blog](https://mccormickml.com) (Chris McCormick is a machine learning researcher and content creator. He has a blog where he shares tutorials on machine learning, deep learning, and natural language processing. His tutorials are beginner-friendly and easy to follow.)

- Adam Savage's [YouTube channel](https://www.youtube.com/user/testedcom) (Adam Savage, one of the presenters of MythBusters, shares his experiences on his YouTube channel. His content ranges from engineering to career advice and much more.)

- Josh Starmer [YouTube channel](https://www.youtube.com/channel/UCtYLUTtgS3k1Fg4y5tAhLbw) (Josh Starmer is a biostatistician and content creator. He has a YouTube channel where he explains statistical concepts in an easy-to-understand way. His videos are engaging and informative.)


## Courses and lectures that fascinate me
- MIT 18.S096 Topics in Mathematics with Applications in Finance by MIT [YouTube playlist](https://www.youtube.com/playlist?list=PLUl4u3cNGP63ctJIEC1UnZ0btsphnnoHR)

- MIT 6.S191 Introduction to Deep Learning [YouTube channel](https://www.youtube.com/@AAmini/videos) & [Course material](https://introtodeeplearning.com/2023/index.html)

- Stanford CS229 by Andrew Ng [YouTube playlist](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU)

- Stanford CS231n Convolutional Neural Networks for Visual Recognition by Fei-Fei Li [YouTube playlist](https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv)


## Online tools that I use
- [Excalidraw](https://excalidraw.com) is a whiteboard tool that lets you sketch diagrams and illustrations. It's great for brainstorming, wireframing, and explaining abstract / complex ideas.

- [Html Edit](https://htmledit.squarefree.com) is an online HTML editor that lets you write and test HTML, CSS, and JavaScript code. It's great for creating and testing web pages.)

- [Typingmind](https://typingmind.com) is a platform that integrates various large language models (LLMs) into a single website, allowing users to interact with them using API codes.

- [Regular expressions 101](https://regex101.com/) is an online tool that lets you test and debug regular expressions quickly.

<!-- TODO: add books to recommendation list -->
<!-- ## Some books that I recommend if...
- You want to learn about the Aviation industry:
-  -->
<!-- # Books
- ⏳ [Deep Learning](http://www.deeplearningbook.org/)
- ⏳ [The Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)
- ⏳ [The Hundred-Page Machine Learning Book](http://themlbook.com/)
- https://virgili0.github.io  -->

<!-- TODO: add more python packages to recommendation list -->
<!-- ## Inpsiring python packages
- [Polars]() is a blazingly fast DataFrame library implemented in Rust. It is designed to be a drop-in replacement for pandas, but with much better performance. -->
<!-- - [Paper-qa]() -->

<!-- TODO: Extract necesarry content from below (chris tan) -->
<!-- My most frequently-used tools to set up working space, monitor machine learning projects and deploy models.

## 1. Set Up Virtual Machines
- [Google Cloud setup and tutorial](https://github.com/cs231n/gcloud/): A comprehensive tutorial to set up a Google Cloud virtual machine by [CS231n](http://cs231n.stanford.edu/) (Stanford).
- [Server setup tutorial by fast.ai](https://course.fast.ai/start_gcp.html): Tutorials to set up virtual machines on Google Cloud, Azure, AWS... for fast.ai courses.
- [Remote SSH with Visual Studio Code](https://code.visualstudio.com/blogs/2019/07/25/remote-ssh): A tutorial to connect to virtual machines on VSCode with Remote SSH. It helps making working on VM easy and smooth as working locally.

## 2. Set Up Work Spaces
- [Byobu](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-byobu-for-terminal-management-on-ubuntu-16-04) for Terminal Management: My favorite tool when wokring on cloud. Byobu allows us to create sessions to open multiple terminal windows. We can detach a session and turn off our computer when training models on cloud and reactivate the session later to continue the training process.
- [Managing Anaconda environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html): Everything we need to know to manage our conda virtual environments.
- [Setting up a Data Science environment using WSL and Jupyter](https://towardsdatascience.com/setting-up-a-data-science-environment-using-windows-subsystem-for-linux-wsl-c4b390803dd): A guide to set up Windows Subsystem for Linux (WSL), install Anaconda and Jupyter on Ubuntu.
- [Oh-my-zsh and agnoster theme](https://blog.joaograssi.com/windows-subsystem-for-linux-with-oh-my-zsh-conemu/): Set up a beautiful and functional theme for your terminal.
![](https://github.com/apodkutin/agnoster-zsh-theme/raw/customize-prompt/agnoster_customization.gif)
- [Setting up development environment for machine learning](https://www.youtube.com/watch?v=N9lo_UxSkWA) by Abhishek Thakur: A YouTube tutorial to set up development environment for machine learning projects.
- [Ipykernel](https://ipython.readthedocs.io/en/stable/install/kernel_install.html#kernels-for-different-environments): Create kernels for different environments so we can switch environments within Jupyter Lab/Notebook.

## 3. VSCode
![](/assets/images/blogs/vscode-workspace.gif)
My favorite VSCode setup for machine learning projects 🤗. First, I use `RemoteSSH` extension to SSH to a virtual machine. It makes interacting with files on cloud as smooth as working locally. Then I use `Byobu` to open multiple terminal windows: `htop` (monitor CPUs), `watch -n1 nvidia-smi` (monitor GPUs), `jupyter lab`, `tensorboard dev upload --logdir .` (upload logs to [TensorBoard.dev](https://tensorboard.dev/)) etc. I can press `F2` to create a new window and press `F4` to switch between windows. Extremely convenient ⚡!
{: .small}

- Extensions:
  - 🌟RemoteSSH: Open any folder on a remote machine using SSH and take advantage of VS Code's full feature set.
  - GitLens: Make Git more powerful on Visual Studio Code.
  - [Peacock](https://www.peacockcode.dev/): Subtly change the workspace color of our workspace. Ideal when we have multiple VSCode instances.
  - vscode-icons: Icons for Visual Studio Code.
  - Bracket Pair Colorizer: A customizable extension for colorizing matching brackets.
  - Code Spell Checker: Spelling checker for source code.
  - Setting Sync: Synchronize settings, snippets, themes, file icons, launch, keybindings, workspaces and extensions across multiple machines.
  - Prettier: Code formatter using prettier.
- [Config code formatter](https://code.visualstudio.com/docs/python/editing#_formatting)
- [Add vertical rulers](https://stackoverflow.com/questions/29968499/vertical-rulers-in-visual-studio-code)

## 4. Git
Some basic guides to interact with Git.
- [GitHub Guides](https://guides.github.com/)
- [Adding an existing project to GitHub using the command line](https://docs.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line)
- [Oh-my-zsh Git alias](https://github.com/ohmyzsh/ohmyzsh/wiki/Cheatsheet): for extremely fast Git actions.

## 5. Production
After finishing important machine learning projects, I always want to deploy a simple prototype of my model with Streamlit to illustrate its usage or to present my works with the audience.
- [Streamlit API](https://docs.streamlit.io/en/stable/api.html#magic-commands)
- [Quickly Build and Deploy a Dashboard with Streamlit and Heroku](https://towardsdatascience.com/quickly-build-and-deploy-an-application-with-streamlit-988ca08c7e83)

## 6. Cheatsheet
- [Linux](https://files.fosswire.com/2007/08/fwunixref.pdf)
- [Regular Expression](https://www.programiz.com/python-programming/regex)
- [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links)

## 7. Misc
- Docstring: [Example Google Style Python Docstrings](https://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html)
- LaTex:
  - [LaTex Online Editor](https://latex.codecogs.com/eqneditor/editor.php)
  - [Handwritten symbols to LaTex](http://write-math.com/)
  - [Math symbols collection](https://leimao.github.io/downloads/tools/Latex-Guidance/Symbols.pdf)
- Style guide: [Computer Science Style Guide: ACM, APA and IEEE](https://dal.ca.libguides.com/c.php?g=257109&p=1717772#jaxiee)
- [Google Drive Link Generator](https://www.wonderplugin.com/online-tools/google-drive-direct-link-generator/) -->


<!-- - Data Analysis with Dr Mike Pound https://www.youtube.com/playlist?list=PLzH6n4zXuckpfMu_4Ff8E7Z1behQks5ba (Mike Pound is a computer scientist and lecturer at the University of Nottingham. He has a YouTube channel where he explains computer science concepts in a fun and engaging way.) -->



