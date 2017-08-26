# Linux Setup and Tools

# Install 
## Essentials 

1.  [Git]

    Install with `sudo apt-get install git-all`

2.  [Vundle]
    
    Install with `git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

    Nice source of Vim plugins at [vimawesome.com](https://vimawesome.com/).

## Programming tools




## LaTeX 

1. [TexLive], install with

` sudo apt-get install texlive texlive-bibtex-extra texlive-pictures texlive-lang-portuguese`

# Configure your environment 

1. [bash_profile] 

2. [Vim] place the provided `.vimrc` at your home dir.

## Scripts and config DOT files

**DOT_tmux.conf**................TMUX customized .tmux.conf</br>
**DOT_vimrc**....................VIM customized .vimrc</br>
**bash_profile**.................customizations for bash usage;</br>
**sh_git_largestobj**............find the largest files in a repository;</br>
**sh_git_listuntrackednodir**....show only untracked files in a repository;</br>
**sh_gitshrink**.................remove some files from a repository;</br>
**sh_gpg2file**..................decrypt several gpg files with input of password only once;</br>
**sh_hardlink**..................complements 'fdupes' and hardlink some equal files;</br>
**sh_iso2utf**...................convert ISO8859-1 encoded file to UTF-8;</br>
**sh_jpg2pdfA4**.................convert a JPG file into a PDF with A4 page size;</br>
**sh_pdf2jpg**...................converts single page PDF in JPG picture</br>
**sh_pdf2png**...................converts multiple pages PDF in PNG pictures (LATEX equations)</br>
**sh_pdfcat**....................concatenates multiple PDF files</br>
**sh_pdfcrop**...................crop white margin around a single page PDF file</br>
**sh_pdfsplit**..................extracts each page of a PDF in a single file</br>
**sh_svg2pdf**...................converts a list of SVG file into PDF files.</br>
**sh_uniqfile**..................creates a unique filename for a given path.</br>
**sh_utf2iso**...................converts a UTF-8 encoded file into a ISO8859-1 file.</br>

[Vundle]:http://github.com/VundleVim/Vundle.vim
[Vim]:http://www.vim.org
[Git]:http://git-scm.com
[TexLive]:https://www.tug.org/texlive/
