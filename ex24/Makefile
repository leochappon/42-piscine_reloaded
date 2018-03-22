# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: lchappon <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2017/11/07 14:00:28 by lchappon          #+#    #+#              #
#    Updated: 2017/11/07 14:59:04 by lchappon         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a

SOURCES = srcs/ft_putchar.c srcs/ft_putstr.c srcs/ft_strcmp.c \
	  srcs/ft_strlen.c srcs/ft_swap.c

HEADER = includes/

FLAGS = -Wall -Wextra -Werror

OPTIONS = -c -I $(HEADER)

OBJECTS = ft_putchar.o ft_putstr.o ft_strcmp.o ft_strlen.o ft_swap.o

all: $(NAME)

$(NAME) :
	gcc $(FLAGS) $(OPTIONS) $(SOURCES)
	ar rc $(NAME) $(OBJECTS)

clean:
	/bin/rm -rf $(OBJECTS)

fclean: clean
	/bin/rm -rf $(NAME)

re: fclean all
