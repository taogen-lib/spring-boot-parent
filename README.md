# spring-boot-parent

Add the parent

```xml
<parent>
	<groupId>com.github.taogen-lib</groupId>
	<artifactId>spring-boot-parent</artifactId>
    <!-- -SNAPSHOT equals master-SNAPSHOT, main-SNAPSHOT for SNAPSHOT of the main branch-->
	<version>main-SNAPSHOT</version>
</parent>
```

Add the [JitPack](https://jitpack.io/#taogen-lib/spring-boot-parent) repository to your build file

```xml
<repositories>
	<repository>
		<id>jitpack.io</id>
		<url>https://jitpack.io</url>
	</repository>
</repositories>
```
## Check for updated dependencies in repository

```shell
# Display new versions
mvn versions:display-dependency-updates
mvn versions:display-plugin-updates
# Update dependency versions from properties
mvn versions:update-properties
# Update the parent version
mvn versions:update-parent 
```
