Readme for JuliaTutorial
========================

This folder contains my Julia tutorials (aimed at students in finance and economics). 

*  Most files are jupyter notebooks. Click one of them to see it online. Sometimes it renders better if you activate the nbviewer (see the symbol in the upper right corner once you have opened the file).
*  To edit and run it online, use www.JuliaBox.com. It has many packages installed. In case you need further packages, see the top menu at JuliaBox.com. To get this repository to JuliaBox, use the Download (as zip) in the Github menu, unzip, then use JuliaBox to upload.
*  To edit and run it with your local Julia installation do the following: (a) start Julia; (b) ```cd(file location)```; (c) ```using IJulia```; (d) ```notebook(dir=pwd())```. You clearly need IJulia to be installed for this.
*  The subfolder Data contains some data sets used in the programs, while the subfolder Results is for output.


On the files:

1. The .jl files are functions used in some of the notebooks.

2. Tutorial_ChapterNumber_Topic.ipynb are (relatively) short notebooks organised around different topics.

3. The current version is tested on Julia 0.6, but uses mostly 0.7/1.0 syntax via the Compat.jl package. For instance, ```Compat.mean(x,dims=1)``` allows using the new 0.7/1.0 syntax in earlier Julia versions (instead of ```mean(x,1)``` in 0.6). If you run this is Julia 0.7/1.0, then the ```Compat.``` can (but does not have to) be dropped.
