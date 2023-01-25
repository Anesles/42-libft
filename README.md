# **libft (Cursus from 42 Porto)**
## **Grade: 125/100**
---
### **Summary:**

In this project I had to develop my own library full of functions that I will use during my 42 Cursus (so as I go through it, I'll update it with more functions).

#### **Installing and running the project:**
* Clone this repository.
```
git clone git@github.com:Anesles/42-libft.git
```
* Create a test file with a main that uses functions from libft.
``` C
#include "libft.h"

int main(void)
{
	char *str = "Test";

	printf("Str length = %d\n", ft_strlen(str));
}
```
* Compile and run.
```
cc -Wall -Wextra -Werror name_of_file.c libft.a
./a.out
```
---
### **Makefile targets**
* `make` or `make all` - Compiles the program.
* `make clean` - Cleans all object files.
* `make fclean` - Cleans all object files, _client_ and _server_.
## Disclaimer
> At [42School](https://en.wikipedia.org/wiki/42_(school)), almost every project must be written in accordance to the [Norm](./extras/en_norm.pdf), the schools' coding standard. As a result, the implementation of certain parts may appear strange and for sure had room for improvement. #42-libft
