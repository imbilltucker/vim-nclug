Here's some advice for what to put in your .vimrc file
-----------


#Don't use 8bit arithmetic much?  Set how your numbers are treated..
set nrformats=alpha

#Use these to let vim determine your indention by file suffix
set autoindent 
set expandtab 

#Like using a mouse? This lets you use it to resize your split vim windows (plus scrolling with scrollwheel)
set mouse=a

# :vnew makes new window to the right with this
set splitright

# :new makes new window to the below with this
set splitbelow


#it's a good idea to have a keystroke that toggles :set paste
set pastetoggle=<Leader>p

#tweak color scheme 
set background=dark

#use leader toggle set paste
nmap <silent> <leader>p :set paste<CR>
nmap <silent> <leader>P :set nopaste<CR>

#do not change to an alternate terminal when exiting vi
set modeline

#Perform syntax highlighting on only 600 chars.. longer that that and vim can get confused on long lines
set synmaxcol=600

