JSHint and JSCS will warn you about important issues regarding you Javascript Code.  
Install it via npm and use it from the command line or from vim.


install

    npm install jshint jscs -g

use

    jshint test.js
    jscs test.js

vim shortcut - (Leader+r)

    :noremap <leader>r :! jshint %<CR>:! jscs % -x<CR>
