# Aarhus University Health Quarto Dissertation Template

This is a Quarto extension that renders a PDF of a dissertation/thesis that follows the criteriae for a PhD dissertation at the Graduate School of Health, Aarhus University. I created it by building upon the work of [Dr. Alberto Guzman's template for Pitt](https://github.com/alberto-guzman/quarto-dissertation) as well as [MR. FC Meyer's template for Vanderbilt](https://github.com/fcmeyer/vu-quarto-dissertation). 

My main goal was to have a working template for handing in my own dissertation in spring 2025.

The extension primarily works using Quarto and a series of LaTeX partials found in the `tex` folder. To use, you will need to modify within the tex folder:

- `_acknowledgements.tex`: add your acknowledgements. If you don't want this page, comment out the line `$_acknowledgements.tex()$` from `before-body.tex`. 
- `_copyright.tex`: adjust the year. If you don't want this page, comment out the line `$_copyright.tex()$` from `before-body.tex`. 
- `_dedication.tex`: add your dedication. If you don't want this page, comment out the line `$_copyright.tex()$` from `before-body.tex`. 
- `_title.tex`: only change your major and committee member names

The template was created to be used for a 3-paper dissertation/thesis, although it can be easily modified to accommodate a traditional dissertation – just swap the .qmd files with your dissertation chapters.

Some things may not be quite up to standards; please make sure you review the regulations at [the Graduate School of Healths website](https://phd.health.au.dk/doingaphd/dissertation/) as I will not be responsible for inaccuracies.

## Installing the extension

To use this extension, navigate to your desired directory and type the following command in your terminal:

```{bash}
quarto use template agdamsbo/au-quarto-dissertation
```

## Using template on an existing directory/folder

If you already have an existing Quarto project or document, you may add the template by typing the following in your terminal:

```{bash}
quarto add agdamsbo/au-quarto-dissertation
```

## To-do-list

The following are the pending tasks to get the template flying

- [ ] Check that everything works as desired for now after forking
- [ ] Make sure to update all text to "Graduate School of Health, Aarhus University"
- [ ] Use the AU logo on front
- [ ] Find a way to include a List of Acronyms based on [rchaput/acronyms](https://github.com/rchaput/acronyms)
- [ ] More to come, I am sure...


### Contributing to the template

From the original author:

> Writing my dissertation in Quarto was both exciting and challenging, given that Quarto had just been released. However, I believe Quarto is an amazing tool for creating reproducible dissertations. I plan on gradually creating documentation for this template, but I also welcome the help of contributors! Happy Writing!


