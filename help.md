## 系统参数
*****
### 系统基本参数
  [针零位](#针零位)<br>
  [左系统纱嘴右行零位](#左系统纱嘴右行零位)<br>
  [左系统纱嘴左行零位](#左系统纱嘴左行零位)<br>
  [机头左限位](#机头左限位)<br>
  [机头右限位](#机头右限位)<br>
  [横机壹英寸针数](#横机壹英寸针数)<br>
  [横机总针数](#横机总针数)<br>
  [同步带齿距校正](#同步带齿距校正)<br>
  [电磁铁高压](#电磁铁高压)<br>
  [纱嘴电磁铁高压](#纱嘴电磁铁高压 )<br>
  [机头移出使能](#机头移出使能 )<br>
  [报警灯音量](#报警灯音量 )<br>
  [报警持续时间](#报警持续时间)<br>
  [自动锁行](#自动锁行)<br>
  [语言切换](#语言切换)<br>
  [加油控制配置](#加油控制配置)<br>
  [日光灯配置](#日光灯配置)<br>
  [翻针度目置零](#翻针度目置零)<br>
### 罗拉相关参数
  [主罗拉速比](#主罗拉速比)<br>
  [副罗拉转动时间](#副罗拉转动时间)<br>
### 选针器相关参数
  [选针器右行补偿](#选针器右行补偿)<br>
  [选针器左行补偿](#选针器左行补偿)<br>
  [选针器刀片个数](#选针器刀片个数)<br>
  [选针器重选](#选针器重选)<br>
  [选针器高压](#选针器高压)<br>
### 度目电机参数
  [度目最大值](#度目最大值)<br>
  [密度马达复位速度](#密度马达复位速度)<br>
  [密度马达工作速度](#密度马达工作速度)<br>
  [度目检查设置](#度目检查设置)<br>
### 摇床相关参数
  [摇床位置](#摇床位置)<br>
  [摇床间隙补偿](#摇床间隙补偿)<br>
  [摇床速度设定](#摇床速度设定)<br>
### 生克相关参数
  [生克有效](#生克有效)<br>
  [生克提前](#生克提前)<br>
  [生克完成点](#生克完成点)<br>
  [生克速度](#生克速度)<br>
  [生克最大值](#生克最大值)<br>
  [生克数据模式](#生克数据模式)<br>
  [系统生克模式](#系统生克模式)<br>
  [后沉降片复位](#后沉降片复位)<br>
  [前沉降片复位](#前沉降片复位)<br>
### 可变度目参数
  [变大补偿左行](#变大补偿左行)<br>
  [变小补偿左行](#变小补偿左行)<br>
  [变大补偿右行](#变大补偿右行)<br>
  [变小补偿右行](#变小补偿右行)<br>
  [平移补偿](#平移补偿)<br>
### 探针相关参数
  [探针类型](#探针类型)<br>
  [左侧探针位置微调](#左侧探针位置微调)<br>
  [右侧探针位置微调](#右侧探针位置微调)<br>
  [探针延时](#探针延时)<br>
### 起底板相关参数
  [卸片罗拉](#卸片罗拉)<br>
  [罗拉打开修正](#罗拉打开修正)<br>
### 网络相关参数
  [网络开关](#网络开关)<br>
  [本机IP](#本机IP)<br>
  [子网掩码](#子网掩码)<br>
  [网关设置](#网关设置)<br>
  [服务器IP](#服务器IP)<br>
  [端口号](#端口号)<br>

## 帮助说明
-----------
### 系统基本参数
####  针零位：<br>
<font color=#FF0000>机器原点设置</font>：归零复位完成后，启动拉杆使机头过针零位探头后停车，手移机头或按A（左行）、B（右行）键移动机头至针床左侧，将机头左外侧（根据客户提供的参数，外框或护山）对准针床的第一针处，方向键移动光标到指定位置，按 F1 键或触笔单击[定位]图标弹出确认选择，写入当前显示的针数值。

<table><tr><td bgcolor=#BDB76B>提醒！新机调试，设置此项参数条件：</td></tr></table>
<font color=#FF0000>按键</font>：设定横机壹英寸针数（机号E），横机总针数（幅宽）基本参数，按“Esc”键退出设定窗口，再连按“Esc”退出至运行监测画面后，拉杆启动自动复位归零。
<font color=#FF0000>触摸</font>：触笔单击横机壹英寸针数（机号E），横机总针数（幅宽）数值提示区，设定完基本参数（横机总针数，横机壹英寸针数，针零位，同步带齿距校正，机头左限位，机头右限位），单击提示栏区退出设定窗口，再单击菜单提示栏逐级退出至运行监测画面后，拉杆启动自动复位归零。
<font color=#FF0000>按键</font>：设定同步带齿距校正参数，按“Esc”键退出设定窗口，再按连按Esc或（一键至运行界面）键退出至运行监测画面后，拉杆启动自动复位归零。
<font color=#FF0000>触摸</font>：触笔单击同步带齿距校正参数，设定完校正参数，单击提示栏区退出设定窗口，再单击菜单提示栏逐级退出至运行监测画面后，拉杆启动自动复位归零。

针零位为机器重要的系统参数（原点），<font color=#FF0000>数值必须是正值</font>。
当原点参考座（磁钢）或针零位感应探头的固定位置调整后，<font color=#FF0000>必须重设此参数</font>（同步带齿距一般无需重设，除非同步带松度已超过规定要求）。
####  左系统纱嘴右行零位：
设定左系统纱嘴右行与原点距离值（针数）。

手动将某一纱嘴（一般选择“1”号）的出线口的中心对准固定针板左侧第一针中心处，然后手移机头或按A（左行）、B（右行）键移动机头，将一系统“1”号换梭电磁铁芯子的右侧对准梭箱上部位移缺口的右侧，方向键移动光标到指定位置，按F1键或触笔单击[定位]图标弹出确认选择，写入当前的针数值。
####  左系统纱嘴左行零位：<br>
设定左系统纱嘴左行与原点距离值（针数）。

手动将某一纱嘴（一般选择“1”号）的出线口的中心对准固定针板左侧第一针中心处，然后手移机头或按A（左行）、B（右行）键移动机头，将一系统“1”号换梭电磁铁芯子的左侧对准梭箱上部位移缺口的左侧，方向键移动光标到指定位置，按F1键或触笔单击[定位]图标弹出确认选择，写入当前的针数值。
####  机头左限位：<br>
设定机头左行限位与原点距离值（针数）。

手移机头或按A（左行）键往左移动，使机头限位铁片接近左限位感应探头，并保持一定的针数距离（探头指示灯灭，信号检测状态“0”），停止移动机头，方向键移动光标到指定位置，按F1键或触笔单击[定位]图标弹出确认选择，写入当前的针数值（此值一般为负整数）。

因主马达伺服在机头移出使能打开时，由于换向过程中的惯性距离，此设置针数距离需大于换向惯性距离

<font color=#FF0000>注意！</font>机头左、右限位探头作用（指示灯亮，信号检测状态“1”），主要用于保护机头在编织过程中由于非正常超程时的安全控制。
####  机头右限位：<br>
设定机头右行限位与原点距离值（针数）。<br>

手移机头或按B（右行）键往右移动，使机头限位铁片接近右限位感应探头，并保持一定的针数距离（探头指示灯灭，信号检测状态“0”），停止移动机头，方向键移动光标到指定位置，按F1键或触笔单击数值区弹出确认选择，写入当前的针数值（此值为正整数）。<br>

因主马达伺服在机头移出使能打开时，由于换向过程中的惯性距离，此设置针数距离需大于换向惯性距离<br>
####  横机壹英寸针数：<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入横机针床正确的机号数值（E），按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入所需针数，单击确定键结束。<br>
####  横机总针数：<br>
设定横机总针数（针床最大有效编织幅宽）。<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。<br>

最大设定数值：1000（针）。
####  同步带齿距校正：<br>
设定机头编织时的同步带齿距（总针数内的脉冲数值）。<br>

设置操作：<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，弹出同步带齿距校正画面<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出同步带齿距校正画面<br>
1. 手动左、右移机头，观察液晶显示屏上的编码数值变化情况（CODER项）。
  ◆右移，编码数值连续递增。
  ◆左移，编码数值连续递减。
1.  机头从左至右，或从右往左全程移动时，编码器数值不能有突变（同向移动中某一位置突然变零，然后再递增或递减），如发现此种情况请检查主马达编码器或主马达伺服分频设置不正确。
2. 左移机头至针床左侧，将机头左外侧对准针床第一针，上、下键移动光标选择“左”数值区，按数字键“1”或触笔单击[设置]图标，输入左脉冲数值。
3. 右移机头至针床右侧，将机头左外侧对准针床最后一针，上、下键移动光标选择“右”数值区，按数字键“2”或触笔单击[设置]图标，输入右脉冲数值。
4. 系统会直接计算出左、右脉冲差值（3＝2－1），显示在“同步带齿距”数值区。
5. 按保存键或触笔单击[保存]图标即可。

<table><tr><td bgcolor=#BDB76B>按Enter或直接退出都将不保存</td></tr></table>
####  电磁铁高压：<br>
设定动作电磁铁高压值（灵敏度）。<br>
范围：1－10<br>
默认：5<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。<br>

数值大小与灵敏度成反比，数值越大，灵敏度越低。一般当电磁铁长时间使用后，请将此参数恰当调大一些。

####  纱嘴电磁铁高压：<br>
设定纱嘴电磁铁高压值（灵敏度）。<br>
范围：1 - 10<br>
默认：5<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。<br>
####  机头移出使能：<br>
设定机头归边使能。<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，显示红色字体，按Enter键切换打开、关闭状态。<br>
<font color=#FF0000>触摸</font>：触笔单击项目字符区，显示红色字体，再次单击切换打开、关闭状态。<br>
<font color=#FF0000>打开</font>：在编织时，每行可使机头跑到机身两边最远处（左、右限位设定点，忽略花样宽度）。<br>
<font color=#FF0000>关闭</font>：机头按花样宽度控制行程，回复正常生产。<br>
####  报警灯音量：<br>
设定报警灯的音量大小。<br>
范围：1 -10<br>
默认：0<br><br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。<br>

当设定值为默认值时，音量默认为10
####  报警持续时间：<br>
设定报警声所持续的时间。<br>
范围：0 - 600（秒）<br>
默认：0<br>
若设定0，则持续报警声直至关闭报警。<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。<br>

####  自动锁行：<br>
设定编织时是否自动行锁定。<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，显示红色字体，按Enter键切换打开、关闭状态。<br>
<font color=#FF0000>触摸</font>：触笔单击项目字符区，显示红色字体，再次单击切换打开、关闭状态。<br>
<font color=#FF0000>打开</font>：在编织时，执行行锁定。<br>
<font color=#FF0000>关闭</font>：在编织时，不执行行锁定。<br>
此项需要配合“工作参数”中的“最大锁行数”才能有效启用。若“最大锁行数”为0，自动锁行功能即使打开也无效。<br>
####  语言切换：<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键切换打开、关闭状态。<br>
<font color=#FF0000>触摸</font>：触笔单击项目字符区，再次单击切换打开、关闭状态。<br>

暂时提供简体中文版与美版，其他语系支持另行通知。<br>
####  加油控制配置：<br>
设定控制加油的方式。<br>
预设配置：根据系统配置设定来控制加油方式。<br>
主控加油：主控来控制加油<br>
机头加油：机头控制加油<br>
加油关闭：关闭加油<br>

<font color=#FF0000>按键</font>：方向键移动光标到指定位置，显示红色字体，按Enter键，弹出“加油控制配置”选择框，上、下键选择所需的类型，按Enter键结束，按Esc键退出选择。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，显示红色字体，再次单击弹出“加油控制配置”选择框，触笔双击所需的类型即可，触笔单击选择框退出选择。
####  日光灯配置：<br>
设定日光灯控制方式。<br>
预设配置：根据系统配置来设定日光灯控制方式。<br>
单灯输出：下灯按钮控制两个日光灯的开与关。<br>
双灯双控：两个开关分别控制两个日光灯。<br>
双灯单控：两个按钮依次日光灯的亮暗。<br>

<font color=#FF0000>按键</font>：方向键移动光标到指定位置，显示红色字体，按Enter键，弹出“日光灯配置”选择框，上、下键选择所需的类型，按Enter键结束，按Esc键退出选择。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，显示红色字体，再次单击弹出“日光灯配置”选择框，触笔双击所需的类型即可，触笔单击选择框退出选择。
####  翻针度目置零：<br>


<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键切换打开、关闭状态。<br>
<font color=#FF0000>触摸</font>：触笔单击项目字符区，再次单击切换打开、关闭状态。<br>
###  罗拉相关参数
####  主罗拉速比：<br>
设定步进主罗拉卷布速度比率。<br>
范围：1 - 16<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

数值大小与卷布速度成正比，数值越大，卷布越快

<font color=#FF0000>提醒！</font>根据横机机号大小及步进驱动器细分数调整，一般细分数设置大，马达运转平稳且运转噪声小，此时需调整卷布系数配合罗拉正常卷布。
####  副罗拉转动时间：<br>
设定副罗拉的转动时间。<br>
范围：1 - 500<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

### 选针器相关参数
####  选针器右行补偿：<br>
设定选针器右行时的补偿值，范围：[-79]－[+79] 。<br>
最小设定单位：0.1（针）<br>
为尽量减少按键次数，便于数值输入方便，设定数值放大10倍显示，即输入补偿数值5则实际为0.5针（实际设定=设定数值/10）。<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入数字、“+/-”符号键输入（负号），默认符号为正，负号输入可在数值输入前后都可，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，键入数字、“+/-”符号键输入（负号），默认符号为正，负号输入可在数值输入前后都可，单击确定键结束。

此参数设定选针器刀头右行编织时的提前、滞后量（针），对右行编织的所有选针器生效。

补偿正、负符号说明:<br>
＋ 正数表示工作刀头滞后工作<br>
－ 负数表示工作刀头提前工作
####  选针器左行补偿：<br>
设定选针器左行时的补偿值，范围：-79－+79 。<br>
操作及说明同选针器右行补偿。<br>

此参数设定选针器刀头左行编织时的提前、滞后量（针），对左行编织的所有选针器生效。<br>
####  选针器刀片个数：<br>
范围：3 - 8<br>
默认：8<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。<br>

选针器有3刀，8刀，10刀，根据用户所需自行选择
####  选针器重选：<br>
设定选针器是否打开重选节能功能。<br>
默认：打开<br>
关闭：复选节能（刀头全上至选针位）<br>
打开：复选工作（刀头参与选针动作）<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，显示红色字体，按Enter键切换打开、关闭状态。<br>
<font color=#FF0000>触摸</font>：触笔单击项目字符区，显示红色字体，再次单击切换打开、关闭状态。

####  选针器高压：<br>
设定选针器高压值（灵敏度）。<br>
范围：1 - 10<br>
默认：3<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

数值大小与灵敏度呈反比，数值越大，灵敏度越低。一般当选针器长时间使用后，请将此参数恰当调大一些。
  
### 度目电机参数
####  度目最大值：<br>
设定度目的通过电流<br>
范围：100 - 790<br>
默认：根据用户的电机规格自行变更<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。
####  密度马达复位速度：<br>
设定密度马达归零时复位速度。<br>
范围：1－10<br>
默认：4<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

此数值表示密度马达至零位传感器的时间百分比，数值越大，归零复位时间越短。
####  密度马达工作速度：<br>
设定密度马达到工作位置时速度。<br>
范围：1－10<br>
默认：6<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

此数值表示密度马达至工作位置时间的百分比，数值越大，时间越短。
####  度目检查设置：<br>
设定最大允许失步数。<br>
范围：0 - 200<br>
默认：0<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

用于检查失步报警。
###  摇床相关参数
####  摇床位置：<br>
设定横机摇床机构安装针板位置（前、后、后双）。<br>
前：前针板位移<br>
后：后针板位移<br>
后双：双后摇床电机<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，显示红色字体，按Enter键，弹出请输入密码框，输入对应密码“8888”后按Enter键，摇床位置进行变更。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，显示红色字体，再次单击弹出请输入密码框和软键盘，输入对应密码“8888”后单击确定键，摇床位置进行变更。

变更顺序为[前床]→[后床]→[后双]→[前床]

####  摇床间隙补偿：<br>
设定丝杆间隙补偿值。<br>
范围：0 - 999<br>
默认：0<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

####  摇床速度设定：<br>
设定摇床速度。<br>
范围：1-100<br>
默认：30<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

此参数数值大小与摇床速度成正比，数值越大，摇床速度越快。反之也然。
### 生克相关参数
####  生克有效：<br>
设定生克步进控制电机工作状态。<br>
打开：生克电机有效。<br>
关闭：生克电机无效。<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，显示红色字体，按Enter键切换打开、关闭状态。<br>
<font color=#FF0000>触摸</font>：触笔单击项目字符区，显示红色字体，再次单击切换打开、关闭状态。

此参数适用步进控制电机的生克机构。
####  生克提前：<br>
设定生克电机动作的提前量。<br>
范围：0 - 100<br>
默认：0<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

以编织区为基准，如果设定数值N，则生克电机将在出编织区之前提前动作
####  生克完成点：<br>
设定生克电机提前完成的针数<br>
范围：0 - 100<br>
默认：0<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

以编织区为基准，如果设定数值N，则生克电机将在出编织区之前完成动作。
####  生克速度：<br>
设定生克运行速度。<br>
范围：20 - 200<br>
默认：根据用户的电机规格自行变更<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。
####  生克最大值：<br>
设定生克最大行程数值。<br>
范围：100 - 5000<br>
默认：0<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。
####  生克数据模式：<br>
设定绝对位置：<br>
相对位置：<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，显示红色字体，按Enter键切换位置状态。<br>
<font color=#FF0000>触摸</font>：触笔单击项目字符区，显示红色字体，再次单击切换位置状态。

####  系统生克模式：<br>
设定生克的安装方式。<br>
生效：按系统标准进行装配<br>
关闭：按照用户所需自行装配<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，显示红色字体，按Enter键切换位置状态。<br>
<font color=#FF0000>触摸</font>：触笔单击项目字符区，显示红色字体，再次单击切换位置状态。
####  后沉降片复位：<br>
设定后沉降片步进控制电机在机头原点复位后与沉降片零位探头的距离值（脉冲）。<br>
范围：[-800] - [+800]<br>
默认：200 <br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

脉冲设定数大小与距离值成正比关系。 <br>
此参数适用步进电机驱动的生克控制机构。
####  前沉降片复位：<br>
设定前沉降片步进控制电机在机头原点复位后与沉降片零位探头的距离值（脉冲）。 <br>
范围：[-800] - [+800]<br>
默认：200 <br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

脉冲设定数大小与距离值成正比关系。 <br>
此参数适用步进电机驱动的生克控制机构。
### 可变度目参数
####  变大补偿左行：<br>
设定范围：[-9.9] - [+9.9]<br>
默认：0<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

####  变小补偿左行：<br>
设定范围：[-9.9] - [+9.9]<br>
默认：0<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

####  变大补偿右行：<br>
设定范围：[-9.9] - [+9.9]<br>
默认：0<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

####  变小补偿右行：<br>
设定范围：[-9.9] - [+9.9]<br>
默认：0<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

####  平移补偿：<br>
设定范围：[-9.9] - [+9.9]<br>
默认：0<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

### 探针相关参数
####  探针类型：<br>
设定探针的安装位置。<br>
配置默认：<br>
普通探针：普通模式探针<br>
前右后左：<br>
前左后右：<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，显示红色字体，按Enter键，弹出“探针类型”选择框，上、下键选择所需的类型，按Enter键结束，按Esc键退出选择。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，显示红色字体，再次单击弹出“探针类型”选择框，触笔双击所需的类型即可，触笔单击选择框退出选择。

####  左侧探针位置微调：<br>
设定探针的检测位置。<br>
范围：[-50] - [+50]<br>
默认：0<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

####  右侧探针位置微调：<br>
设定范围：[-50] - [+50]<br>
默认：0<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。

####  探针延时：<br>
设定探针报警延时时间。<br>
范围：0 - 600<br>
默认：0<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。 
### 起底板相关参数
####  卸片罗拉：<br>
设定卸片时罗拉转动速度的大小。<br>
默认：40<br>
范围：10--100<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。 
####  罗拉打开修正：<br>
设定罗拉打开时存在的误差。<br>
范围：0--500<br>
<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。 
### 网络相关参数
####  网络开关：<br>
设定是否开启联网功能。<br>

<font color=#FF0000>按键</font>：方向键移动光标到指定位置，显示红色字体，按Enter键切换打开、关闭状态。<br>
<font color=#FF0000>触摸</font>：触笔单击项目字符区，显示红色字体，再次单击切换打开、关闭状态。
####  本机IP：<br>
设定当前机器联网时这个机器的IP地址。<br>

<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。 
####  子网掩码：<br>
设定当前机器联网时的子网掩码。<br>

<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。 
####  网关设置：<br>
设定当前机器联网时的网关号。<br>

<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。 
####  服务器IP：<br>
设定当前机器连接的网络的服务器IP地址。<br>

<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。 
####  端口号：<br>
设定当前机器在监控设备中显示的端口号。<br>

<font color=#FF0000>按键</font>：方向键移动光标到指定位置，按Enter键，显示带红色下划线红色字体，键入修改值，按Enter键结束。<br>
<font color=#FF0000>触摸</font>：触笔单击项目数值区，再次单击弹出软键盘，显示带红色下划线红色字体，输入设定值，单击确定键结束。 
