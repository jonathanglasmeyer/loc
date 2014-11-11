# loc

`loc` is a LOC counter that respects `*.gitignore` and shows summaries for a whole git repo from any subfolder of this repo. 

It also respects an optional `*.locignore` (in the root of a given git repo) in which you can specify additional globbing patterns for files/folders that should not be counted.

## screenshot:
![screenshot](http://i.imgur.com/8mInetg.png)

## dependencies
- `sloccount`
- `python3`

## setup
- add this repos folder to your `$PATH`

## usage:
- run `loc` from any folder in a git repo.
