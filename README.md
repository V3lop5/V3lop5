### Hi there 👋

<h3>
  
```kotlin
package about.v3;

class Paul : Male, Developer {

  override val languages = listOf("Kotlin", "RPGLE", "CLLE", "SQL", "Java", "C++", "C#")
  
  override val databases = listOf("db2", "PostgreSQL")
  
}

fun main() {
  val me = Paul()
  me.sayHi()
}
```

</h3>
