# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: lchappon <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2017/11/07 17:34:11 by lchappon          #+#    #+#              #
#    Updated: 2017/11/08 12:38:20 by lchappon         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = ft_display_file

SRC = display_file.c

all: $(NAME)

$(NAME) :
	gcc -c -Wall -Wextra -Werror $(SRC)
	gcc -o $(NAME) display_file.o

clean:
	/bin/rm -f display_file.o

fclean: clean
	/bin/rm -f $(NAME)

re: fclean all
