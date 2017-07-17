# setup
#install Amber-tools

#install Autodock-vina
cd /home/arnold/
wget "http://mgltools.scripps.edu/downloads/downloads/tars/releases/REL1.5.6/mgltools_x86_64Linux2_1.5.6.tar.gz"
tar -zxvf mgltools_x86_64Linux2_1.5.6.tar.gz
cd mgltools_x86_64Linux2_1.5.6
export PATH="$PATH:/home/arnold/mgltools_x86_64Linux2_1.5.6/bin"
alias pmv='/home/arnold/mgltools_x86_64Linux2_1.5.6/bin/pmv'
alias adt='/home/arnold/mgltools_x86_64Linux2_1.5.6/bin/adt'
alias vision='/home/arnold/mgltools_x86_64Linux2_1.5.6/bin/vision'
alias pythonsh='/home/arnold/mgltools_x86_64Linux2_1.5.6/bin/pythonsh'
export PATH="$PATH:/home/arnold/mgltools_x86_64Linux2_1.5.6/MGLToolsPckgs/"
