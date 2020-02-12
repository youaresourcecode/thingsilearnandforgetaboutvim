# thingsilearnandforgetaboutvim
The things I learn and forget about vim

1. How to execute current line in bash or zsh: :.w !bash 
Also  :exec '!'.getline('.') que dicen que puede mapearse
con una tecla por ejemplo: nmap <F6> :exec '!'.getline('.')
Fuente: https://stackoverflow.com/questions/19883917/execute-current-line-in-bash-from-vim

2. Searching, just 4 things to remember ... 
/pattern       - search forward for pattern
?pattern       - search backward
n              - repeat forward search
N              - repeat backward

3. Delete from cursor to the beginning of the line with d0,
   from the cursor to the end of the line with d$ or C. And
then R activates remplacing text.

4. Replace in the same line: 
· Globalmente: :%s/"/'/g (el % indica todo el doc)
· Globalmente y con confirmación: :%s/"/'/gc
· En una línea, la primera ocurrencia: :s/'/"/
· En una línea, toda la fila: :s/'/"/g 
· Buscar sobre la selcción \%V donde pones la comilla simple

5. Paste exactly in a place: Instead of yy, use 0y$, and move to where you want to put it, and press p or P.

6. 
