# sexstories

A shell script for downloading sexstories in nicely formated files

## Requirements

 - [hgrep](https://github.com/TUVIMEN/hgrep)

## Installation
    
    install -m 755 sexstories /usr/bin

## Json format

Here's example of a [story](story-example).

## Usage

    sexstories [DIR]

Script goes through every page of [sexstories](https://sexstories.com) and downloads every story saving it in file named by it's title.

First 8 lines are reserved for metadata

    printf 'Title: "%s"\nAuthor: "%s"\nGenres: "%s"\nTime: "%s"\nRead: "%s"\nRated: "%s"\nVotes: "%s"\nComments: "%s"\n'

Get some help

    sexstories -h
