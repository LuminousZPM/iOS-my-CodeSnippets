# iOS-my-CodeSnippets

***
**使用方法**
CodeSnippets目录已经存在时
第一种使用方式：

1.打开终端，执行命令：`cd ~/Library/Developer/Xcode/UserData/CodeSnippets`

2.在此目录下执行命令:`git clone https://github.com/zhfei/iOS-my-CodeSnippets.git`


**CodeSnippets目录还没有创建时**

1.打开终端，执行命令：
```
git clone git@github.com:zhfei/iOS-my-CodeSnippets.git ~/Library/Developer/Xcode/UserData/CodeSnippets
```

注意：因为工程clone下来后，自带文件夹`iOS-my-CodeSnippets`，还需要做简单的处理，最终目的是让代码库的所以++资源文件+.git文件++都放到`~/Library/Developer/Xcode/UserData/CodeSnippets`文件夹下


***
==代码块命名规则制定中...==
```
//代码块命名规则
//1.基本规范
my_名词 动作_swift
my_名词 动作_oc
//2.添加block,func,txt补充说明
my_名词 动作_swift_func
my_名词 动作_oc_block
my_名词 动作_oc_txt
```
block: 方法内的代码块
func: 完整的方法
txt:工程配置变量，VC结构分割

##### 代码块类型

***
##### swift部分
1.dispatch(大中枢并发)
- my_dispatchAfter_swift_block
- my_dispatchAfterCancle_swift_func
- my_dispatchgroup_swift_block
- my_dispatchMainQueue_swift_block
- my_dispatchSemaphoreCreate_swift_block

2.serial(序列化功能)
- my_serialDataToJson_swift_func
- my_serialJsonToStr_swift_func

3.realm(Realm数据库操作)

4.alertVC(系统弹框)
- my_alertVC_swift_block

5.bezier(贝塞尔曲线)
- my_bezier_swift_block

6.button(按钮创建)
- my_btnCreate_swift_block

7.dire(目录)
8.dateFormatter(格式化时间)
- my_dateFormat2Date_swift_func
- my_dateFormat2Str_swift_func

9.property(属性创建)

10.predicate(谓词)
11.screenShot(截屏)
- my_screenShot_swift_func
- my_screenShotToPhoto_swift_func

12.suStr(子字符串)
- my_suStr_swift_func

13.imageView(imageView创建)
- my_imageViewCreate_swift_block

14.label(label创建)
- my_labelCreate_swift_block

15.layer(layer创建)
- my_layerCreate_swift_block

16.layerGradient(layerGradient渐变色图层创建)
- my_layerGradientCreate_swift_block

17.tableView(tableView代理)

18.uiFactory(uiFactor创建)
- my_uiFactory_swift_func

19.enum(enum枚举定义)

20.timer(timer创建使用)
- my_timerAfterCancle_swift_block

21.log(log使用)

22.selector(selector选择子)
- my_selector_swift_block

23.weakSelf(weakSelf弱引用)

24.width(width视图宽高)
- my_widthV+heightV_swift_block
- my_widthS+heightS_swift_block







***
##### OC部分
1.dispatch(大中枢并发)
- my_dispatchAfter_oc_block
- my_dispatchMainQueue_oc_block
- my_dispatchGlobalQueue_oc_block
- my_dispatchgroup_oc_block

2.serial(序列化功能)
3.realm(Realm数据库操作)
- my_realmCreate_oc_block
- my_realmEncry_oc_block
- my_realmMigrat_oc_block
- my_realmNotifi_oc_block

4.alertVC(系统弹框)
- my_alertVC_oc_block

5.bezier(贝塞尔曲线)

6.button(按钮创建)
7.dire(目录)
- my_dirCache_oc_block
- my_dirDocu_oc_block

8.dateFormatter(格式化时间)

9.property(属性创建)


10.predicate(谓词)
- my_predicate_oc_block

11.screenShot(截屏)

12.suStr(子字符串)

13.imageView(imageView创建)

14.label(label创建)

15.layer(layer创建)
- my_layerLine_oc_block

16.layerGradient(layerGradient渐变色图层创建)

17.tableView(tableView代理)
- my_tableViewAll_oc_block
- my_tableViewParter_oc_block

18.uiFactory(uiFactor创建)

19.enum(enum枚举定义)
- my_enum+Type_oc_block

20.timer(timer创建使用)

21.log(log使用)
- my_log_oc_block

22.selector(selector选择子)

23.weakSelf(weakSelf弱引用)
- my_weakSelf_oc_block

24.width(width视图宽高)


***
##### 工程设置，文档部分

A.arc(arc类文件设置，搜索路径)
- my_arc_txt

B.note(note注释)
- my_note_txt

C.structure(structure结构)
- my_structure_oc_txt
- my_structureCN_oc_txt
- my_structureHeardCN_oc_txt
- my_structure_swift_txt

D.property(property定义)
- my_propert_oc_txt


