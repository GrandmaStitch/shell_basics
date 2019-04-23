[Linux commands](https://ss64.com/bash/)

### echo comment

  - `echo 'hello shello!'`

  - `echo $COLUMNS x $LINES`

### ls

  - `ls -a`

  - `ls -l`

  - `ls -al *.jpg`

  - `ls bear*`

### cd

### pwd

### mkdir

### mv

  - `mv apple orange`
    rename the file apple as orange

  - `mv orange /example/directory/`
    move the file orange to /example/directory/ directory

  - `mv 'example/dirctory/apple' example`
    only use quotes stat a directory or a file

  - `mv example/dirctory/*.jpg example`

### curl

  - `curl -L 'https://www.google.com/'`
    -L means of following redirects

  - `curl -o google.html -L 'https://www.google.com/'`
    retrieve a web page and save to a file

### cat

### less

  - press j: forward one line
  - press k: backward one line
  - press f: forward one window
  - press b: backward one window
  - press q: exit

  - /pattern: search forward for pattern matching line

  - g: go to the first line in file
  - G: go to the last line in file

### tail

  - `tail -50 lookup.txt`
    extract the last 50 line from the file

### rm

  - `rm abc.txt`
    remove files

  - `rm -rf abc.txt`
    force remove files or dirctories

  - `rm -i abc.txt`
    prompt before every removal

### rmdir

  - `rmdir dirs`
    remove directories

### grep - "global regular expression print"

  - `grep 'hunting the snark' example.txt`
    search the file for the string 'hunting the snark'

  - `grep shell example.txt | less`
    send the output into the less command

  - `curl -L 'https://www.google.com/' | grep google`
    stat the output which match for the pattern

  - `grep -F -x -v -f paid.txt invoices.txt >paidinvoices.txt`
    remove lines from invoices.txt if they appear in paid.txt

### wc - print out 'newlines, words, bytes'

  - `wc -l google.html`
    count the number of lines in the file

  - `wc -w google.html`
    count the number of words in the file

  - `grep google google.html | wc -w`
    count the number of word 'google' in the file

### whoami

### .

the current directory

### ..

the parent directory

### ~

the home directory