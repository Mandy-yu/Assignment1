# Assignment1
    1  password
    2  passwd
    3  pwd
    4  passwd
    5  pwd
    6  echo $HOME
    7  echo $PATH
    8  ls
    9  pwd
   10  ls
   11  /usr/bin/ls
   12  cp ~/.bashrc ~/.bashrc.orig
   13  vim ~/.bashrc
   14  touch history.txt
   15  mkdir ~/history
   16  history > ~/history/history.txt
   17  echo history.txt
   18  cat history.txt
   19  history
   20  cat ~/history/history.txt
   21  vim ~/history/history.txt
   22  cd ~/history
   23  vim history.txt
   24  history
   25  pwd
   26  history
   27  ls
   28  cd history
   29  ls
   30  cat history.txt
   31  cd ..
   32  ll
   33  ls
   34  ll
   35  pwd
   36  cd history
   37  ll
   38  rm history.txt
   39  ll
   40  vim history.txt
   41  ll
   42  cd ..
   43  history > ~/history/history.txt
   44  ll
   45  cd //
   46  cd ..
   47  history | vim ~/history/history.txt
   48  cat ~/history/history.txt
   49    cd ~
   50    perl -MNet::FTP -e     '$ftp = new Net::FTP("ftp.ncbi.nlm.nih.gov", Passive => 1);
   51       $ftp->login; $ftp->binary;
   52       $ftp->get("/entrez/entrezdirect/edirect.tar.gz");'
   53    gunzip -c edirect.tar.gz | tar xf -
   54    rm edirect.tar.gz
   55    builtin exit
   56    /bin/bash
   57    export PATH=${PATH}:$HOME/edirect >& /dev/null || setenv PATH "${PATH}:$HOME/edirect"
   58    ./edirect/setup.sh
   59  echo "export PATH=\${PATH}:/home/chengqiy/edirect" >> $HOME/.bashrc
   60  esearch -db pubmed -query "lycopene cyclase" |   efetch -format abstract
   61  esearch -db pubmed -query "lycopene cyclase" |   efetch -format abstract > pubmed.090419.v1.txt
   62  vim pubmed.090419.v1.txt
   63  pip install wordcloud
   64  pip install --user wordcloud
   65  wordcloud_cli --text pubmed.090419.v1.txt --imagefile wordcloud.png
   66  ls
   67  vim wordcloud.png
   68  cd ..
   69  pwd
   70  ls
   71  cd /home/chengqiy
   72  ls
   73  echo wordcloud.png
   74  scp -r chengqiy@trgn.usc.edu:/home/chengqiy/wordcloud.png /home/user/Desktop/
   75  scp -r chengqiy@trgn.usc.edu:/home/chengqiy/wordcloud.png /home
   76  scp -r chengqiy@trgn.usc.edu:/home/chengqiy/wordcloud.png /User/ycq
   77  scp -r chengqiy@trgn.usc.edu:/home/chengqiy/wordcloud.png /Users/ycq
   78  scp chengqiy@trgn.usc.edu:/home/chengqiy/wordcloud.png /local/home
   79  scp chengqiy@trgn.usc.edu:/home/chengqiy/wordcloud.png /home
   80  history
   81  vim ~/.bashrc
   82  ls
   83  LL
   84  ll
   85  a=b
   86  echo a
   87  echo "a"
   88  history
   89  passwd
   90  vim ~/.bashrc
   91  pwd
   92  ls
   93  cd bin
   94  mkdir bin
   95  ls
   96  vim ~/.bashrc
   97  ls
   98  cd ..
   99  ls
  100  cd ~/.bin
  101  vim ~/.bashrc
  102  ls
  103  echo $PATH
  104  ls
  105  pwd
  106  cd ..
  107  cd ~/.bash.orig
  108  cp ~/.bashrc ~/.bashrc.orig
  109  ls ll
  110  ll
  111  ls -alk
  112  vim ~/.bashrc
  113  pwd
  114  ls
  115  ls history
  116  pwd
  117  ls
  118  ls -la
  119  ll history
  120  rm ~/history.txt
  121  ls
  122  ls ~/history
  123  esearch -db pubmed -query "RNA crosslink" |   efetch -format abstract > pubmed.090419.v1.txt
  124  vi pubmed.090419.v1.txt
  125  head pubmed.090419.v1.txt
  126  vi pubmed.090419.v1.txt
  127  head pubmed.090419.v1.txt
  128  wordcloud_cli --text pubmed.090419.v1.txt --imagefile wordcloud.png
  129  history
