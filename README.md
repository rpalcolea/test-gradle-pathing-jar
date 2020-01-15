# test-gradle-pathing-jar

Execute `./gradlew -g /tmp/really/really/really/long/prefix/for/each/dependency/j3awDqlz1NftNYlWdFtbR0jLlOE2kYrs8UGkijDPKLsJu8AUms9WpXAJUMMMhTijn3MA5LixQRb66Hm6c6ZM87DSxwANfxDrRQNz/test-gradle-path-jar run -s`

You will get

```
aused by: java.io.IOException: Cannot run program "/Users/rperezalcolea/.sdkman/candidates/java/8.0.181-zulu/bin/java" (in directory "/Users/rperezalcolea/Projects/github/rpalcolea/test-gradle-path-jar"): error=7, Argument list too long
        at net.rubygrapefruit.platform.internal.DefaultProcessLauncher.start(DefaultProcessLauncher.java:25)
        ... 7 more
Caused by: java.io.IOException: error=7, Argument list too long
        ... 8 more
```
