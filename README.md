# API

## Aim:

To create an API to print HELLO WORLD.

## Algorithm:

1.Open Spring Initialzr.
2.Save the zip file.
3.Open an IDE like IntelliJ,Oracle etc.
4.Open the folder in the IDE.
5.Create Components.
6.Connect the database with the SpringBoot.

## Program:
```
package com.hs.you;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;
@SpringBootApplication
@RestController
class YouApplicationTests {
	public static void main(String[] args){SpringApplication.run(YouApplicationTests.class,args);}
	@GetMapping("/")
	public String Hello()
	{
		return "Hello World!";
	}
}

```
## Output:
![image](https://github.com/SaiDarshan2003/API/assets/94692595/50e44748-bef8-4d01-90cb-44cdef94cf2d)

## Result:

Thus we have successfully created an API to print HELLO WORLD.
