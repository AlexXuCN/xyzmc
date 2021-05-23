# 指令

## 登录插件相关
**注册**  
`/register <密码> <重复密码>`  
或 `/reg <密码> <重复密码>`

**登录**  
`/login <密码>`  
或 `/l <密码>`

**修改密码**  
`/changepassword <旧密码> <新密码> <重复新密码>`    
或 `/changepw <旧密码> <新密码> <重复新密码>`

**绑定邮箱**   
`/bindemail set <邮箱>`  
或`/bdmail set <邮箱>`  
*后续请按游戏内提示操作

**忘记密码**
`/resetpassword forget`  
或`/repw forget`  
*后续请按游戏内提示操作

## 空岛插件
### 常规

**获取空岛插件帮助**  
`/island help`  
或`/is help`  

**创建/回到你的空岛**  
`/island`  
或`/is`  
![经典空岛](/assets/images/Command-is-create-0.png "经典空岛")  
![双空岛](/assets/images/Command-is-create-1.png "双空岛")  
![更更更更难的空岛](/assets/images/Command-is-create-2.png "更更更更难的空岛")  
![L形空岛](/assets/images/Command-is-create-3.png "L形空岛")  

**创建空岛**  
`/island create`  
或`/ls create`

**回到空岛**  
`/island go`  
或`/is go`  
或`/island spawn`  
或`/is spawn`

**重置空岛**  
`/island reset`  
或`/is reset`  
*需在10秒输入两次以确认，建议提前复制  
* **三思而后行！！！**

**空岛商店** (其实是空岛的挑战任务，当商店来用吧)  
`/island challenges`
或`/is challenges`


### 岛屿等级

*注: 岛屿等级与方块数量和死亡次数有关

**查看**  
`/island level [player]`  
或`/is level [player]`  
*[player ]参数为玩家名, 代表查看谁的等级, 输入时不用带 "[" 和 "]"  
不加 [player] 代表自己

**排名**  
`/island top`  
或`/is top`

### 设置

**语言**  
`/island language`
或`/is language`

**查看参数**  
`/island info`  
或`/is info`

**空岛参数设置**  
`/island settings`
或`/is settings`  
*多图标警告

**空岛名称**  
`/island setname <新名称>`  
或`/is setname <新名称>`  
*重置名称  
`/island resetname`  
或`/is resetname`

**空岛出生点**  
`/island sethome`  
或`/is sethome`

**生物群系**(暂时没什么卵用)  
`/island biomes`  
或`/is biomes`

### 多人游戏

**获取帮助**  
`/island team`  
或`/is team`

**邀请他人加入自己的岛屿**  
`/island team invite <player>`  
或`/is team invite <player>`  
*\<player\>参数为玩家名, 输入时不用带 "<" 和 ">"  
* **被邀请者如果接受，他的岛屿将不复存在！！！！！！**  

**接受邀请**  
`/island accept`  
或`/is accept`  
* **三思而后行！！！**   

**拒绝邀请**  
`/island reject`  
或`/is reject`

**离开这个让你心碎的岛屿**  
`/island team leave`  
或`/is team leave`  
*岛屿所有者无法使用

**从岛屿中移除玩家**  
`/island team kick <player>`  
或`/is team kick <player>`  
*\<player\>参数为玩家名, 输入时不用带 "<" 和 ">"  
*仅岛屿所有者可用

**转移岛屿所有者**  
`/island team setowner <player>`  
或`/is team setowner <player>`  
*\<player\>参数为玩家名, 输入时不用带 "<" 和 ">"  
*仅岛屿所有者可用

**信任岛外人员**
`/island team trust <player>`  
或`/is team trust <player>`  
*\<player\>参数为玩家名, 输入时不用带 "<" 和 ">"  
*仅岛屿所有者可用

**取消信任岛外人员**(上一条的反向操作)
`/island team untrust <player>`  
或`/is team untrust <player>`  
*\<player\>参数为玩家名, 输入时不用带 "<" 和 ">"  
*仅岛屿所有者可用

**ban掉岛外人员**(禁止通过任何方式入岛)
`/island ban <player>`  
或`/is ban <player>`  
*\<player\>参数为玩家名, 输入时不用带 "<" 和 ">"  
*仅岛屿所有者可用

**取消ban**(上一条的反向操作)
`/island unban <player>`  
或`/is unban <player>`  
*\<player\>参数为玩家名, 输入时不用带 "<" 和 ">"  
*仅岛屿所有者可用

**被ban列表**
`/island banlist <player>`  
或`/is banlist <player>`  
*\<player\>参数为玩家名, 输入时不用带 "<" 和 ">"  

## 传送

### 使用空岛传送牌

**设置方法**

在**你的**空岛上立一块告示牌  
上书

> [Welcome]  

![传送牌](/assets/images/Command-is-language-cn.png "传送牌")  
如果你的岛屿等级足够，应该会有提示，并且牌子的字会变绿

**去到某人的传送牌**  
`/island warp <player>`  
或`/is warp <player>`  
*\<player\>参数为玩家名, 输入时不用带 "<" 和 ">"  

**去到某人的传送牌(带UI)**
`/island warps`  
或`/is warps`

### 使用warp插件  

*注: 最多设置三个传送点

**设置传送点**  
`/warp set \<名称\>`  
**\<名称\>参数为传送点名, 输入时不用带 "<" 和 ">"  

**删除传送点**  
`/warp del \<名称\>`  
**\<名称\>参数为传送点名, 输入时不用带 "<" 和 ">"  

**传送至传送点**  
`/warp \<名称\>`  
**\<名称\>参数为传送点名, 输入时不用带 "<" 和 ">"  

### tpa  

**发送传送到对方请求**  
`/tpa <player>`
*\<player\>参数为玩家名, 输入时不用带 "<" 和 ">"  

**发送传送对方到此请求**  
`/tpahere <player>`
*\<player\>参数为玩家名, 输入时不用带 "<" 和 ">"  

**接受请求**  
`/tpaccept`

**拒绝请求**  
`/tpdeny`
