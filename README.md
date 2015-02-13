# Presentations

This is the official repository for [Ann Arbor R User Group](http://www.meetup.com/Ann-Arbor-R-User-Group/) presentations.

## Organization

Each meetup has its own directory named like `yyyy-mm`, e.g. `2015-01`. Within that, each presentation should have its own directory.

## Presentation Format

The preferred presentation format is an R Markdown document, though presenters can bring in additional material. For any materials that can't be reached from an arbitrary web browser, you should coordinate with the meetup host to make sure they can accomodate you.

You can find out more about creating R Markdown files [here](http://rmarkdown.rstudio.com/).

## Other tips

If your code uses random number generation use the `set.seed(some number)` function to make your results reproducible.

Try to maintain the same coding style throughout. Consider taking a look at [Hadley Wickham's style guide](http://adv-r.had.co.nz/Style.html) for general guidelines.

## Instructions for new presenters

First time presenters should message an organizer to be added to the github organization. Clone the directory for the meetup you will be presenting at (e.g. `2015-03-12`). Create a new directory and add your content, including code, data, and output. Initiate a pull request when you have finished your presentation.

### New to Git?

If you are new to version control using Git, checkout the comprehensive [documentation](http://git-scm.com/documentation).

### Adding your presentation

Clone the GitHub repository and start a new branch for your presentation:

    $ git clone https://github.com/AnnArborRUserGroup/Presentations.git
    $ cd Presentations/
    $ git branch my-presentation-branch
    $ git checkout my-presentation-branch

Make your presentation or add your files to the `presentations/yyyy-mm-dd` directory (where `yyyy-mm-dd` is the date of the meetup). When you are ready, commit your files locally and push your branch to GitHub:

    $ git add -A
    $ git commit -a -m "add your message here"
    $ git push -u origin my-presentation-branch

If you run into trouble using Git send one of the organizers a message and we will help you out.