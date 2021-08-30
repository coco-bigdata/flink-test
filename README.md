# flink-test
flink-test

```shell
nc -l 9000
hello
hello hello hello

flink run -c com.github.zhangchunsheng.SocketTextStreamWordCount ~/dev/github/flink-test/target/original-flink-test-1.0-SNAPSHOT.jar 127.0.0.1 9000
```