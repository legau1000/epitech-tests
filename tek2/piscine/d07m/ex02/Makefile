BINPATH ?= ..
NAME ?= test02
BIN ?= $(BINPATH)/$(NAME)
EX ?= ex02
TESTSRCS ?= *.cpp
EXSRCS ?= ../srcs/$(EX)/*.cpp
INCLUDES ?= -I../srcs/$(EX)/ -I/tmp/epitech-tests/$(EX)/
CXXFLAGS ?= -W -Wall -Wextra -Werror
LDFLAGS ?= -W -Wall -Wextra -Werror

all: $(NAME)

$(NAME):
	g++ -o $(BIN) $(TESTSRCS) $(EXSRCS) $(INCLUDES) $(LDFLAGS)

fclean:
	rm $(BIN)

re: fclean all

.PHONY: all fclean re
