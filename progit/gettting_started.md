# Getting Started

This chapter will be about getting started with Git.We will begin by explaining some background on version control tools,then move on to how to Git running on your system and finally how to get it set up to start working with.At the end of this chapter you should understand why Git is around,why you should use it and you should be all set up to do so.

## About Version Control

What is "version control",and why should you care? Version Control is a system that records changes to a file or set of files over time so that you can recall specific versions later.For the examples in this book,you will use software source code as the files being version controlled,though in reality you can do this with nearly any type of file on a computer.

If you are a graphic or web designer and want to keep every version of an image of layout(which you would most certainly want to),a Version Control System is very wise thing to use.It always you to revert selected files back to a previous state.revert the entire project back to a previous state,compare changes over time,see who last modified something that might be causing a problem,who introduced an issue and when,and more.Using a VCS also generally means that if you screw things up or lose files,you can easily recover.In addition,you get all this for very little overhead.

### Local Version Control Systems

Many people's version-control method of choice is to copy files into another directory(perhaps a time-stamped directory,if they're clever).This approach is very common because it is so simple,but it is also incredibly error prone.It is easy to forget which directory you're in and accidentally write to the wrong file or copy over files you don't mean to.

To deal with this issue,programmers long ago developed local VCSs that had s simple database that kept all the changes to files under revision control.
