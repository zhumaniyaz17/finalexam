How many processes will be created by this code?
```C
#include <unistd.h>

int main(){
    fork();
    fork();
    fork();
}
```
* 1
* 4
* **8**
* 6
