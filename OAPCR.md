# OAPCR产品文档
	作者：李爱勇
	版本：v0.1.3.2、 时间：2015/12/29、 更新： 12/29/2015 2:22:05 PM 
	版本：v0.1.3.3、 时间：2016/01/05、 更新：1/5/2016 5:14:16 PM 

> 字体、大小、颜色、透明度等显示属性由UI设计确定，特殊说明：字体大小使用偶数。
>
> 设计中如有不协调或其他违和感可提出意见或建议
> 
>
> ## 一些特殊样式范例，仅本文档使用
> + <span style=text-decoration:line-through>这里是被删除的</span>
> + <span style=color:green>绿色</span> <span style=color:red>红色</span> <span style=color:blue>蓝色</span> <span style=color:yellow>黄色</span> <span style=color:orange>橙色</span>

## 启动页

![启动页](http://oapcr.sso.dcux.com/images/proto/splash.png)

1. **背景图**
	- 校园风
2. **LOGO**
	- 校园风
	- 华东理工大学
3. **启动进度**
	- 不一定是条状
	- 不一定有百分比
4. **版本号**
	- 位置不固定

## 登录页 ##

![登录页](http://oapcr.sso.dcux.com/images/proto/login.png)

1. **登录标题**
	- 1.1 背景UI设计
	- 1.2 标题居中
2. **输入框**
	- 2.1 用户名输入框
		* 2.1.1 提示信息： `用户名`
		* 2.1.2 获取焦点时，隐藏提示信息
		* 2.1.3 失去焦点时，如果无输入内容则显示提示信息，否则不变
		* 2.1.4 输入框中是否有icon小图标，UI设计
	- 2.2 密码输入框
		* 2.2.1 提示信息： `密码`
		* 2.2.2 获取焦点时，隐藏提示信息
		* 2.2.3 失去焦点时，如果无输入内容则显示提示信息，否则不变
		* 2.2.4 用户名输入框变更时，不清空
		* 2.2.5 输入框中是否有icon小图标，UI设计
3. <span style=text-decoration:line-through>**身份选择项**</span>

		只用于演示
4. **确认按钮**
	- 4.1 检测用户名是否为空
	- 4.2 检测密码是否为空
	- 4.3 演示时是否选择了角色
	- 4.4 检测失败时以弹框的形式展示提示信息，

		![登录页弹框](http://oapcr.sso.dcux.com/images/proto/login_popup.png)
		> 使用系统原生弹框
5. **错误信息**
	- 5.1 用户为空时提示 `用户名不能为空`
	- 5.2 密码为空时提示 `密码不能为空`
	- 5.3 暂无其他严格检测信息
6. **背景**

	UI设计

## 兴趣选择 ##

1. **兴趣项**
	- 待定，运营一段后再确认，后台提供修改
	- 只有初次登录时让用户选择兴趣项
	- 第一版不提供重新选择兴趣项入口

## 首页 ##

![主页](http://oapcr.sso.dcux.com/images/proto/main.png)
> 可上下滚动

![首页](http://oapcr.sso.dcux.com/images/proto/main_home.png)

1. **标题栏**

	![标题](http://oapcr.sso.dcux.com/images/proto/main_home_title.png)
	- 1.1 背景UI设计
	- 1.2 标题居中
	- 1.3 不可滚动
2. **轮播图**

	![轮播图](http://oapcr.sso.dcux.com/images/proto/main_home_slide.png)
	- 2.1 三条推荐的校园动态。可以是活动、新闻、课程等，必须是有图片的。
	- 2.2 每个图片下方有标题，透明背景。
	- 2.3 点击进入对应详情页，如活动则进入该活动详情页
	- 2.4 每次新打开App时更新
3. **消息**

	![消息](http://oapcr.sso.dcux.com/images/proto/main_home_msg.png)
	- 3.1 三条消息
	- 3.2 上下滑动切换
	- 3.3 优先显示版本更新消息
	- 3.4 优先最新消息
	- 3.5 每次新打开App时更新
4. **活动**

	![活动信息](http://oapcr.sso.dcux.com/images/proto/main_home_activity.png)
	- 4.1 三个活动
	- 4.2 最新优先，由左向右排列
	- 4.3 包含公开可参与的和已参与的
	- 4.4 优先显示有icon的活动
	- 4.5 无icon的用标题代替，
	- 4.6 无icon时，使用不同背景，可以是默认图，可以是背景色，UI设计
	- 4.7 提供更多入口
	- 4.8 每次新打开App时更新
5. **课程**

	![课程信息](http://oapcr.sso.dcux.com/images/proto/main_home_course.png)
	- 5.1 三个课程
	- 5.2 最新优先，由左向右排列
	- 5.3 显示课程标题
	- 5.4 提供更多入口
	- 5.5 不同背景，可以是默认图，可以是背景色，UI设计
	- 5.6 每次新打开App时更新
6. **成绩**

	![成绩信息](http://oapcr.sso.dcux.com/images/proto/main_home_score.png)
	- 6.1 三个课程成绩
	- 6.2 最新优先
	- 6.3 提供更多入口
	- 6.4 每次新打开App时不更新，当进入成绩详细列表时更新
7. **推荐新闻**

	![推荐新闻](http://oapcr.sso.dcux.com/images/proto/main_home_news.png)
	- 7.1 三条推荐新闻
	- 7.2 不能与轮播图中的新闻重复
	- 7.3 无评论
	- 7.4 显示发布时间
	- 7.5 每次新打开App时更新
8. **菜单栏**

	![菜单](http://oapcr.sso.dcux.com/images/proto/main_menu.png)
	- 8.1 三栏，左侧“首页”、中间“时间轴”、右侧“我的”
	- 8.2 在首页时，首页菜单高亮显示。其他类推。
	- 8.3 菜单图标UI设计
	- 8.4 有未读消息时，“我的”图标上增加红点<span style="color:red;font-size:64px;line-height:16px;vertical-align: middle;" >·</span>。首页或事项有更新时类似
	- 8.5 在首页状态下，再次点击“首页”图标，刷新首页里的数据
	- 8.6 在时间轴状态下，再次点击“时间轴”图标，刷新时间轴里的数据
## 时间轴 ##

![时间轴](http://oapcr.sso.dcux.com/images/proto/main_timeline.png)

> 可上下滚动

1. **加载**
	- 第一次打开时，获取最新指定个数事项信息
	- 再次打开时，
		* 有前端缓存时，读取缓存事项
		* 有前端缓存时，检测是否有新事项
			+ 有，则在菜单上的“事项”图标上增加红点<span style="color:red;font-size:64px;line-height:16px;vertical-align: middle;" >·</span>
			+ 无，不变
		* 无前端缓存时，获取最新指定个数事项信息
2. **标题栏**
	- 新增。右侧，点击弹出活动或私人二选一的选择框
	- 选择活动。进入新增活动页
	- 选择私人。进入新增私人事项页
	
	![事项新增框](http://oapcr.sso.dcux.com/images/proto/main_timeline_popup.png)
3. **时间轴**
	- 2.1 下拉刷新，上拉加载更多
	- 2.2 包含活动、课程、私人事项
	- 2.3 时间轴线
		* 左侧图标。活动为创建人头像，课程为教师头像，私人为自己头像
		* 轴线上为事项时间点，显示小时与分钟，24小时制
		* 轴线上时间跨年时显示年份，跨日时显示月份与日期
		* 右侧事项主体
	- 2.4 课程

		![课程](http://oapcr.sso.dcux.com/images/proto/main_timeline_course.png)
		* 只显示已参与的
		* 左侧为教师头像
		* 右侧主体，点击进入课程详情页
			+ 背景。与活动、私人区分
			+ 标题。加粗字体
			+ 课程教师、地点、时间一行内显示
			+ 标签。区分系统标签与自定义标签。最多三个，如果标签过长溢出一行时，则不显示有溢出的标签
			+ 图片。有时展示，最多三张
			+ 友好时间显示，如“12月28日第3~4节”
			+ 通知。该课程教师可显示
			+ 生成签到。该课程教师可显示，点击进入课程生成签到选择方式页

			![生成签到选择方式页](http://oapcr.sso.dcux.com/images/proto/course_sign_gen.png) ![生成扫码签到](http://oapcr.sso.dcux.com/images/proto/course_sign_gen_qr.png) ![生成答题签到](http://oapcr.sso.dcux.com/images/proto/course_sign_gen_question.png)

			+ 签到。课程教师打开签到时，参与人员可显示。该课程教师生成签到时使用扫码时，点击进入扫码签到页；答题时，则是答题签到页。
			+ 评论。所有人都可评论，点击进入课程评论页
			+ 点赞。所有人都可点赞。三种状态：可点赞，已点赞，不可用。点赞后可取消点赞，不可点踩
			+ 点踩。所有人都可点踩。三种状态：可点踩，已点踩，不可用。点踩后可取消点踩，不可点赞
	- 2.5 活动。

		![活动](http://oapcr.sso.dcux.com/images/proto/main_timeline_activity.png)
		* 只显示已参与的
		* 左侧为活动创建人头像
		* 右侧主体，点击进入活动详情页
			+ 背景。与课程、私人区分
			+ 标题。加粗字体
			+ 活动类型、地点、时长，不可换行
			+ 标签。区分系统标签与个人标签。最多三个，如果标签过长溢出一行时，则不显示有溢出的标签
			+ 图片。有时展示，最多三张
			+ 友好的时间显示。如“30分钟后”
			+ 生成签到。活动创建人和管理者可显示，点击进入生成签到选择方式页
			+ 签到。活动管理人员打开签到时，参与人员可显示，根据活动设置点击进入扫码或答题签到页
			+ 评论。所有人都可评论，点击进入活动评论页
			+ 点赞。所有人都可点赞。三种状态：可点赞，已点赞，不可用。点赞后可取消点赞，不可点踩
			+ 点踩。所有人都可点踩。三种状态：可点踩，已点踩，不可用。点踩后可取消点踩，不可点赞
	- 2.6 私人事项

		![私人事项](http://oapcr.sso.dcux.com/images/proto/main_timeline_private.png)
		* 左侧为本人头像
		* 右侧主体。无详情页
			+ 背景。与活动、课程区分
			+ 标题。加粗字体
			+ 地点。不可换行
			+ 图片。有时展示，最多三张
			+ 内容。事项内容
			+ 友好的时间显示。如“30分钟后”


## 我的 ##

![我的](http://oapcr.sso.dcux.com/images/proto/main_me.png)

1. **标题栏**
	- 背景透明
	- 系统设置。右侧，点击进入系统设置页
2. **个人背景图**
	- 第一版固定背景图
3. **头像**
	
4. **昵称**
	- 唯一
	- 提供一次更改的机会
	- 可更改时点击弹出输入框

	![昵称修改弹框](http://oapcr.sso.dcux.com/images/proto/main_me_popup.png)

	- 修改昵称输入框。不可为空
	- 点击确定按钮。如果昵称输入框为空时，提示昵称不可为空；如果已存在时，提示已经存在
	> 错误提示使用系统原生弹框
5. **消息**
	- 点击进入消息列表

	![消息列表](http://oapcr.sso.dcux.com/images/proto/msg_list.png)
	- 包含系统推送消息、课程提醒、活动提醒、私人事项提醒、他人发送的消息
6. **电脑登录**
	- 点击打开电脑登录

	![电脑登录](http://oapcr.sso.dcux.com/images/proto/pc_login.png) ![电脑登录](http://oapcr.sso.dcux.com/images/proto/pc_login_confirm.png)

7. **个人信息**
	- 点击进入个人信息页

	![个人信息](http://oapcr.sso.dcux.com/images/proto/user_info.png)  ![个人信息](http://oapcr.sso.dcux.com/images/proto/user_info_teacher.png)
	- 区分教师与学生
8. **反馈**
	- 点击进入反馈页

	![反馈](http://oapcr.sso.dcux.com/images/proto/feedback.png)
9. **关于**
	- 点击进入关于页

	![关于](http://oapcr.sso.dcux.com/images/proto/about.png)
	- 版本更新，点击检测版本。如有更新弹出确认更新选择框，如果无更新提示
	- 功能介绍，弹出功能介绍
9. **系统设置**

	![关于](http://oapcr.sso.dcux.com/images/proto/setting.png)
	- 推送消息，可关闭系统推送的且是可关闭的一些消息，但版本更新消息则不可取消
	- 课程提醒，可关闭课程相关的提醒，但教师发送变更通知不关闭
	- 活动提醒，可关闭活动相关的提醒
	- 私人事项提醒，可私人事项相关的提醒
	- 仅在WIFI下加载图片
	- 清理缓存

## 个人主页 ##

![个人主页](http://oapcr.sso.dcux.com/images/proto/user_page.png)

1. **状态**
	- 4种状态。
	+ 教师本人，显示姓名，没有备注和发送信息

	![教师本人](http://oapcr.sso.dcux.com/images/proto/user_page_teacher_self.png)
	+ 其他教师，不显示姓名，有备注和发送信息

	![其他教师](http://oapcr.sso.dcux.com/images/proto/user_page_teacher.png)
	+ 学生本人，显示姓名，没有备注和发送信息

	![学生本人](http://oapcr.sso.dcux.com/images/proto/user_page_student_self.png)
	+ 其他学生，不显示姓名，有备注和发送信息

	![其他学生](http://oapcr.sso.dcux.com/images/proto/user_page_student.png)
2. **人物类型**
	- 教师
		+ 姓名，只有本人可以看见
		+ 性别
		+ 学校
		+ 职称
	- 学生
		+ 姓名，只有本人可以看见
		+ 性别
		+ 年级
		+ 学校
		+ 学院

## 课程列表 ##

![课程列表](http://oapcr.sso.dcux.com/images/proto/course_list.png)

1. **加载**
	- 最新的、自己的课程
	- 可上拉更多、下拉刷新
	- 初始显示5个
2. **课程列表**
	- 可点赞、点踩、签到、
	- 有权限时可生成签到
	- 学生可以给教师留言
	- 教师可以发送课程通知
	- 评论即打开详情，并移动至评论处

## 课程详情页 ##

![课程事项](http://oapcr.sso.dcux.com/images/proto/course.png)

1. **课程基本属性**
	- 标题
	- 教师、地点、时间、时长
		* 时长友好显示，如“12月30日第3~4节”
	- 标签，后台自动生成或后台编辑。第一版不提供打标签功能
	- 状态
		* 分为：未开始、进行中、已结束。
		* 不同状态下不同的表现形式
	- <span style=text-decoration:line-through>图标</span>，第一版不提供图标，相应的添加、修改、查看中图标也去除
	- 班级，可以是多个
	- <span style=color:yellow>介绍，可以空</span>，待定
	- <span style=color:yellow>图片，可以空。有数量和大小限制</span>，待定
2. **功能**
	- 点赞，点赞后不可点踩，可取消
	- 点踩，点踩后不可点赞，可取消
	- 评论，可以带图片的评论。评论可以被回复，包括自己和他人
	- 留言，学生可以留言，不带图片
	- 通知，任课教师可以发送通知，不带图片
	- 签到，学生签到
	- <span style=color:yellow>课程不可以修改，但可以修改介绍和上传图片<span>，待定

## 活动列表 ##

![活动列表](http://oapcr.sso.dcux.com/images/proto/activity_list.png)

1. **加载**
	- 最新的、自己的、可参与并推荐的活动
	- 可上拉更多、下拉刷新
	- 初始显示5个
2. **活动列表**
	- 可点赞、点踩、签到
	- 有权限时可生成签到
	- 可报名参与
	- 评论即打开详情，并移动至评论处
	- 有权限时可以修改、删除

## 活动详情页 ##

![活动事项](http://oapcr.sso.dcux.com/images/proto/activity.png)

1. **活动基本属性**
	- 标题
	- 创建人
	- 管理人员
	- 时间
	- 地点
	- 时长
	- 标签，可以通过修改功能修改标签
	- <span style=text-decoration:line-through>图标</span>，第一版不提供图标，相应的添加、修改、查看中图标也去除
	- 图片
		* 可以多图片，有数量限制
	- 报名参与，提供可报名选项
2. **功能**
	- 点赞，点赞后不可点踩，可取消
	- 点踩，点踩后不可点赞，可取消
	- 签到，创建人和管理人员无需签到
	- 评论，可以带图片的评论。评论可以被回复，包括自己和他人
	- 报名参与，也可取消参与，取消后在一段时长内不可再参与。管理员取消参与时，同时取消管理员身份。创建人不可以取消参与，只能删除该活动
	- 修改，
	- 删除
	- 添加
	- 变更管理人员，在修改功能中变更

## 活动添加 ##

![活动添加](http://oapcr.sso.dcux.com/images/proto/activity_add.png)

1. **功能**
	- <span style=color:red>去除活动图标项<span>
	- 活动人员，去除勾选自己，默认自动添加自己，点击设置管理人员，长按删除

## 私人事项添加 ##

![私人事项添加](http://oapcr.sso.dcux.com/images/proto/private_add.png)

## 新闻列表 ##

![新闻列表](http://oapcr.sso.dcux.com/images/proto/news_list.png)

1. **加载**
	- 优先最新的，优先推荐的
	- 可上拉更多、下拉刷新
	- 初始显示5个

## 新闻详情 ##

![新闻详情](http://oapcr.sso.dcux.com/images/proto/news.png)

1. **活动基本属性**
	- 标题
	- 来源
	- 时间
	- 正文，含图片与文字
2. **功能**
	- 只查看，无评论、点赞等
	- 后台提供新增、修改、删除、置顶、推荐等功能
		+ 置顶，置顶数量限制
		+ 推荐，有图片新闻才可推荐至轮播图中

## 成绩 ##

![成绩](http://oapcr.sso.dcux.com/images/proto/score_list.png)

1. **功能**
	- 显示当前学期的所有课程成绩
	- 提供概览功能，有些统计信息待定
		+ 总学分
		+ 总绩点
		+ 选修数
		+ 挂科数 
	- 挂科突出显示
	- 选修与必修区分
	- 可查看历史成绩，选择年和学期的形式
