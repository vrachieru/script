# script

Treat compiled languages such as C or Java as scripts.

Here's a simple example:
```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello from java!");
    }
}
```

Run it by typing:
```bash
$ script Hello.java
Hello from java!
```


Or, call it from the shebang!
```java
#!/usr/bin/script

public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello from java!");
    }
}
```

```bash
$ ./Hello.java
Hello from java!
```

The installation consits only in dropping the `script` bin into your `/usr/bin/`
