# 四十九自用的 subconverter 模板

作者地址： [subconverter](https://github.com/tindy2013/subconverter)

基本无测速 [nine-clash-rule-base](./config/nine-clash-rule-base.ini)

## 使用文档

sub 后端

```https://suc.guguge.ga/sub?```

输出 clash 配置

```target=clash```

emoji 开启

```emoji=true```

udp 开启

```udp=true```

节点重新排序

```sort=true```

开启跳过节点证书验证

```scv=true```

clash 新名称

```new_name=true```

配置模板输入 url 编码

```config=```

机场链接输入 url 编码

```url=```

**url 编码地址**

[Encode and decode strings | SukkaLab (skk.moe)](https://lab.skk.moe/encode)

## 栗子

```
https://suc.guguge.ga/sub?target=clash&target=clash&emoji=true&udp=true&sort=true&scv=true&new_name=true&config=https%3A%2F%2Fraw.githubusercontent.com%2FNine499%2Fnine-clash-rule%2Fmaster%2Fconfig%2Fnine-clash-rule-base.ini&url=啊哈哈
```

在本例，将机场链接替换 啊哈哈 就可使用。
