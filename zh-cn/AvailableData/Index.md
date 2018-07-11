# 介绍

GameMaker Language 的功能可用性数据。

这个数据将用于 GML Support 插件。

这里的数据可能不准确，所以本仓库同样支持贡献数据。

## 项目地址

[https://github.com/LiarOnce/gml-support-available-data](https://github.com/LiarOnce/gml-support-available-data)

## 支持文件

|      | Full | Simple |
| :--: | :--: | :----: |
| JSON |  ✓   |   ✓    |
| XML  |  ✓   |   ✗    |
| YAML |  ✓   |   ✓    |

## 调用地址

|                  |                             Full                             |                            Simple                            |
| :--------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|       JSON       | [https://raw.githubusercontent.com/LiarOnce/gml-support-available-data/master/full/data.json](https://raw.githubusercontent.com/LiarOnce/gml-support-available-data/master/full/data.json) | [https://raw.githubusercontent.com/LiarOnce/gml-support-available-data/master/simple/data.simple.json](https://raw.githubusercontent.com/LiarOnce/gml-support-available-data/master/simple/data.simple.json) |
| JSON(Compressed) | [https://raw.githubusercontent.com/LiarOnce/gml-support-available-data/master/full/data.compressed.json](https://raw.githubusercontent.com/LiarOnce/gml-support-available-data/master/full/data.compressed.json) |                       (not available)                        |
|       XML        | [https://raw.githubusercontent.com/LiarOnce/gml-support-available-data/master/full/data.xml](https://raw.githubusercontent.com/LiarOnce/gml-support-available-data/master/full/data.xml) |                       (not available)                        |
| XML(Compressed)  | [https://raw.githubusercontent.com/LiarOnce/gml-support-available-data/master/full/data.compressed.xml](https://raw.githubusercontent.com/LiarOnce/gml-support-available-data/master/full/data.compressed.xml) |                       (not available)                        |
|       YAML       | [https://raw.githubusercontent.com/LiarOnce/gml-support-available-data/master/full/data.yaml](https://raw.githubusercontent.com/LiarOnce/gml-support-available-data/master/full/data.yaml) | [https://raw.githubusercontent.com/LiarOnce/gml-support-available-data/master/simple/data.simple.yaml](https://raw.githubusercontent.com/LiarOnce/gml-support-available-data/master/simple/data.simple.yaml) |

## 函数 / 变量 / 常量 标识

| 标识 |          含义           |
| :--: | :---------------------: |
|  y   |          允许           |
|  yd  |      允许但不建议       |
|  n   |         不允许          |
|  n1  | 在新的 GMS 版本中不允许 |
|  f   |          函数           |
|  c   |          常量           |
|  v   |          变量           |

## 版本标识

| 标识 (Identification) |              含义              |
| :-------------------: | :----------------------------: |
|         type          | 数据类型（函数 / 常量 / 变量） |
|         gm81          |         GameMaker 8.1          |
|          gms          |        GameMaker:Studio        |
|         gms2          |       GameMaker Studio 2       |