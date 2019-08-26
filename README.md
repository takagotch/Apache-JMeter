### apache-jmeter
---
https://github.com/apache/jmeter

http://jmeter.apache.org/

```java
systemProp.http.proxyHost=proxy.example.invalid
systemProp.http.proxyPort=8080
systemProp.http.proxyUser=your_user_name
systemProp.http.proxyPassword=your_password
systemProp.https.proxyHost=proxy.example.invalid
systemProp.https.proxyPort=8080
systemProp.https.proxyUser=your_user_name
systemProp.http.proxyPassword=your_password

skip.bug52310=true
skip.bug60607=true
skip.batchtest_Http4ImplPreemptiveBasicAuth=true
skip.batchtest_SlowCharsFeature=true
skip.batchtest_TestKeepAlive=true
skip.batchtest_ResponseDecompression=true
skip.test_http=true
skip.test_TestDNSCacheManager.testWithCustomResolverAndServer=true
```

```sh
./gradlew build
./gradlew check [-Djava.awt.headless=true]
```

```
```


