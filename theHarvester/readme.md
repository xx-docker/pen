# 仓库位置和使用
- registry.cn-hangzhou.aliyuncs.com/xx-pen/theharvester
- docker pull registry.cn-hangzhou.aliyuncs.com/xx-pen/theharvester


## 使用教程

```
docker run -it --rm  \
registry.cn-hangzhou.aliyuncs.com/xx-zhang/pen:theharvester \
python theHarvester.py -d linux.cn -s -c -b baidu --limit 20
```

## 仓库2
```
docker run -it --rm registry.cn-hangzhou.aliyuncs.com/xx-pen/theharvester python theHarvester.py -d baidu.com -s -c -b baidu --limit 20
```