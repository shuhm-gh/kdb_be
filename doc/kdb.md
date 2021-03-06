李同学, 我就近期开发工作情况和软件开发一般情况作一些说明, 以期同步一下必要信息.

### 5月22日以来工作说明

* 数据模型设计
* 接口设计
* 系统概要设计

* 打通前端后端通信
  * [登录]功能后端实现(不完善, 具体开发属于用户系统模块)
  * [登录]功能前端实现(不完善, 没有错误提示等标准功能)
  > 以打通前后端通信为目标, 主要解决页面数据(用户填写)如何到前端代码, 前端代码如何与后端通信的问题

* 竞品页面
  * 下拉列表, **实时增量搜索**, 支持中文, 对易用性很重要, 比如200个店铺, 每个店铺下有500种图书, 实际使用时如何操作?
  * [已选]动态下拉列表(已替换为动态标签)
  * [已选]**动态标签**, 可增可删, 主要是排版布局, 页面关注对象是宫格图, 以什么方式, 布置在页面什么位置?
  * **动态宫格**, 根据[已选]个数绘制曲线图, 主要解决待绘制的曲线图个数不确定的时候, 页面展示效果, 尤其是太多的时候, 如客户同时比较50个竞品, 如何展示?
  * 鼠标悬停显示数值

  > 竞品页面开发完成, 前端开发主体工作就差不太多了, 另外的页面相对简单, 所用控件也基本都在竞品页面使用过了

* 添加[持续发布]
  > 持续发布是软件工程中的一种策略, 目的是客户所见, 就是开发人员所开发, 即写完代码后, 不需要其他中间环节, 客户就可以看到最新产品

### 软件开发阶段说明
* 需求
  > 需求沟通, 反复沟通, 可以会先出原型效果, 甚至先出demo, 之后再沟通
* 项目计划
  > 需求确认后, 进行粗略整体设计, 以估算为目标
  > 进行项目计划, 确定时间节点

> 从这个点开始, 乙方与甲方会有定期或不定期的沟通, 反馈, 汇报, 乙方开始开发工作
* 整体设计
  > 其中会包括技术选型, 技术点验证等环节
  > 可能会先出demo, 让甲方确认设计

* 数据模型设计
* 概要设计
* 接口设计
* 详细设计

> 注, 以上步骤, 甲方都是感受不到的, 不会体现在功能上

* 编码
  * 框架开发
  * 基础公用模块开发
  > 注, 以上开发工作, 甲方也是感受不到的, 不会体现在功能上
  
  * 功能开发
  > 从这里开始, 且具备[持续发布]能力, 才可能让甲方以较短迟延, 感受到功能上的变化

* 调优
* 测试
* 交付
* 运维