# Illinois Reboot 2021 Capstone Project

The project narrative is explained in `Project Capstone.ipynb`.

You should not fork this repo; instead you should [import the repo](https://github.com/new/import) to the
team captain's account and fork from there.  That version of the repo will be your primary code product.

You will also submit a full project report built on the milestones.  That may be composed any way you like
and should be sent to the Illinois Reboot administrators.  Each team should have a single report with
graphics and some code samples, with references to the rest.

The data set in `reviews.zip` is quite large, and I recommend you avoid opening it in Windows Explorer or
the macOS file browser.  On many systems, you can unzip it at the command line using

```sh
unzip reviews.zip
```

As the data sets are large, the merged database you work on will be quite large as well.  I recommend not
storing it as part of your repo; instead, you should be able to reconstruct it using code as needed.  This
is a good way to work on large data sets.  On my machine, it takes less than two minutes to reconstruct
the full database from all three data sets.

If you are interested in using SQL for part of the lesson and Python for the rest, you may find
[the PySQL module](https://swcarpentry.github.io/sql-novice-survey/10-prog/index.html) to be helpful.
