+++
title = "Freiluftkino"
date = 2018-08-05
draft = false
[taxonomies]
tags = ["scraping", "movies"]
category = ["project"]
+++

I tried to learn how to scrape websites in Python.

One use case that came to mind was open air cinemas (*Freiluftkino*) in Berlin which I love going to. But I'm always annoyed when trying to look up the screenings because there is no central page where you can see what is playing in very one of them on a given day.

So I wrote my first scraper to scrape the schedules of the open air cinemas that I know I frequent and wrote a little website.

Sadly the huge success of this project never came to be because I could not figure out how to configure Selenium on Travis CI and make at cron job work that would scrape the pages every day to update the schedule. Can you believe it?

Well, at least I have a nice foundation for next year's open air movie season.

[Live page](https://lislis.de/projects/freiluftkino/) and [code for it](https://gitlab.com/lislis/open-air-cinema-berlin).
