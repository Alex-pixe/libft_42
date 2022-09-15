# libft
project for ecole 42

for this project you need to rewrite some libc functions, you can see them in the root of the repository  
and for the bonus part you need to write functions to work with linked lists.  
  
* You can see the full assignment here [subject](https://github.com/cbridget42/libft_42/blob/main/subject/en.subject.pdf)
* Coding style: [norminette](https://github.com/cbridget42/libft_42/blob/main/subject/en.norm.pdf)
  
### Usage:
* first you need to download the repository and compile the code! To do this, run:
	```bash
	git clone git@github.com:cbridget42/libft_42.git
	cd libft_42
	make
	make bonus //compile with bonus
	```
* then you will have a libft.a file.
	+ to use it you need to add libft.h header to your project.
	+ compile your project with libft.a and with flag -I ./path to libft_42
* also you can:
	```bash
	make clean //remove objects files
	make fclean //remove objects files and libft.a
	```
