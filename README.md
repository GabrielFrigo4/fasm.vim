# Flat Assembler support for vim

 Has syntax, compiler, indent support.

## Set Flat Assembler syntax by default for `*.asm` files

 Add following to your `.vimrc`:

 ```
 autocmd BufReadPre *.asm let g:asmsyntax = "fasm"
 ```

## Improvements to the original works:

 * All files are useable on Linux
 * Update to modern CPUs (AVX-512 registers)

## Based on:

### syntax:

 1. https://github.com/RIscRIpt/vim-fasm-syntax
 2. https://github.com/fedorenchik/fasm.vim
 3. https://github.com/vim/vim/blob/master/runtime/syntax/fasm.vim
 4. https://github.com/vim/vim/blob/master/runtime/syntax/nasm.vim

### compiler:

 1. https://www.vim.org/scripts/script.php?script_id=1073

### indent:

 1. https://github.com/vim-scripts/fasm.vim
