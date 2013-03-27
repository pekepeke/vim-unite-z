# unite-z

z.zsh source for unite.vim

Version: 0.0.1  
Author : pekepeke <pekepekesamurai+vim@gmail.com>  
License: MIT <http://opensource.org/licenses/MIT>  
	Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:  
	The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.  
	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.  

## INTRODUCTION

*unite-z* is a Vim plugin to provide unite.vim source
to select directory on z.zsh history file.

Requirement:
	- z.zsh (Recommend latest version at https://github.com/rupa/z)
	- |unite.vim| (Recommend latest version at https://github.com/Shougo/unite.vim)

Latest version:
	https://github.com/pekepeke/vim-unite-z

### CUSTOMIZE
#### g:unite_z_path

	Set The datafile path of z.zsh.(default=$HOME/.z)

### USAGE

To select directory, execute |:Unite| with argument of z


	:Unite z


