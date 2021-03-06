# Week 4 Assignment

![](../../images/Draft_Version_picture.png)

Submit your completed assignment (**.ipynb** files) onto Moodle for peer assessment.

## Submission deadline: Saturday, September 19th, 2015, 6:00 PM

## Problem 4.1. See template:

## Problem 4.2. See template: [unix\_ipython](unix_ipython.ipynb)

### How to download the templates

You can download the template by updating your local course repository that you created in [Week 1 Lesson 2](https://github.com/UI-DataScience/info490-fa15/blob/master/Week1/lesson2.md), e.g. `/home/data_scientist/info490`. Open a terminal, either by using _New_ -> _Terminal_ in the IPython/Jupyter notebooks server, or by using the interactive terminal mode in Docker:

```shell
$ docker exec -it <container name> /bin/bash
```

You can find the container name by doing `docker ps`. At the Unix shell, go to the directory where the course repository is mounted,

```shell
$ cd /home/data_scientist/info490
```

and use `git pull` to update the local repository:

```shell
$ git pull
```

Now, if you navigate to `/home/data_scientist/info490/Week4/assignment`, you will discover that the `git pull` command has updated the contents of the local repository.
