CC = cc
FLAGS = -Wall -Wextra -Werror
DEPS = .
RM = rm -f
AR = ar -rc

TARGET = 	ft_atoi.o ft_bzero.o ft_calloc.o ft_isalnum.o ft_isalpha.o ft_isascii.o ft_isdigit.o \
			ft_isprint.o ft_itoa.o ft_memchr.o ft_memcmp.o ft_memcpy.o ft_memmove.o ft_memset.o \
			ft_putchar_fd.o ft_putendl_fd.o ft_putnbr_fd.o ft_putstr_fd.o ft_split.o ft_strchr.o \
			ft_strdup.o ft_striteri.o ft_strjoin.o ft_strlcat.o ft_strlcpy.o ft_strlen.o ft_strmapi.o \
			ft_strncmp.o ft_strnstr.o ft_strrchr.o ft_strtrim.o ft_substr.o ft_tolower.o ft_toupper.o

BONUS_TARGET = 	ft_lstadd_back.o ft_lstadd_front.o ft_lstclear.o \
			ft_lstdelone.o ft_lstiter.o ft_lstlast.o \
			ft_lstmap.o ft_lstnew.o ft_lstsize.o

NAME = libft.a

%.o : %.c 
	$(CC) $(FLAGS) -c $< -o $@ -I $(DEPS)

all: $(NAME)

bonus: $(TARGET) $(BONUS_TARGET)
	$(AR) $(NAME) $^

$(NAME): $(TARGET)
	$(AR) $(NAME) $^

clean:
	$(RM) $(TARGET) $(BONUS_TARGET)

fclean: clean
	$(RM) $(NAME) $(BONUS_TARGET)

re: fclean all

rebonus: fclean bonus

so:
	$(CC) -nostartfiles -fPIC $(FLAGS) $(TARGET) $(BONUS_TARGET)
	cc -nostartfiles -shared -o libft.so $(TARGET) $(BONUS_TARGET)