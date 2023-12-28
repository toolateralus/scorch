#### to clone this repo & submodules ::

##### _for linux:_ 

first 
`git clone https://github.com/toolateralus/scorch`

then (the important step),
`git submodule update --init --recursive`


to use the language (runs the file `scorch-interpreter/scorch_src/main.scorch`):

`cd scorch-interpreter ; cargo r --release`

to use the language from a command line REPL (read, eval, print loop) 

`cd scorch-interpeter ; cargo r --release cli`

to dump the token output, AST, and post-execution context to std out

`cd scorch-interpeter ; cargo r --release dump`

to dump the token output, AST, and post-execution context to std out

`cd scorch-interpeter ; chmod +x scripts/sterr_dump.sh ; ./scripts/sterr_dump.sh`
