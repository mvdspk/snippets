# when creating JSON pojos

use below

## Pojo has member, but json file doesnt have
```java
import org.codehaus.jackson.annotate.JsonIgnoreProperties;
```
```java
@JsonIgnoreProperties(ignoreUnknown = true)
```

## Null value

```java
import org.codehaus.jackson.map.annotate.JsonSerialize;
```
```java
@JsonSerialize(include = JsonSerialize.Inclusion.NON_NULL)
```

[generate Getter setter during run time](https://github.com/mvdspk/snippets/blob/main/java/index.md#generate-getter-setter-during-run-time)
