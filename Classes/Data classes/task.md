## Data classes

Learn about [classes](http://kotlinlang.org/docs/reference/classes.html),
[properties](http://kotlinlang.org/docs/reference/properties.html)
and [data classes](https://kotlinlang.org/docs/reference/data-classes.html)
and then rewrite the following Java code in Kotlin:

```java
public class Person {
    private final String name;
    private final int age;

    public Person(String name, int age) {
        this.name = name;
        this.age = age;
    }

    public String getName() {
        return name;
    }

    public int getAge() {
        return age;
    }
}
```

After add the `data` modifier to the resulting class.
This will make the compiler generate some useful methods for this class: `equals`/`hashCode`, `toString`, and a few others.
