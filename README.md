## 和卖商户后台测试

背景：商户2.0版基础功能验收
环境：windows 10，1366*768，chrome 63.0.3239.132（正式版本） （64 位）

<font face = SimHei color = red>红色，高优先级</font>
<font face = SimHei color = blue>蓝色，低优先级</font>

---

### 整体

** 风格/尺寸：**

1. 整体宽度过大，左侧级联菜单以及主要内容显示区应收窄，网页两遍适度留白，增加有效内容显示条数。（参考在现有基础上缩放到90%效果）
2. 顶部导航条高度过大。
3. 网页遮罩层覆盖滚动条，因为提示信息居中页面显示，导致关闭遮罩时提示信息轻微左移，有抖动感，影响视觉效果。

** 规范/标准 **

1.  提示信息标准不统一，成功信息使用绿色提示，失败信息使用红色提示。
![](https://i.imgur.com/mHjXhVR.png)
2.  引导信息提示，叹号+文案，	且不支持关闭操作（首页）。
![](https://i.imgur.com/U9VBSdT.png)
3. 删除提示
![](https://i.imgur.com/WurPGVg.png)    ![](https://i.imgur.com/gjvbDTp.png)
4. 售后处理提示，去掉对话框标题
![](https://i.imgur.com/Fb5cbyb.png)
---

### 入驻环节

1. 海外身份证不需要校验格式。
2. 点击“确认无误”后完成自动登录，跳转至商户后台首页。

---

### 账户管理

1. 现阶段账户管理功能优先级不高，暂时不做。
2. 增加密码找回功能。

### 订单管理

** 搜索/筛选 **

1.  订单状态下拉选项增加“全部”，不再设置清空条件按钮。
2.  时间选择控件，起始时间和结束时间应分开进行设置。

    *   选择起始时间时结束时间也会跟着改变，或者在选择结束时间时起始时间跟随改变。
    *   无法截取一天时间内的某个时段进行查询（确定按钮无法点击）

3.  选择查询条件进行查询，清空查询条件后列表数据没有恢复默认状态。

** 订单列表 **

1.  订单列表应显示购买的全部商品,其中包括商品缩略图、商品名称、规格属性、商品价格、购买数量。
2.  订单状态没有“已删除”，已删除状态是针对客户端用户隐藏的订单，和商户没有关联性。
3.  订单列表每页默认显示20条订单。

** 订单详情 **

1.  备注信息在卖家每次提交时 都会覆盖掉已有内容，包括清空状态下的覆盖。

---

### 售后管理

** 售后查询 **
1. 售后详情，售后信息与处理记录之间间距过大。

** 售后设置 **

1. 必须有一个地址为默认地址，默认地址不可删除。
2. 删除默认地址时，提示信息错误。
![](https://i.imgur.com/mEgHeLQ.png)
3. 有且仅有一个收货地址时，该地址为默认地址。

---

### 商品管理

** 发布商品 **
1. 商品分类选择，第三季分类下无内容，去掉展开箭头。
2. 提示信息（注：如果未找到想要发布的商品分类，需要修改主营类目，请联系lichi.com）错误，暂改为请联系平台客服。
![](https://i.imgur.com/Roz5G7m.png)
3. 新建运费模板时应在新页面中打开模板编辑页，不能中断当前操作。




