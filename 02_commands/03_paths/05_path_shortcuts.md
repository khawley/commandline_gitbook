# Path Shortcuts

In discussing _relative paths_, I showed examples that started with a`.` and `..`.  These are examples of shortcuts you can use to build a path.

## The Dot `.`

`.` is used to signify your _current directory_.  Any path built on this means, "use my current directory as a starting point".  Usually this is implied and isn't needed, but you still need to understand what it means.

For example, if I'm in my `/Users` directory, to get to my `kelseyhawley` folder, I could say my next path is `kelseyhawley` or `./kelseyhawley`.  The first, `kelseyhawley` uses an implied `.`.  The second uses an explicit `.`.  Both are _relative paths_ (relative to my `/Users` directory).

## The Double Dot `..`

`..` is used to signify the _parent of your current directory_.  Any path built on this, says "go to the parent of my current directory as a starting point".

For example, if I wanted to change to a different user, and I was starting in `/Users/kelseyhawley`, I would use `../user_2`, which says go to the parent of my current directory (`/Users`), then its child (`user_2`).

```
/Users/
    kelseyhawley/  <-- starting here
    user_2/ <-- get to here
```

## Home Directory `~`

The `~` is a shortcut to your home directory.  This is unique to each user.  For my example, `/Users/kelseyhawley` is my home directory.  If I login as myself, my home directory might be `/Users/kelseyhawley`.  This home directory will be consistent each time you login, but could be different on a Windows, Linux or Mac machine.

Using `~` we can build an _absolute path_, since `~` will resolve to your absolute home directory path.

Example: `~` is the same as `/Users/kelseyhawley`.  If I had a file in `kelseyhawley` called `textfile`, the _absolute path_ to the file would be `/Users/kelseyhawley/textfile` or `~/textfile`