# GDI Chicago Slides Template

These slides are built using Yeoman, with the Reveal generator. It will compile your Sass (located in `css/source`) automatically.

If you add a new Sass file that isn't a partial, you need to edit the Gruntfile. You'll see examples of where this change needs to be made.

To add a new (HTML) slide:

```
$ yo reveal:slide "Slide name"
```

To watch:

```
$ grunt server
```

To compile for distribution (`slideshow` folder):

```
$ grunt dist
```

# End result

You should have:

* a website in the `workshop` folder
* slides in the `slideshow` folder