# Nonebot 漂流瓶插件
* 安装
    -
    - 使用 `pip install nonebot_plugin_bottle`
    - 使用 `nb plugin install nonebot_plugin_bottle`
* 指令 (前应带指令前缀)
    - 
    - `扔漂流瓶` [文本/图片]
    - `捡漂流瓶` 
    - `评论漂流瓶` [漂流瓶编号] [文本]
    - `举报漂流瓶` [漂流瓶编号]
    - `查看漂流瓶` [漂流瓶编号]
    - SUPERUSER指令：
        - `清空漂流瓶`
        - `删除漂流瓶 [漂流瓶编号]`
* 功能须知
    -
    - `扔漂流瓶`指令无字数限制，如需要可在代码中修改
    - `捡漂流瓶`若捡到的漂流瓶存在回复，则会显示最近三条(默认)，使用`查看漂流瓶`查看所有回复
    - `查看漂流瓶`为保证随机性，无评论时不展示漂流瓶内容，可在代码中修改
    - `评论漂流瓶`若机器人有被回复人好友，会发送被回复通知
    - `举报漂流瓶`五次(默认)后将自动删除
    - `清空漂流瓶`无确认过程，使用需谨慎
    - `漂流瓶数据库`存放在`data/bottle/data.json`中
* 已知bug
    -
    - 第一次加载该插件时无法正常使用（重启后恢复）
* 效果展示
    -
    ![image](https://user-images.githubusercontent.com/97968466/191049649-2e8d8555-f285-470f-9f7b-f5a0994341ee.png)
    ![image](https://user-images.githubusercontent.com/97968466/191049794-1b409436-fd70-43d9-8dcb-3575e82fd69b.png)
    ![image](https://user-images.githubusercontent.com/97968466/191050004-0c5579cf-2d45-4fc3-af62-04205261d1a2.png)
