# Extras

Some other shortcuts/tricks that are nice to know.

## clear

```
$ clear
```

`clear` just scrolls up your terminal giving you lots of blank space. Your history is still there, just scrolled out of the way.

## chaining path shortcuts

The path shortcuts we showed earlier can be chained.

`../..`  to get to a grandparent directory.  You can chain all the `..`'s you want, but unless you can keep track of which folder you ended up in, I don't recommend more than 2 or 3 in a row.

To look inside a grandparent folder `ls ../..`  To go to a grandparent folder `cd ../..`

You can also build a path off of your home directory shortcut `~`, as talked about earlier.  `~/Desktop`  You can use this to go to or look inside that folder from anywhere.  

Remember `~` creates an absolute path, not a relative one.  You can be in any folder when using an absolute path.

## cd

If you ever type `cd` without any arguments, its actually a short itself for `cd ~`.  It will take you to your home directory by default.
