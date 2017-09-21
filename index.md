---
layout: default
title: Ananya Sai B
description: MTech Student (CSE), IIT Madras
---
## About Me
	Hi there, I'm Ananya! I am currently doing my MTech in Computer Science at IIT Madras. I have completed an academic adventure of exploring the breadths of Computer Science by crediting courses from various domains ranging from Compilers, Cloud computing to Indexing large datasets and Deep learning. I am currently exploring the depths of Deep Learning and NLP under the guidance of Dr Mitesh M. Khapra

## Projects
# Attentive deep neural networks for Question Answering
Modelling RNNs for reading comprehension tasks, specifically to answer questions based on given passage, by exploring various attention mechanisms
# Query plan selector for MongoDB
Implemented a query plan selector/pruner to reduce the number of query plans to be executed by predicting the best plan out of the available, if possible; else by trying to eliminate bad plans without having to execute them.
# AI-powered Pacman
Empowered pacman game character with artificial intelligence to get high scores on the game (This project was as part of edX course CS188.1x Artificial Intelligence which provided support for graphics functionalities for this project)
# Supergraph search in graph databases
Graph isomorphism being an NP problem, an edge-based tree index was built to make the search algorithm faster.
Supergraph search would be useful in graph-involved problems such as identifying malicious activities in the web, identifying diseases based on molecular structure and predicting the properties of new compounds.
# Mini Java compiler
Implemented an optimizing compiler for IR code generation along with optimizations of Conditional Constant Propagation and Function Inlining. Also added code to identify Loop Invariants and Independent Iterations for Loop Transformations and perform Alias Analysis

## Work Experience
I worked for an year at Cisco as a Software Engineer from August 2015 to June 2016. I worked on OSPF routing protocol, building a data model to enable coordinating large set of routers centrally. I also worked on RCMD (Route Convergence Monitoring and Diagnostics) project to quickly detect failures in the network.

## Teaching Experience
I work as a teaching assistant for Probability and Computing(CS5820) taught by Professor John Augustine. The work involves setting up and grading tutorials and assignments for the course.

## Academic Details
I completed my BE in Computer Science and Engineering at Sri Jayachamarajendra College of Engineering, Mysore in 2015 with a cgpa of 9.53/10.

[![Build Status](https://travis-ci.org/pages-themes/cayman.svg?branch=master)](https://travis-ci.org/pages-themes/cayman) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-cayman.svg)](https://badge.fury.io/rb/jekyll-theme-cayman)

*Cayman is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/cayman), or even [use it today](#usage).*

![Thumbnail of cayman](thumbnail.png)

## Usage

To use the Cayman theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    theme: jekyll-theme-cayman
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```



## Customizing

### Configuration variables

Cayman will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

### Layouts

If you'd like to change the theme's HTML layout:

1. [Copy the original template](https://github.com/pages-themes/cayman/blob/master/_layouts/default.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
2. Create a file called `/_layouts/default.html` in your site
3. Paste the default layout content copied in the first step
4. Customize the layout as you'd like

### Sass variables

If you'd like to change the theme's [Sass variables](https://github.com/pages-themes/cayman/blob/master/_sass/variables.scss), set new values before the `@import` line in your stylesheet:

```scss
$section-headings-color: #0086b3;

@import "{{ site.theme }}";
```

## Roadmap

See the [open issues](https://github.com/pages-themes/cayman/issues) for a list of proposed features (and known issues).

## Project philosophy

The Cayman theme is intended to make it quick and easy for GitHub Pages users to create their first (or 100th) website. The theme should meet the vast majority of users' needs out of the box, erring on the side of simplicity rather than flexibility, and provide users the opportunity to opt-in to additional complexity if they have specific needs or wish to further customize their experience (such as adding custom CSS or modifying the default layout). It should also look great, but that goes without saying.

## Contributing

Interested in contributing to Cayman? We'd love your help. Cayman is an open source project, built one contribution at a time by users like you. See [the CONTRIBUTING file](CONTRIBUTING.md) for instructions on how to contribute.

### Previewing the theme locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone down the theme's repository (`git clone https://github.com/pages-themes/cayman`)
2. `cd` into the theme's directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit [`localhost:4000`](http://localhost:4000) in your browser to preview the theme

### Running tests

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` one before the test script will work.
