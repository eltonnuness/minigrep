#Minigrep
simple grep clone, this program read the file and return lines by query passed.

##How build
`cargo build --release`

##How use
`./minigrep {query} {filename}`

example: 

`./minigrep to poem.txt`

or with no case sensitive

`CASE_INSENSITIVE=1 ./minigrep to poem.txt`




