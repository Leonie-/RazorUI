# RazorUI
Each group of gridded elements can be broken down however you like. Open the 'example.html' file in a browser, and you will see the purple boxes at the top adapt as follows:

* Wide desktop – one row of eight
* Desktop – two rows of four
* Tablet – three rows of two
* Phone – four rows of one

This works by adding classes to the grids. e.g:

```
.break-into-4-desktop { }

.break-into-2-tablet { }

etc...
```

Different elements can be shown and hidden for different size screens as required, using the appropriate classes:

```
.hidden-desktop

.hidden-tablet

.hidden-phone
```

Here are the page widths it currently uses (these can all be changed, as long as the maths works):

* Wide desktop -  1166px, gutters 10px, columns 39px
* Desktop - 950px, gutters 10px, columns 30px
* Tablet - 734px, gutters 10px, column 21px
* Phone – less than 733px, 100% fluid layout

