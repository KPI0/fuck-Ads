### 1.随机数
------------------------------------------------------------------------------------------------------------------------------------------------------
##### 元素选择器模式
m.ijjxs.com###\34 26241 > .pd6   
m.ijjxs.com###\31 45461 > .pd6   
m.ijjxs.com###\32 61021 > .pd6   
m.ijjxs.com###\32 61022 > .pd6   
##### 审查元素
```
<div class="pd6">小提示：请记录收藏本站最新网址 ijjxs.com，以便在打不开网站的情况下手动输入网址访问。</div>
```
通用规则
```
m.ijjxs.com##div[class="pd6"]
```
-------------------------------------------------------------------------------------------------------------------------------------------------------
##### 元素选择器模式
www.veidc.com##div.widget_custom_html.widget.widget-on-phone.widget_text:nth-of-type(1)
www.veidc.com##div.widget_custom_html.widget.widget-on-phone.widget_text:nth-of-type(2)
www.veidc.com##div.widget_custom_html.widget.widget-on-phone.widget_text:nth-of-type(3)
www.veidc.com##div.widget_custom_html.widget.widget-on-phone.widget_text:nth-of-type(4)
##### 审查元素
```
<div class="widget_text widget-on-phone widget widget_custom_html">
<div class="textwidget custom-html-widget">
```
通用规则
```
www.veidc.com##div[class="textwidget custom-html-widget"]
www.veidc.com##div[class="widget_text widget-on-phone widget widget_custom_html"]
```
或者
```
www.veidc.com##div.widget_custom_html.widget.widget-on-phone.widget_text:nth-of-type(n)
```
-------------------------------------------------------------------------------------------------------------------------------------------------------
##### 审查元素
```
<div class="bmqvwHLQ"style="line-height: 115px; top: 0px; left: 0px; z-index: 1211; width: 100vw; background: url("https://91zsri0.sanso.hk/MTMyMA13201320/0402/1585822437.gif91zsri0.sanso.hk/MTMyMA13201320/1023/1571821329.gif") 0px 0px / 100vw 115px no-repeat;">    
<div class="berxzCJY"style="line-height: 115px; top: 0px; left: 0px; z-index: 1211; width: 100vw; background: url("https://91zsri0.sanso.hk/MTMyMg13221322/0402/1585822374.gif") 0px 0px / 100vw 115px no-repeat;">   
<div class="hlowzSTZ"style="line-height: 115px; top: 0px; left: 0px; z-index: 1211; width: 100vw; background: url("https://91zsri0.sanso.hk/MTMyMw13231323/0323/1648011591.gif") 0px 0px / 100vw 115px no-repeat;">
```
通用规则  
```
##div[style*="z-index: 1211"]
```
--------------------------------------------------------------------------------------------------------------------------------------------------------
##### 元素选择器模式
i.ifeng.com##.share_items-1SYjHZrS    
i.ifeng.com##.share_items-2SfbdZr8   
i.ifeng.com##.share_items-3SrjHZrr    
通用规则
```
i.ifeng.com##[class^="share_items"]:nth-ancestor(1)
```
------------------------------------------------------------------------------------------------------------------------------------------------------
