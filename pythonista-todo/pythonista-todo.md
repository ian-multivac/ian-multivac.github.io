# Todo List Sync

A Pythonista 3 script that parses text files and creates ClickUp tasks and iOS reminders for any flagged text.  Perfect for sifting through dozens of WIP projects!

## Project Overview

Todo list apps are a dime a dozen, and I often find myself hopping from one to another, depending on the project that I'm working on. Lately, I've been using Pythonista 3 on iOS a lot for prototyping small projects while I'm away from my desk. It has several really useful iOS-specific libraries that have been simple to use, but it's challenging to swap back and forth between apps to update tasks or make notes.

I also use several iPad apps to take notes that allow me to use Apple's Pencil to scrawl out handwritten text and diagrams, and I generally export those to iCloud folders. They usually contain a lot of items that I jot down to follow up with, but they can easily get lost in the shuffle. It can be painful.

This script will use the Share sheet within iOS, and process a text file line by line, looking for todo list items and keywords. If it finds them, it will create a new ClickUp task and iOS reminder item for each one, so I can more easily keep track of where I left off.



[Continue to the repository](https://github.com/ian-multivac/pythonista-todo-sync)
