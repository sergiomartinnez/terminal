# terminal
bases for terminal and commands that i learned in terminal course
>- cd directory change
>- -l see large format 
>- -lh human read in kilobytes
>- -la see hidden files 
>- -lS Documents by size
>- -lr reverse, 
>- tree display all the files like tree -L [n] is for watching the documents in level of your preference
>- Pwd show you the current directory. relative rute is . and .. | . is for going to a specific document | .. is for going back
>- Mkdir create directory
>- Touch create files
>- Cp copy
>- mv move and rename files
>- rm remove and -i interactive
>- rm -r remove directories
>- head show us the 10 head lines of text files (10)
>- -n n show us the specific lines of a text (head or tail)
>- tail show us the last 10 lines of text files
>- xdg-open open text files
>- Alias create fast commands for example: Alias l=”ls -lh” 
>- Man manuals
>- Info  similar to manual but shorter 
>- Whatis for knowing that commands do
>- --help helps you with what commands do
>- Ls * searching files with specifications
>- Ls *abc search files that has ABC forwards
>- Ls abc* search similarities before the asterisk 
>- Ls abc? searching only all the files ABC but with one extra character (more questionmarks more characters)
>- ls [[:upper:]]* searching files with capitals (solo archivos)
>- ls -d [[:upper:]]* for searching folders and can be changed with lower 
>- Ls [xyz]* searches files that has those letters
>- ls abc > xyz redirects  (files)
>- ls abc >> xyz accumulate 
>- | for use commands by commands like a chain and make multiple things 
>- Tee redirects
>- ; runns synchronized commands
>- && if the command before runs it will run the next
>- || or if the past commands runs it doesnt matter, the next command anyways will run
>- Ls -l tell you the permission of the file
>- Chmod change the permissions of files
>- $home home variable leads you to home and can be runned with cd $HOME
>- $PATH have the routes of the binaries that the system execute
>- Find allows you to find files ex. find ./ -name file
>- -type f= file
>- -type d= documents
>- Find ./ -size 20M sizes
>- Grep searching similarities in a file
>- Grep towers movies.csv
>- Grep -c how many occurrences there is in a file
>- Grep -c the movies.csv (1013)
>- Grep -ci ignore the uppercase or lowercase
>- Grep -v it's for all the mismatched movies 
>- Grep -vi towers
>- Wc count how many words there are, first value word lines, characters second and third number of bits L ,W, C in that order (wc -l)
>- Ifconfig show al the config of the net
>- Ping is for checking if a website is working
>- Curl gives you the format html
>- Wget brings from internet
>- Traceroute gives you the route that you are using until you connect to website
>- Netstat -i show you the devices of the net
>- Tar compress -c (compress) -v(show us what that do on the terminal) -f(compress a file)
>- -z compress in a gzip format
>- -x decompress
>- Zip compress
>- Unzip decompress
>- Ps watches all the background process that is running
>- Top show us the process that are using more resources
>- H show us all the commands that we can use
>- Kill kill process
>- Jobs watch all the background processes
>- Fg 1 is used to move the process to foreground
>- Ctrl D ends the process
>- Bg 1 is used to move the process to background
