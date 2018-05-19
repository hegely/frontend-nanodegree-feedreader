# Feed Reader Testing

## Table of Contents

* [Overview](#overview)
* [How to Run](#how-to-run)
* [Features](#features)

## Overview

This project was created for the Udacity Front End Developer Nanodegree. In this project <a target="_blank" href="http://jasmine.github.io">Jasmine</a> is used. Jasmine is a behavior-driven development framework for testing JavaScript code.

## How to Run

Download the package from my <a target="_blank" href="https://github.com/hegely/frontend-nanodegree-feedreader/archive/master.zip">github repository</a>. Open index.html in the browser. Jasmine tests will run automatically, results will be displayed on the bottom of the screen.

## Features

- User can choose RSS Feed from the menu at the top left of the screen.
- Several Tests are performed on the page load:
	- allFeeds variable is defined
	- Feed URLs are defined and not empty
	- Feed name is defined and not empty
	- Menu icon is hidden by default
	- Menu icon is visibile on click
	- Initial Entries - loadFeed has at least one feed entry
	- New Feed Selection - content changes when a new feed is loaded
