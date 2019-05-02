# Lowercase a String

## C++

```c++
#include <algorithm>
#include <string>

int main()
{
    std::string myString = "THIS IS A STRING";
    transform(myString.begin(), myString.end(), myString.begin(), ::tolower); // Passed by reference
}
```

## Go

```go
package main

import "strings"

func main() {
	myString := "THIS IS A STRING"
	myLowerString := strings.ToLower(myString) // Passed by value
}
```

## Java

```java
public class Main {
    public static void main(String[] args) {
        String myString = "This is a STRING";
        String myLowerString = myString.toLowerCase(); // Passed by value
    }
}


```


## JavaScript & TypeScript

```JavaScript
let myString = "THIS IS A STRING";
let myLowerString = myString.toLowerCase(); // Passed by value
```


## Python

```python
my_str = "THIS IS A STRING"
my_lower_str = my_str.lower() # Passed by value
```

## Ruby

```ruby
my_string = "THIS IS A STRING"
my_lower_string = my_string.downcase # Passed by value
my_string.downcase! # Passed by reference
```