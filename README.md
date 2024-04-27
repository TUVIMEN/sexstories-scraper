# sexstories-scraper

A shell script for downloading sexstories in nicely formatted files

## Requirements

 - [reliq](https://github.com/TUVIMEN/reliq)

## Installation
    
    install -m 755 sexstories-scraper /usr/bin

## Json format

Here's example of a [story](story-example).

## Usage

    sexstories-scraper [DIR]

Script goes through every page of [sexstories](https://sexstories.com) and downloads every story saving it in file named by it's title.

First 8 lines are reserved for metadata

    printf 'Link "%s"\nTitle: "%s"\nAuthor: "%s"\nGenres: "%s"\nTime: "%s"\nRead: "%s"\nRated: "%s"\nVotes: "%s"\nComments: "%s"\n'

Get some help

    sexstories-scraper -h
