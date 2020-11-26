---
#用户管理
---

##1 进入用户管理模块

点击页面顶部菜单栏的 <u>用户</u> ，即可进入用户管理模块。  
![avatar](../images/userGuide/user/userMenu-cn.jpg)
![avatar](../images/userGuide/user/userList-cn.jpg)

##2 用户检索

###2.1 检索用户ID中包含输入文字的用户
如下图，用户列表上方有检索框，可通过它检索用户。
检索的匹配模式是部分包含匹配，即用户ID中包含输入的检索文字的用户会被检索到。且检索文字不区分大小写。
![avatar](../images/userGuide/user/userSelCtrl-cn.jpg)
首先，在检索框中输入检索文字，
![avatar](../images/userGuide/user/inputSelUserWord-cn.jpg)
然后点击检索按钮(即放大镜图标),或者按回车键(Enter键)，
![avatar](../images/userGuide/user/selUserIcon-cn.jpg)
用户ID中包含检索文字的用户被检索出来。
![avatar](../images/userGuide/user/selectedUser-cn.jpg)

###2.2 显示所有用户
如果想显示所有用户，则删除检索框中的所有文字，之后点击检索按钮，即可显示所有用户。

##3 下载用户信息一览
可以点击下载按钮，将用户信息一览以csv文件格式下载到本地电脑。

点击下图红框中的下载按钮，
![avatar](../images/userGuide/user/downUserFileIcon-cn.jpg)
下载完成后，浏览器底部显示下载完成的文件，点击文件右边的箭头，
![avatar](../images/userGuide/user/downloadedUser-cn.jpg)
在弹出的菜单中，选择 <u>在文件夹中显示</u> ,
![avatar](../images/userGuide/user/showDownFileInFld-cn.jpg)
下载文件的所在文件夹被打开，可以看到下载文件，
![avatar](../images/userGuide/user/openDownFileFld-cn.jpg)
打开文件，确认文件里的用户信息。
![avatar](../images/userGuide/user/openDownUserFile-cn.jpg)

##4 新建用户
新建用户有两种方式。
&emsp;第一种是点击用户列表左上方的的 <u>+新建</u> 按钮(参见下图的第一个红框)。
&emsp;第二种是点击上传按钮，通过上传的csv文件批量新建用户(参见下图的第二个红框)。
![avatar](../images/userGuide/user/newUserTwoBtn-cn.jpg)

以下分别说明两种新建用户的方法。

###4.1 点击用户列表左上方的 <u>+新建</u> 按钮来新建用户
点击用户列表左上方的 <u>+新建</u> 按钮,
![avatar](../images/userGuide/user/addUserBtn-cn.jpg)
进入新建用户页面,
![avatar](../images/userGuide/user/newUserInit-cn.jpg)
输入要新建的用户信息后，点击<u>保存</u>按钮,
![avatar](../images/userGuide/user/newUser-cn.jpg)
页面跳转到用户信息详情页面。可继续进行用户其它信息的设定。
![avatar](../images/userGuide/user/userCreated-cn.jpg)

<u>**用户图片设定的说明：**</u>
如下图，点击上载，
![avatar](../images/userGuide/user/userPicBtn-cn.jpg)
弹出文件选择框，
![avatar](../images/userGuide/user/selFileDlg-cn.jpg)
选择一个图片文件，之后点击<u>打开(O)</u>按钮，
![avatar](../images/userGuide/user/selFileDlgOpen-cn.jpg)
图片上载并显示。
![avatar](../images/userGuide/user/userPicSeled-cn.jpg)

当要改变用户图片时，则将鼠标移动到图片上，则会出现下图中的眼睛图标和垃圾箱图标。
![avatar](../images/userGuide/user/userPicMouseUp-cn.jpg)
点击眼睛图标，可以放大图片
![avatar](../images/userGuide/user/userPicZoomInIcon-cn.jpg)
![avatar](../images/userGuide/user/userPicZoomIn-cn.jpg)
若要关闭放大，则点击放大框的右上角的 <u>X</u> 即可。
![avatar](../images/userGuide/user/userPicZoomInCloseIcon-cn.jpg)

更改用户图片时，则点击垃圾箱图标
![avatar](../images/userGuide/user/userPicBinIcon-cn.jpg)
则设定的图片被删除。删除后，若想重新设定，则可点击<u>上载</u>重新选择图片。
![avatar](../images/userGuide/user/userPicDeled-cn.jpg)

###4.2 通过上传的csv文件批量新建用户
首先准备好用户csv文件,csv文件的内容和格式参见下图中的newUserList.csv，
![avatar](../images/userGuide/user/userCsvFile-cn.jpg)
点击用户列表右上方的上载按钮，
![avatar](../images/userGuide/user/uploadUserCsvIcon-cn.jpg)
弹出文件选择框，
![avatar](../images/userGuide/user/selFileDlgUserCsv-cn.jpg)
选择准备的用户csv文件，之后点击<u>打开(O)</u>按钮，
![avatar](../images/userGuide/user/selectedUserCsv_cn.jpg)
画面回到用户一览页面，可以看到用户csv文件中的用户已显示在用户一览中。
![avatar](../images/userGuide/user/addedUserByCsv-cn.jpg)


##5.用户综合信息管理
点击要修改的用户的用户ID(当用户较多时，可通过检索缩小一览里的用户条数)，
![avatar](../images/userGuide/user/clickOneUserInList-cn.jpg)
进入用户综合信息管理画面,此页面提供以下功能：
- 编辑：用户基本信息修改
- 总览：用户工单完成情况一览
- 群组会员：用户所属群组一览、删除群组
- 项目：用户项目一览、新建项目和删除项目
- 工作流：用户工作流一览和删除
- 工单：用户工单一览、删除工单
- 活动：用户操作记录一览
- 备注：用户项目备注一览
     
![avatar](../images/userGuide/user/userViewInit-cn.jpg)

###5.1 修改用户基本信息
若要修改用户基本信息，则点击用户综合信息管理页面左上方的 <u>编辑</u> 按钮,
![avatar](../images/userGuide/user/editUserBtn-cn.jpg)
进入用户基本信息修改页面，
![avatar](../images/userGuide/user/editUserInit-cn.jpg)
修改用户信息，之后点击 <u>保存</u> 按钮,
![avatar](../images/userGuide/user/editUser-cn.jpg)
返回用户综合信息管理页面，可以看到用户信息已被修改。
![avatar](../images/userGuide/user/editedUser-cn.jpg)

###5.2 用户总览标签页
进入用户综合信息管理页面后，页面右栏的第一个就是用户总览标签页。
如果在其它标签页，点击<u>用户总览</u>标签，切换到用户总览标签页。
图中的方格是日期方格，绿色方格表示有工作，灰色方格表示空闲。
![avatar](../images/userGuide/user/userViewOverall-cn.jpg)

将鼠标移至要查看的日期方格上，会显示此格的日期以及工单件数。
![avatar](../images/userGuide/user/userOverallMouseUp-cn.jpg)
鼠标单击要查看的日期方格，则会总览标签页下部显示工单详情列表。
![avatar](../images/userGuide/user/userOverallClicked-cn.jpg)

###5.3 群组会员标签页
点击群组会员标签，
![avatar](../images/userGuide/user/userViewGropTag-cn.jpg)
进入此用户的所属群组会员一览页面。
![avatar](../images/userGuide/user/userViewGropList-cn.jpg)

####5.3.1 用户所属群组的检索
当群组较多时，可通过群组一览左上方的检索框，缩小一览中的群组表示条数。
检索匹配模式为包含模式。即群组编号中包含所输入的检索文字的群组被检索出来。且检索文字不区分大小写。

例如下图,检索框中输入检索文字,
![avatar](../images/userGuide/user/userViewGropSelWord-cn.jpg)
然后点击检索按钮(即放大镜图标),或者按回车键(Enter键)，
![avatar](../images/userGuide/user/userViewGropSelIcon-cn.jpg)
群组编号中包含检索文字的群组被检索出来。
![avatar](../images/userGuide/user/userViewGropSelected-cn.jpg)

**[备注]**当想要显示所有群组时，则删除检索框中的所有文字，然后点击检索按钮(即放大镜图标),或者按回车键(Enter键)即可。

####5.3.2 用户所属群组的删除
从群组一览中，点击要删除群组的前面的复选框，
![avatar](../images/userGuide/user/userViewGropChkbox-cn.jpg)
选中后，群组一览上方显示选中的条数以及<u>删除</u>按钮，
![avatar](../images/userGuide/user/userViewGropChkOn-cn.jpg)
点击删除按钮，
![avatar](../images/userGuide/user/userViewGropDelBtn-cn.jpg)
弹出删除确认对话框，点击OK按钮，(若想放弃删除，则点击取消即可)，
![avatar](../images/userGuide/user/userViewDelGrpConfirm-cn.jpg)
群组一览刷新，可以看到删除的群组已从一览中消失。
![avatar](../images/userGuide/user/userViewDeledGrp-cn.jpg)

###5.4 项目标签页
点击项目标签，
![avatar](../images/userGuide/user/userViewProjTag-cn.jpg)
进入此用户的项目一览页面。注意一览的第一列(即项目一列)为<u>项目所有人</u>和<u>项目编号</u>用"/"拼接在一起的文字内容。
![avatar](../images/userGuide/user/userViewProjList-cn.jpg)

####5.4.1 用户项目的检索
当项目较多时，可通过项目一览左上方的检索框，缩小一览中的项目表示条数。
检索匹配模式为包含模式。即项目编号中包含所输入的检索文字的项目被检索出来。且检索文字不区分大小写。

例如下图,检索框中输入检索文字,
![avatar](../images/userGuide/user/userViewProjSelWord-cn.jpg)
然后点击检索按钮(即放大镜图标),或者按回车键(Enter键)，
![avatar](../images/userGuide/user/userViewProjSelIcon-cn.jpg)
项目编号中包含检索文字的项目被检索出来。
![avatar](../images/userGuide/user/userViewProjSelected-cn.jpg)

**[备注]**当想要显示所有项目时，则删除检索框中的所有文字，然后点击检索按钮(即放大镜图标),或者按回车键(Enter键)即可。

####5.4.2 新建用户项目
当想要新建一个此用户的项目时，则点击项目一览右上方的<u>+新建</u>按钮，
![avatar](../images/userGuide/user/userViewProjNewBtn-cn.jpg)
页面跳转到新建项目页面，
![avatar](../images/userGuide/user/userViewProjNewInit-cn.jpg)
输入项目信息后，点击<u>保存</u>按钮，
![avatar](../images/userGuide/user/userViewProjNew-cn.jpg)
页面跳转到项目总览页面，
![avatar](../images/userGuide/user/userViewProjCreated-cn.jpg)
重新回到用户综合信息管理页面的项目标签页(打开此页面的方法请参见 ##1 进入用户管理模块->##5.用户综合信息管理->###5.4 项目标签页 ),
可以看到新建的项目已显示在项目一览中。
![avatar](../images/userGuide/user/userViewProjCreatedReList-cn.jpg)

####5.4.3 用户项目的删除
从项目一览中，点击要删除项目的前面的复选框，
![avatar](../images/userGuide/user/userViewProjChkbox-cn.jpg)
选中后，项目一览上方显示选中的条数以及<u>删除</u>按钮，
![avatar](../images/userGuide/user/userViewProjChkOn-cn.jpg)
点击删除按钮，
![avatar](../images/userGuide/user/userViewProjDelBtn-cn.jpg)
弹出删除确认对话框，点击OK按钮，(若想放弃删除，则点击取消即可)，
![avatar](../images/userGuide/user/userViewDelProjConfirm-cn.jpg)
项目一览刷新，可以看到删除的项目已从一览中消失。
![avatar](../images/userGuide/user/userViewDeledProj-cn.jpg)

###5.5 工作流标签页
点击工作流标签，
![avatar](../images/userGuide/user/userViewWorkflowTag-cn.jpg)
进入此用户的工作流一览页面。
![avatar](../images/userGuide/user/userViewWorkflowList-cn.jpg)

####5.5.1 用户工作流的检索
当工作流较多时，可通过工作流一览左上方的检索框，缩小一览中的工作流的表示条数。
检索匹配模式为包含模式。即工作流名称中包含所输入的检索文字的工作流被检索出来。且检索文字不区分大小写。

例如下图,检索框中输入检索文字,
![avatar](../images/userGuide/user/userViewWorkflowSelWord-cn.jpg)
然后点击检索按钮(即放大镜图标),或者按回车键(Enter键)，
![avatar](../images/userGuide/user/userViewWorkflowSelIcon-cn.jpg)
工作流名称中包含检索文字的工作流被检索出来。
![avatar](../images/userGuide/user/userViewWorkflowSelected-cn.jpg)

**[备注]**当想要显示所有工作流时，则删除检索框中的所有文字，然后点击检索按钮(即放大镜图标),或者按回车键(Enter键)即可。

####5.5.2 工作流的删除
从工作流一览中，点击要删除的工作流的前面的复选框，
![avatar](../images/userGuide/user/userViewWorkflowChkbox-cn.jpg)
选中后，工作流一览上方显示选中的条数以及<u>删除</u>按钮，
![avatar](../images/userGuide/user/userViewWorkflowChkOn-cn.jpg)
点击删除按钮，
![avatar](../images/userGuide/user/userViewWorkflowDelBtn-cn.jpg)
弹出删除确认对话框，点击OK按钮，(若想放弃删除，则点击取消即可)，
![avatar](../images/userGuide/user/userViewDelWorkflowConfirm-cn.jpg)
工作流一览刷新，可以看到删除的工作流已从一览中消失。
![avatar](../images/userGuide/user/userViewDeledWorkflow-cn.jpg)

###5.6 工单标签页
点击工单标签，
![avatar](../images/userGuide/user/userViewWorkorderTag-cn.jpg)
进入此用户的工单一览页面。
![avatar](../images/userGuide/user/userViewWorkorderList-cn.jpg)

####5.6.1 工单一览说明 
(1) 工作流
将鼠标移至某工作流的工作流一列上时，将显示此工作流的概要信息。
![avatar](../images/userGuide/user/userViewWrkOrdNameMouseup-cn.jpg)
![avatar](../images/userGuide/user/userViewWrkOrdTip-cn.jpg)
(2) 目标/经过时间
工单一览中的目标/经过时间一列，是以柱状图表示的。将鼠标移至某一工单的柱状图上时，
将会显示此工单的历经时间。
![avatar](../images/userGuide/user/userViewWrkOrdTakeupTime-cn.jpg)

####5.6.2 工单的删除
从工单一览中，点击要删除的工单的前面的复选框，
![avatar](../images/userGuide/user/userViewWorkorderChkbox-cn.jpg)
选中后，工单一览上方显示选中的条数以及<u>删除</u>按钮，
![avatar](../images/userGuide/user/userViewWorkorderChkOn-cn.jpg)
点击删除按钮，
![avatar](../images/userGuide/user/userViewWorkorderDelBtn-cn.jpg)
弹出删除确认对话框，点击OK按钮，(若想放弃删除，则点击取消即可)，
![avatar](../images/userGuide/user/userViewDelWorkorderConfirm-cn.jpg)
工单一览刷新，可以看到删除的工单已从一览中消失。
![avatar](../images/userGuide/user/userViewDeledWorkorder-cn.jpg)

####5.7 活动标签页
点击活动标签
![avatar](../images/userGuide/user/userViewOperationTag-cn.jpg)
进入此用户的工单一览页面。此页面可以查看用户的操作历史。
![avatar](../images/userGuide/user/userViewOperationList-cn.jpg)

####5.8 备注标签页
点击备注标签,
![avatar](../images/userGuide/user/userViewProjMemoTag-cn.jpg)
进入此用户的项目备注一览页面。
![avatar](../images/userGuide/user/userViewProjMemoList-cn.jpg)

#####5.8.1 备注详情
点击一览的标题，
![avatar](../images/userGuide/user/userViewProjMemoTitleLink-cn.jpg)
进入备注详情页面。
![avatar](../images/userGuide/user/userViewProjMemoDtl-cn.jpg)
如果想修改备注信息，可以点击<u>编辑...</u>按钮，
![avatar](../images/userGuide/user/userViewProjMemoDtlEditBtn-cn.jpg)
进入备注修改页面，
![avatar](../images/userGuide/user/userViewProjMemoEditInit-cn.jpg)
修改备注信息，之后点击<u>保存</u>按钮，
![avatar](../images/userGuide/user/userViewProjMemoEdit-cn.jpg)
保存修改后，页面会转回备注详情页面。可以看到备注已被修改。
![avatar](../images/userGuide/user/userViewProjMemoEdited-cn.jpg)

#####5.8.1 备注的删除
从备注一览中，点击要删除的备注的前面的复选框，
![avatar](../images/userGuide/user/userViewProjMemoChkbox-cn.jpg)
选中后，备注一览上方显示选中的条数以及<u>删除</u>按钮，
![avatar](../images/userGuide/user/userViewProjMemoChkOn-cn.jpg)
点击删除按钮，
![avatar](../images/userGuide/user/userViewProjMemoDelBtn-cn.jpg)
弹出删除确认对话框，点击OK按钮，(若想放弃删除，则点击取消即可)，
![avatar](../images/userGuide/user/userViewDelProjMemoConfirm-cn.jpg)
备注一览刷新，可以看到删除的备注已从一览中消失。
![avatar](../images/userGuide/user/userViewDeledProjMemo-cn.jpg)

##6.删除用户
要删除用户，首先在用户一览里选中要删除的用户。当一览中用户数过多时，可利用检索缩减列表中用户数。
![avatar](../images/userGuide/user/selectUserInUserList-cn.jpg)
选中后，一览的上方出现选中件数信息和删除按钮。
![avatar](../images/userGuide/user/selectedUserInUserList-cn.jpg)
点击删除按钮。
![avatar](../images/userGuide/user/userListDeleteBtn-cn.jpg)
弹出删除确认对话框。
![avatar](../images/userGuide/user/deleteUserFromListConfirm-cn.jpg)
点击对话框上的OK按钮即可(若想放弃删除，则点击取消按钮)。
![avatar](../images/userGuide/user/deleteUserFromListConfirmOkBtn-cn.jpg)
用户被删除，从一览中消失。
![avatar](../images/userGuide/user/deletedUserFromList-cn.jpg)





