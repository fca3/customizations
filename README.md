# Personal Linux

# Table of Contents
- [About](#about)
- [Installs](#installs)
   - [Essentials](#essentials)
   - [Programming tools](#programming-tools)
   - [LaTeX](#latex)
- [Configure](#configure)
   - [Config files](#config-files)
- [Scripts](#scripts)
- [TODO](#todo)

# About

This repositorie contains linux personal instructions and tools with:

1. Selected tools and fast instruction to install them;
1. Instructions on how to configure a new PC;
1. Config files (DOT files);
1. Script tools;

# Installs
## Essentials 

1.  [Git]

    `sudo apt-get install git-all`

1.  [Vundle]

    `git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

    Nice source of Vim plugins at [vimawesome.com](https://vimawesome.com/).
    
1.  [Curl]

    `sudo apt-get install curl`
    

## Programming tools

1.  [Meteor]

    `curl https://install.meteor.com/ | sh` 
    
1.  [Atom]

    [Download the .deb](https://atom.io/download/deb), and then:

    ```bash
    sudo dpkg -i atom-amd64.deb
    sudo apt-get -f install
    ```
## LaTeX 

* [ ] Try LaTeX Online https://pt.overleaf.com/

1. [TexLive], install with

   `sudo apt-get install texlive texlive-bibtex-extra texlive-latex-extra texlive-lang-portuguese`

# Configure

1. bash

   Copy bash_profile to /etc (eg.):
   
   `sudo cp ~/repos/personalized-linux/bash_profile /etc/`
   
   Add call to bash_profile at the /etc/bash.bashrc:
   
   `printf "\n\n#Added by [Amorim]\nsource /etc/bash_profile\n" | sudo tee -a /etc/bash.bashrc`

2. [Vim] 

   Place the provided `.vimrc` at your home dir.

## Config files

**DOT_tmux.conf**................TMUX customized .tmux.conf</br>
**DOT_vimrc**....................VIM customized .vimrc with Vundle support and selected plugins</br>
**bash_profile**.................customizations for bash usage;</br>


# Scripts
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

# TODO

* [ ] add database installs

[Vundle]:http://github.com/VundleVim/Vundle.vim
[Vim]:http://www.vim.org
[Git]:http://git-scm.com
[TexLive]:https://www.tug.org/texlive/
[Curl]:https://curl.haxx.se/
[Meteor]:https://www.meteor.com/
[Atom]:https://atom.io/
