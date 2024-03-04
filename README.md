# CV-Template-Latex

![Example](https://github.com/danifreflow/CV-Template-Latex/blob/main/pictures/example.png)
This is a repo for helping to make a CV uysing 
<div id = "header" align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/92/LaTeX_logo.svg/800px-LaTeX_logo.svg.png?20210414121601" width="100">
</div>
The file **Template.tex** is the one that must be change then you must export to pdf

## Step 1
Please look the code and fing the `%CHANGE` coments and put your data and your photos instead
**EXAMPLE**
```
  \begin{minipage}[t]{8cm}
    \vspace*{-0.5cm}
    \begin{tcolorbox}[grow to left by=0.6cm,colback=Lblanco,colframe=Lblanco]
      \section*{Contact}
      %CHANGE
      %change Contact data with your own contact data
      \begin{tabular}{r l}
        Tel: +34 XXX XXX XXX \\
        E-Mail: you@youremail.com \\
      \end{tabular}
```

## STEP 2 
Once you finish export your tex file into svi using

```
latex Template.tex
```
## STEP 3
Once you export the dvi file you must convert the file into a pdf so you can share it
```
dvipdf Template.dvi Template.pdf
```
## STEP 4 
Please enjoy , if you think you can make it better im open to commits 
<div id = "header" align="center">
  <img src="https://imgs.search.brave.com/8DqVuGy2xU2LW9aRC3lddP80aEDvkOD16xjjNJlRi8s/rs:fit:860:0:0/g:ce/aHR0cHM6Ly9saWJy/ZXBsYW5ldC5vcmcv/dy9pbWFnZXMvMy8z/Zi9HTlVfR2VuZXJh/dGlvbl9Mb2dvX2J5/X09yY2EucG5n" width="100">
</div>
