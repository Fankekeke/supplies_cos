### 基于SpringBoot + Vue的物资管理系统.

资产盘点系统、供应链协同平台、库存管控、物资申领流程、数字化仓储管理、物料生命周期

##### 基础档案与分类体系
###### 商户/物资类别： 统一维护物资分类标准与供应商档案，为后续采购与出入库提供规范的数据底座。

###### 套餐管理： 组合常用物资形成标准套餐，支持一键式批量申领，极大提升了办公或生产物资的下发效率。

##### 需求申请与审批流转
###### 制定申请物品： 员工根据实际需求在线提交物资申领单，支持多物品组合申请，开启业务流转首环。

###### 申请记录/审批： 管理员实时审核申领请求，记录从发起、审核到驳回的全过程，确保物资发放有据可依。

##### 采购计划与供应链协同
###### 制定采购计划： 基于审批通过的申领需求与当前库存水位，由管理员科学制定采购清单，优化资金利用。

###### 采购员采购： 采购人员根据执行计划对接供应商，实时跟进到货进度，确保物资供应链条的及时性。

##### 仓储存取与动态追踪
###### 库房管理/入库记录： 规范物资验收入库流程，详细记录到货批次与存储位置，确保入库账实相符。

###### 出库记录/明细： 根据审批结果办理实物出库，自动关联申领人与用途，实现物资去向的精准追踪。

###### 出入库物品明细： 汇总每一笔物资流动的动态详情，为资产盘点与财务对账提供颗粒度极细的原始凭证。

##### 运营预警与决策分析
###### 报表统计： 自动聚合申领频率、消耗趋势及库存周转率，通过可视化数据报表，辅助管理层科学运营。

#### 安装环境

JAVA 环境 

Node.js环境 [https://nodejs.org/en/] 选择14.17

Yarn 打开cmd， 输入npm install -g yarn !!!必须安装完毕nodejs

Mysql 数据库 [https://blog.csdn.net/qq_40303031/article/details/88935262] 一定要把账户和密码记住

redis

Idea 编译器 [https://blog.csdn.net/weixin_44505194/article/details/104452880]

WebStorm OR VScode 编译器 [https://www.jianshu.com/p/d63b5bae9dff]

#### 采用技术及功能

后端：SpringBoot、MybatisPlus、MySQL、Redis、
前端：Vue、Apex、Antd、Axios
报表：Spread.js

平台前端：vue(框架) + vuex(全局缓存) + rue-router(路由) + axios(请求插件) + apex(图表)  + antd-ui(ui组件)

平台后台：springboot(框架) + redis(缓存中间件) + shiro(权限中间件) + mybatisplus(orm) + restful风格接口 + mysql(数据库)

开发环境：windows10 or windows7 ， vscode or webstorm ， idea + lambok

商户管理，套餐管理，申请记录，库房管理，入库记录，出库记录，采购计划，报表统计，物资类别，出入库物品明细

制定申请物品->管理员审批制定采购计划->采购员采购->入库->出库


#### 前台启动方式
安装所需文件 yarn install 
运行 yarn run dev

#### 默认后台账户密码
[管理员]
admin
1234qwer

[采购员]
caigou
1234qwer

[用户]
lisi
1234qwer
#### 项目截图

|  |  |
|---------------------|---------------------|
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907138762.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907317483.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907125711.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907304037.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907113125.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907268190.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907098318.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907247498.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907608952.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907224697.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907599256.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907209784.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907578751.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907187396.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907368072.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907170241.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907351735.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703907151020.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/work/936e9baf53eb9a217af4f89c616dc19.png) |

#### 演示视频

暂无

#### 获取方式

Email: fan1ke2ke@gmail.com

WeChat: `Storm_Berserker`

`附带部署与讲解服务，因为要恰饭资源非免费，伸手党勿扰，谢谢理解😭`

> 1.项目纯原创，不做二手贩子 2.一次购买终身有效 3.项目讲解持续到答辩结束 4.非常负责的答辩指导 5.**黑奴价格**

> 项目部署调试不好包退！功能逻辑没讲明白包退！

#### 其它资源

[2025年-答辩顺利通过-客户评价🍜](https://berserker287.github.io/2025/06/18/2025%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2024年-答辩顺利通过-客户评价👻](https://berserker287.github.io/2024/06/06/2024%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2023年-答辩顺利通过-客户评价🐢](https://berserker287.github.io/2023/06/14/2023%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2022年-答辩通过率100%-客户评价🐣](https://berserker287.github.io/2022/05/25/%E9%A1%B9%E7%9B%AE%E4%BA%A4%E6%98%93%E8%AE%B0%E5%BD%95/)

[毕业答辩导师提问的高频问题](https://berserker287.github.io/2023/06/13/%E6%AF%95%E4%B8%9A%E7%AD%94%E8%BE%A9%E5%AF%BC%E5%B8%88%E6%8F%90%E9%97%AE%E7%9A%84%E9%AB%98%E9%A2%91%E9%97%AE%E9%A2%98/)

[50个高频答辩问题-技术篇](https://berserker287.github.io/2023/06/13/50%E4%B8%AA%E9%AB%98%E9%A2%91%E7%AD%94%E8%BE%A9%E9%97%AE%E9%A2%98-%E6%8A%80%E6%9C%AF%E7%AF%87/)

[计算机毕设答辩时都会问到哪些问题？](https://www.zhihu.com/question/31020988)

[计算机专业毕业答辩小tips](https://zhuanlan.zhihu.com/p/145911029)

#### 接JAVAWEB毕设，纯原创，价格公道，诚信第一

`网站建设、小程序、H5、APP、各种系统 选题+开题报告+任务书+程序定制+安装调试+项目讲解+论文+答辩PPT`

More info: [悲伤的橘子树](https://berserker287.github.io/)

<p><img align="center" src="https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/%E5%90%88%E4%BD%9C%E7%89%A9%E6%96%99%E6%A0%B7%E5%BC%8F%20(3).png" alt="fankekeke" /></p>
