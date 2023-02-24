### 总楼栋-弹出（集合详情）

##### 简要描述:

- 总楼栋-弹出（集合详情）接口

##### 请求URL:

- api/building/getzldtcdetail

##### 请求方式

- GET

##### 参数

``` javascript
// 前端：params， 后端注解：@RequestParam
{
    id: 1     // 主键
}
```

##### 返回示例

``` javascript
{
    code: 200,
    message: '请求成功',
    data: {
        jznd: '2005年',         // 建筑年代 string
        jzjg: '钢结构',         // 建筑结构 string
        zdmj: 538.2,            // 占地面积 float
        jzmj: 883.2,            // 建筑面积 float
        symj: 752.2,            // 使用面积 float
        jsymj: 832.2,           // 净使用面积 float
        dsdx: '2/0',            // 地上/地下 string
        fjs: 22,                // 房间数 int
        fjmj: 526.23,           // 房间面积 float
        zcsl: 0,                // 资产数量 int
        zcjz: 0,                // 资产价值 float
        xzry: 19,               // 行政人员 int
        cb: 0,                  // 超标 int
        dwqkList: [             // 单位情况 array
            {
                dwmc: '人事处', // 单位名称 string
                fjsl: 300,      // 房间数量 int
                fjmj: 242.33    // 房间面积 float
            }
        ],
        flqkList: [             // 分类情况 array
            {
                flmc: '会堂',   // 分类名称 string
                fjsl: 300,      // 房间数量 int
                fjmj: 242.33    // 房间面积 float
            }
        ],
        fdwfltj: [              // 分单位分类统计
            {
                dwmc: '国资处',  // 单位名称 string
                flmc: '会堂',   // 分类名称 string
                fjsl: 300,      // 房间数量 int
                fjmj: 242.33    // 房间面积 float
            }
        ],
        lcpmt: [                // 楼层平面图 array
            {
                img: 'https://dd' // 平面图地址, string
                level: 1          // 楼层 int
            }
        ],
        ldzcqk: [                 // 楼栋资产情况 array
            {
                zcmc: '通用设备',  // 资产名称 string
                tjs: 10,          // 台件数 int
                zje: 0            // 总金额 float
            }
        ],
        mcbdjl: [                   // 名称变动记录
            {
                time: '2021-10-10',                                             // 变动时间
                content: '后勤楼-->西品二',                                      // 内容 string
                desc: '根据学校2022年10月10日会议决定，特将后勤楼修改为西品二'      // 变动描述 string
            }
        ]
    }
}
```