# **Libft**
This project was graded <strong style="color: green">125/100</strong>.

## **About**
> This project is all about writing down a useful set of functions to later on be used on future projects. All the code was implemented by me and based on the version of the subject available from the moment of the kickoff here in Porto (2<sup>nd</sup> November).

&#128196;
&#9989;

## **Implementation**
<table>
	<thead>
		<tr>
			<th>Project Part</th>
			<th>Function Name</th>
			<th>Implemented</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td rowspan=23><strong>Mandatory (I)</strong></td>
			<td>ft_atoi</td>
			<td>&#9989;</td>
		</tr>
		<tr>
			<td>ft_bzero<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_calloc<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_isalnum<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_isalpha<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_isascii<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_isdigit<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_isprint<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_memchr<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_memcmp<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_memcpy<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_memmove<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_memset<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_strchr<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_strdup<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_strlcat<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_strlcpy<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_strlen<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_strncmp<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_strnstr<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_strrchr<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_tolower<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_toupper<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td rowspan=11><strong>Mandatory (II)</strong></td>
			<td>ft_itoa<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_putchar_fd<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_putendl_fd<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_putnbr_fd<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_putstr_fd<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_split<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_striteri<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_strjoin<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_strmapi<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_strtrim<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_substr<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td rowspan=9><strong>Bonus Part</strong></td>
			<td>ft_lstadd_back<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_lstadd_front<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_lstclear<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_lstdelone<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_lstiter<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_lstlast<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_lstmap<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_lstnew<td>
			<td>&#9989;<td>
		</tr>
		<tr>
			<td>ft_lstsize<td>
			<td>&#9989;<td>
		</tr>
	</tbody>
</table>


## **Compilation**
To compile the library you can either run `make` or `make bonus` in the terminal. The rule `make` will only compile the mandatory part of this work, while the `make bonus` rule will compile both the mandatory and the bonus part together.

Both rules generate a `libft.a` file, which is zipped version of all the object files. Imagine you have a `main.c` file and you want to use your library in it. You can compile it by running the following command:

```sh
$ cc -Wall -Wextra -Werror main.c -lft -L (REPLACE BY PATH TO libft.a) -I (REPLACE BY PATH TO libft.h)
```

## **Testing**

This project was tested using the [libft-unit-tester](https://github.com/alelievr/libft-unit-test) and manual revision only.

