# 1585094442 add-certificate-to-java-key-store
#java #self-signed #cert #keystore

```bash
keytool -import -trustcacerts -alias <alias name> -keystore /Library/Java/JavaVirtualMachines/jdk1.8.0_231.jdk/Contents/Home/jre/lib/security/cacerts -file <certificate as pem>
```

## Links
- [1585094553-get-conjur-self-signed-certificate.md](1585094553-get-conjur-self-signed-certificate.md)
