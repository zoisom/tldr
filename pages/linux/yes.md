# yes

> The yes command is used to output "y", or whatever word you choose, forever.

- output piped to the rm -i command, which prompts for confirmation before deleting each file :

`yes | rm -i *.txt`

- The yes outputs "n" in a constant stream to the rm -i command, answering "no" :

`yes n | rm -i *.txt`

- yes syntax :

`yes {{string}}`
