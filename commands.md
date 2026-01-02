  124  mkdir test_dir
  125  cd test_dir/
  126  touch example.txt
  127  mv example.txt renamed_example.txt
  128  ls -l
  129  clear
  130  cd ..
  131  clear
  132  cat /etc/passwd
  133  clear
  134  head -n 5 /etc/passwd
  135  tail -n 5 /etc/passwd
  136  clear
  137  grep "root" /etc/passwd
  138  grep -w "root" /etc/passwd 
  139  clear
  140  ls
  141  zip -r test_dir.zip test_dir
  142  unzip test_dir.zip -d unzipped_dir
  143  ls
  144  wget https://example.com/sample.txt
  145  ls
  146  wget https://docs.google.com/document/d/1yUgUiHw7tEnBFFd7igALwTta-NmK1A_m_Fowf8Yr3Wg/edit?tab=t.0
  147  ls
  148  clear
  149  ls
  150  cat 'edit?tab=t.0' 
  151  clear
  152  [200~wget https://www.gnu.org/licenses/gpl-3.0.txt
  153  wget https://www.gnu.org/licenses/gpl-3.0.txt
  154  ls 
  155  cat gpl-3.0.txt 
  156  clear
  157  ls 
  158  touch secure.txt
  159  chmod 444 secure.txt
  160  ls -ld 
  161  ls -l secure.txt 
  162  clear
  163  export MY_VAR="Hello, Linux!"
  164  echo MY_VAR
  165  echo $MY_VAR
  166  clear
  167  ls
  168  history >> linux-assignment/commands.md
