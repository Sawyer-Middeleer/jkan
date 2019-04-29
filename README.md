# About this project 
This web app has gone through a couple iterations since its inception.

At first, all of the data was Chicago-based and spanned a number of categories, including transportation, 311 and education. However, it was unclear how this would be any more useful than the City of Chicago's existing data portal.

As someone who frequently uses open data for research, I have always found it cumbersome to collect data from multiple cities' data portals. This seemed like a natural opportunity to aggregate data from several cities that one might want to analyze together in one place.

Once I started bringing in other cities' data, I realized that I would need to change how I organized the data on the website. To fix this problem, I recategorized datasets by city and focused the range of data I provided to only 311 service data. The reason for this decision was threefold:

Once I categorized data by city, it became difficult to add subcategories.
Focusing on one data category now would make it easier to build on some kind of additional functionality later.
311 service is a particularly interesting category of data to compare across cities.
In the future, I hope to use the data that I've aggregated to provide some insight into what makes 311 services most effective.

## Regarding the custom.css file
This custom.css file is the individual work of Sawyer Middeleer, inspired and, in some cases,
adapted from the work done by the folks on the Estonian Open Government Data Portal (https://opendata.riik.ee/en/)
and the Open Austin project (https://www.open-austin.org/).

I used css styling primarily to improve the user experience of my site, and secondarily to create a visual identity.

I found that the base styling added extra clutter, which made it a little more difficult to find things than I thought it should be.
Since this data portal is meant to be incredibly simple, I wanted the aesthetics to facilitate user navigation as much as possible
Hover, active and focus styling hopefully improve legibility and responsiveness to user actions.

A simple, cohesive color scheme on top of the lumina theme makes the site more visually appealing than a basic gray and blue.
The maroon and gray are color choices that give the site a little UChicago pride and direct attention to the correct places.

In addition to css work here, there are small instances of html additions on other pages to add elements where
I thought they would be beneficial. For example, I added a box on the index.html page and changed how categories are organized.
I also added links to my twitter and github on the navigation bar for some added transparency into who created the website,
just in case this app ever makes it out there into the public.


# JKAN [![Build Status](https://travis-ci.org/timwis/jkan.svg?branch=gh-pages)](https://travis-ci.org/timwis/jkan) [![Join the chat at https://gitter.im/timwis/jkan](https://badges.gitter.im/timwis/jkan.svg)](https://gitter.im/timwis/jkan?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
A lightweight, backend-free open data portal, powered by Jekyll

Open-source data portals can be really hard to install and maintain. But their
basic purpose of providing links to download data really isn't that complicated. JKAN is a proof-of-concept
that allows a small, resource-strapped government agency to stand-up an open data portal by simply
[clicking the fork button](https://help.github.com/articles/fork-a-repo/).

Please note this is still a work in progress! Check out the [issues](https://github.com/timwis/jkan/issues) to help
out or give feedback.

[Demo site](https://demo.jkan.io)

## Installation
See [Get Started](https://jkan.io/#get-started) on [jkan.io](https://jkan.io) for an installation wizard,
or follow the [manual installation](https://github.com/timwis/jkan/wiki/Manual-Installation) instructions yourself.

For configuration details, see the [wiki](https://github.com/timwis/jkan/wiki)

## Development
Please see the [Architecture](https://github.com/timwis/jkan/wiki/Architecture) page in the wiki.
