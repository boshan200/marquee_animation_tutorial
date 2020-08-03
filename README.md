使用html加上css製作跑馬燈動畫

======================================
1. 首先將 html tag <marquee> 放到跑馬燈所在的DOM節點裡頭
EX: HTML TAG長這樣:
<!-- HTML Code -->
<marquee class="marquee" direction="left" scrollamount="50" behavior="scroll">Scrolling text...</marquee>

HTML屬性說明:
* class:讓此html tag可以藉由這個屬性受到css語法操控
* direction:控制此動畫移動的方向
* scrollamount:控制動畫移動的速度 (1~100數字越大越快)
* behavior:動畫的行為 (有scroll、alternate、slide三種)
=======================================

2. 再來將css語法放入HEAD裡頭即可完成操作

EX: CSS 語法範例:
<style type="text/css" scoped>
.marquee {
font-family:'Comic Sans MS';
font-size:2em;
line-height:1.3em;
color:#330099;
background-color:#CCFFFF;
padding:1.5em;
}
</style>

css屬性說明:
* font-family:控制字型
* font-size:字體大小
* line-height:字體高度 (在此高度分成兩種單位:px以及em, em是一個浮動單位取決於他的父節點的字體大小。比如父節點的字體大小是10px，那麼0.5em就是5px。)
* color:字體顏色，使用16進位編碼來表示
* background-color:背景顏色，表示方式同color
* padding:圍繞字體的空白處



