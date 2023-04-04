# cbflec
Color-blind friendly Beamer theme for lectures

## How to Use
There are two ways to use the beamer theme **cbflec**:

1. Place the style file (**beamerthemecbflec.sty**) in the same folder that contains your tex file. You need to do this whenever you want to use the theme.
2. Or more conveniently, assuming you are a Mac user, follow the MacTeX distribution's [suggestion](https://tug.org/mactex/READ_ME_FIRST.pdf) (see section MacTeX for Experts):
	1. Create a folder named **texmf** in `~/Library` so that you have the location `~/Library/texmf` (`~` means home directory). Library folder under home directory is hidden from view. Press **Command + Shift + .** to view the folder. If you are not sure about this step, read more [here](https://tex.stackexchange.com/questions/10252/how-do-i-add-a-sty-file-to-my-mactex-texshop-installation).
  	2. In that location, first create a subfolder named **tex**. Inside the **tex** folder, then create another subfolder named **latex** so that you have the location `~/Library/texmf/tex/latex`.
	3. Place **beamerthemecbflec.sty** in the subsubfolder you create in step 2.

The second option allows you to use **cbflec** directly.

Finally, insert `\usetheme{cbflec}` in the preamble of your tex file.
