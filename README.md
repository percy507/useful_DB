## 整理常用的数据

### 世界各国和地区名称代码（GB/T2659-2000）

```js
[{
  "name_cn": "中国",
  "name_en": "China",
  "letter_code": "CN",
  "number_code": "156",
  "full_name_cn": "中华人民共和国",
  "full_name_en": "People’s Republic of China"
}]
```

  * http://doc.mbalib.com/view/5c07d3de0ebd4726dfab3d5561bc90f6.html
  * http://project.calis.edu.cn/calis/lhml/biaozhun/9.htm

### 中国-民族

```js
[{
  "code": "01",
  "nation": "汉族"
}]
```

  * http://www.nsfc.gov.cn/publish/portal0/tab560/

### 中国-省市

```js
[{
    "name": "浙江省",
    "adcode": "330000",
    "districts": [{
        "name": "杭州市",
        "adcode": "330100"
    }, {
        "name": "宁波市",
        "adcode": "330200"
    }, {
        "name": "温州市",
        "adcode": "330300"
    }, {
        "name": "嘉兴市",
        "adcode": "330400"
    }, {
        "name": "湖州市",
        "adcode": "330500"
    }, {
        "name": "绍兴市",
        "adcode": "330600"
    }, {
        "name": "金华市",
        "adcode": "330700"
    }, {
        "name": "衢州市",
        "adcode": "330800"
    }, {
        "name": "舟山市",
        "adcode": "330900"
    }, {
        "name": "台州市",
        "adcode": "331000"
    }, {
        "name": "丽水市",
        "adcode": "331100"
    }]
}]
```

### 中国-省市县(区)

```js
{
    "name": "中华人民共和国",
    "adcode": "100000",
    "districts": [{
        "name": "北京市",
        "adcode": "110000",
        "districts": [{
            "name": "北京市市辖区",
            "adcode": "110100",
            "districts": [{
                "name": "东城区",
                "adcode": "110101",
                "districts": null
            }, {
                "name": "西城区",
                "adcode": "110102",
                "districts": null
            }, {
                "name": "朝阳区",
                "adcode": "110105",
                "districts": null
            },
            ...
}
```