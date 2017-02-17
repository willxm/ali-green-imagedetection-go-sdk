# sdk supported
* aliyun.green (version: 2016-10-18)

## usage
```
var cfg green.Config
cfg.AccessKeyId = "your AccessKeyId"
cfg.SecretKey = "your SecretKey"
cfg.RegionId = "cn-hangzhou"

cli := green.New(cfg)
idr, err := cli.ImageDetection(imageUrls)
```
