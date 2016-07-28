# myTeX
TeXsample

zacky's TeX

[Ubuntu 12.04でLaTeX環境を構築する](http://qiita.com/muniere/items/a468d4673d7bb7105dc7)

.zshrc  
.bashrc
`
    $ texc() { 
    	platex $1.tex;
    	dvipdfmx $1;
    	evince $1.pdf;
    }
`
