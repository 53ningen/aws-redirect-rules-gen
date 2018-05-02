aws management console redirect rules for S3 static webhosting
===

see: [https://53ningen.com/chrome-address-bar-aws/](https://53ningen.com/chrome-address-bar-aws/)

## usage

```
# console
./gen > /tmp/generated.xml

# cli
./json-gen > ./config.json
aws s3api put-bucket-website --bucket redirect.53ningen.com --website-configuration file://config.json
```

## LICENSE

MIT
