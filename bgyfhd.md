### 办公用房核定

##### 简要描述:

- 办公用房核定接口

##### 请求URL:

- api/datashow/getbgyfhd

##### 请求方式

- GET

##### 参数

- 略

##### 返回示例

``` javascript
{
    code: 200,
    message: '请求成功',
    data: {
        cbrs: 18,
        zcjys: 10,
        zc: 10,
        fc: 10,
        kjjys: 10
    }
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| cbrs | int | 超标人数 |
| zcjys | int | 正处级以上 |
| zc | int | 正处 |
| fc | int | 副处 |
| kjjys | int | 科级及以上 |