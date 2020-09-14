---
title: Contributing Content
---

1. Navigate to the directory for the current year.
2. Add papers to the contents/readings directory.
3. Edit <year>.md for your date.
    - Write your name(s) in the "Students:" line.
    - List the papers in the "Readings:" line.
        - Include a link to the paper, _i.e._, `Readings: [citation in author/year format](URL to paper on GitHub)`
			- NOTE: the URL to a directory or a file is slightly different from its location in the repository.
			- For directories: if the location of the directory is `content/years/2017/bibliographies`, the corresponding URL is: `github.com/mikeryanmay/IB290/tree/master/content/years/2017/bibliographies`. The `github.com/mikeryanmay/IB290/blob/master` is important!
			- For files: this is much the same as for directories, but you need to add `github.com/mikeryanmay/blob/master` before the path to the filename.
4. Push your changes to the remote repository.
    - `cd <your repository directory>`
    - `git add .` to stage your edits.
    - `git commit -m "including our papers"` to commit your edits to your local repository./
    - `git pull` to synchronize your local repository with the remote.
    - `git push` to synchronize the remote repository with your local repository.
5. Repeat the above steps to include your annotated bibliography and slides when they are complete. 
