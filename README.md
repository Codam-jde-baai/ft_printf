# ft_printf: Custom Printf Implementation

This **ft_printf** project is a utility project developed as my second project at Codam. It involves creating a custom implementation of the standard `printf` function, utilizing my own **Libft** library.

## Project Highlights

- **Integration with Libft**: This project integrates my personal **Libft** library, this is the first time linking the libft library.
  
- **Introduction to `va_list`**: `ft_printf` introduced the use of the `va_list` datatype, which is important for handling variable argument lists in C. This was my first experience using `va_list`, it is a very practical and easy to use datatype.

## The Project

The **ft_printf** project is organized to facilitate easy integration and use in future projects. It includes:

- **Core Functionality**: The main `ft_printf` function is supposed to mimick the real `prinft()` as closely as possible and its intended to be used in my future CODAM projects.
  
- **Format Specifiers**: The function supports a range of format specifiers:
  - `'c'`: Outputs a character using `ft_print_putchar`.
  - `'s'`: Outputs a string using `ft_print_putstr`.
  - `'p'`: Outputs a pointer address using `ft_print_ptr`.
  - `'d'` or `'i'`: Outputs a signed integer using `ft_print_nb`.
  - `'u'`: Outputs an unsigned integer using `ft_print_unb`.
  - `'x'`: Outputs a lowercase hexadecimal using `ft_print_hexl`.
  - `'X'`: Outputs an uppercase hexadecimal using `ft_print_hexu`.
  - `'%'`: Outputs a literal percent sign.

### Challenges

Developing **ft_printf** came with a few small challenges for someone need to programming:
- Implementing and using the `va_list` datatype
- Understanding how pointers are printed
- Converting decimal to hexadecimal 
- Addressing edge cases, such as:
	- `%` signs at the end of the format string
	- no matching input for a flag `%`
	- numeric edges cases.

## Conclusion

**ft_printf** is a project that helped increase my understanding of C programming and extend my **Libft** library. As for future projects I have made printf a part of Libft and not a linked library to `ft_printf`.

Feel free to explore the code and use it as a reference or inspiration for your own projects.