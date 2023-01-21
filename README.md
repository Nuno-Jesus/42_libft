# **Libft**
This project was graded <strong>125/100</strong>.


## 📒 **About**
This project is all about writing down a useful set of functions to later on be used on future projects. All the code was implemented by me and based on the version of the subject available from the moment of the kickoff here in Porto, <strong>2<sup>nd</sup> November 2022</strong>.

## 🚨 **Disclaimer**
At 42, the C projects are built following a bunch of rules that enforce good coding style. Some of them are:

	- No for, do while, switch, case or goto are allowed
	- No more than 25 lines per function and 5 functions per file
	- No assigns and declarations in the same line (unless static)
	- No more than 5 variables in 1 function
	... 

## 🔧 **Implementation**
<table>
	<thead>
		<tr>
			<th>Part / Total Functions</th>
			<th>Function Name</th>
			<th>Implemented</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td rowspan=23><strong>Mandatory (I) / 23</strong></td>
			<td>ft_atoi</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_bzero</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_calloc</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_isalnum</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_isalpha</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_isascii</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_isdigit</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_isprint</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_memchr</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_memcmp</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_memcpy</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_memmove</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_memset</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_strchr</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_strdup</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_strlcat</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_strlcpy</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_strlen</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_strncmp</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_strnstr</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_strrchr</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_tolower</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_toupper</td>
			<td>✅</td>
		</tr>
		<tr>
			<td rowspan=11><strong>Mandatory (II) / 11</strong></td>
			<td>ft_itoa</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_putchar_fd</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_putendl_fd</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_putnbr_fd</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_putstr_fd</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_split</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_striteri</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_strjoin</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_strmapi</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_strtrim</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_substr</td>
			<td>✅</td>
		</tr>
		<tr>
			<td rowspan=9><strong>Bonus Part / 9</strong></td>
			<td>ft_lstadd_back</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_lstadd_front</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_lstclear</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_lstdelone</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_lstiter</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_lstlast</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_lstmap</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_lstnew</td>
			<td>✅</td>
		</tr>
		<tr>
			<td>ft_lstsize</td>
			<td>✅</td>
		</tr>
	</tbody>
</table>



## 📦 **Compilation**
To compile the library you can either run `make` or `make bonus` in the terminal. The rule `make` will only compile the mandatory part of this work, while the `make bonus` rule will compile both the mandatory and the bonus part together.

Both rules generate a `libft.a` file, which is zipped version of all the object files. Imagine you have a `main.c` file and you want to use your library in it. You can compile it by running the following command:

```sh
$ cc -Wall -Wextra -Werror main.c -lft -L (REPLACE BY PATH TO libft.a) -I (REPLACE BY PATH TO libft.h)
```


## 💫 **Testing**

This project was tested using the [libft-unit-tester](https://github.com/alelievr/libft-unit-test) and manual revision only.


## 📞 **Contact me**

Feel free to ask me any questions through Slack (**ncarvalh**).

