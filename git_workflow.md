---
title: Contributing Content
---

First, clone the repo to your local computer so that you have a local version. If you are using a PC (rather than a Mac), you'll need to install git (avoid "git bash")--I suggest you install the windows subsystem for linux (WSL), which comes with git. See [these instructions](https://www.git-tower.com/blog/git-wsl/). (As a bonus, WSL will also let you run RevBayes...)

Generally speaking, once git is installed (git comes with macs automatically so no installation necessary if you're using a mac), navigate in terminal to the directory that you'd like the course files to go, and type `git clone https://github.com/crothfels/PhyloSeminar.git`.

1. Navigate to the directory for the current year (there will be a "years" directory, and inside there you'll find a directory for each year this course has been offered).
2. Add papers to the readings directory, the annotated bibliography to the annotatedBibliographies directory, and your introductory presentation to the presentations directory.
3. Edit <year>.md for your date.
    - Write your name(s) in the "[This could be you]" line (keep the square brackets)
    - List the papers in the "Readings:" line.
        - Include a link to the paper, _i.e._, `Readings: [citation in author/year format](URL to paper on GitHub)`
			- NOTE: the URL to a file is slightly different from its location in the repository. If the location of the file is `years/2024/readings/fileName`, the corresponding URL is: `github.com/crothfels/PhyloSeminar/blob/master/years/2024/readings/fileName`. The `github.com/crothfels/PhyloSeminar/blob/master` is important!
4. Push your changes to the remote repository.
    - `cd <your repository directory>`
    - `git add .` to stage your edits.
    - `git commit -m "including our papers"` to commit your edits to your local repository./
    - `git pull` to synchronize your local repository with the remote.
    - `git push` to synchronize the remote repository with your local repository.
