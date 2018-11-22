\[\[\_TOC\_\]\]

\# 资源列表

\|资源编码	\|资源名称\|资源说明\|

\|----\|----\|----\|

\|\[qz\_pr\_pe\]\(\#个人不动产信息\)\|个人不动产信息\|由泉州不动产登记中心提供,包含个人不动产详细信息\|





\# 不动产信息

\#\# 业务数据说明

\|参数	\|含义\|说明\|

\|----\|----\|----\|

\|location \|房屋坐落 \|丰泽区东海大街与滨海街交汇处西南侧东海湾·御花园x组团x栋xxxx \|

\|buildingid \|楼栋号 \|x组团x栋 \|

\|purpose \|规划用途\|住宅 \|

\|houseid \|房屋号 \|22 \|

\|structure \|房屋结构 \|钢筋砼 \|

\|totalfloor \|总楼层 \|40 \|

\|onfloor \|所在楼层 \|xx层 \|

\|iscongeal \|是否查封 \|否 / 是 \|

\|buildarea \|建筑面积 \|80 \|

\|userarea \|套内面积 \|70 \|

\|apportionarea \|公摊面积 \|10 \|

\|housecenterid \|房屋代码 \|33222 \|

\|housetype \|户型  \|两室一厅 \|

\|licenceid \|产权证编号 \|闽\(2018\)泉州市不动产权第0xxxx号 \|

\|ISTRANSACTION \|是否交易中\|否 / 是 \|

\|ismortgate \|是否抵押 \|否 / 是 \|

\|registrationdate \|登记日期 \|20180101 \|

\|personname \|姓名 \|\|

\|idcard \|身份证号 \|\|

\|landnature \|土地性质 \|\|

\|contractecord\|合同备案情况 \|\|

\|handleestatestate\|不动产流程办理状态 \|\|

\|obligeename\|权利人 \|\|

\#\# 案列

\#\#\# 请求

\#\#\# 返回

    {

    	"personname": "王一",

    	"idcard": "22042\*\*\*\*\*\*\*\*\*0379",

    	"Personalpropertydetails": \[{

    		"location ": "丰泽区东海大街与滨海街交汇处西南侧东海湾·御花园x组团x栋xxxx",

    		"buildingid": "x组团x栋" ,

    		"purpose": "住宅",

    		"houseid": "22" ,

            "structure": "钢筋砼",

            "totalfloor": "40",

            "onfloor": "38",

            "iscongeal": "0",

            "buildarea": "80",

            "userarea": "70",

            "apportionarea": "10",

            "housecenterid": "33222",

            "housetype": "两室一厅",

            "licenceid": "闽\(2018\)泉州市不动产权第0xxxx号",

            "ISTRANSACTION": "0",

            "ismortgate": "0",

            "registrationdate": "20180101",

            "landnature":"出让",

            "contractecord":"已备案",

            "handleestatestate":"已申请",

            "obligeename":"王一"

    	}\]

    }

