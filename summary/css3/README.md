# 重要模块


# **选择器**

## **~**

> 设置同一父元素下的 div 元素之后的每一个 p 元素的字体大小

~~~css
div~p{
	font-size:14px
}
~~~

## **[class^="test"]**

> 设置class属性值以"test"开头的所有div字体大小

~~~css
div[class^="test"]{
	font-size:14px
}
~~~

## [class$="test"]

> 设置class属性值以"test"结尾的所有div字体大小

~~~css
div[class$="test"]{
	font-size:14px
}
~~~

## [class*="test"]

> 设置class属性值以"test"所有div字体大小

~~~css
div[class*="test"]{
	font-size:14px
}
~~~

## div:first-of-type

> 选择的 div 元素是其父元素的第一个 div 元素

~~~css
div:first-of-type{
	font-size:14px
}
~~~

## div:last-of-type

> 选择的 div 元素是其父元素的最后一个 div 元素

~~~css
div:last-of-type{
	font-size:14px
}
~~~

## div:only-of-type

> 指定属于父元素的特定类型的唯一子元素的div 元素

~~~css
div:only-of-type{
	font-size:14px
}
~~~

## div:only-child

> 指定属于父元素的特定类型的唯一子元素的div 元素

~~~css
div:only-child{
	font-size:14px
}
~~~

## div:nth-child(n)

> 选择每个div元素是其父级的第n个子元素

~~~css
div:nth-child(n){
	font-size:14px
}
~~~

## div:nth-last-child(n)

> 选择每个div元素的是其父级的第n个子元素，从最后一个子项计数

~~~css
div:nth-last-child(n){
	font-size:14px
}
~~~

## div:nth-of-type(n)

> 选择每个div元素是其父级的第n个div元素

~~~css
div:nth-of-type{
	font-size:14px
}
~~~

## div:nth-last-of-type(n)

> 选择每个div元素的是其父级的第n个div元素，从最后一个子项计数

~~~css
div:nth-last-of-type{
	font-size:14px
}
~~~

## div:last-child

> 选择每个div元素是其父级的最后一个子级。

~~~css
div:last-child{
	font-size:14px
}
~~~

## div:root

> 选择文档的根元素

~~~css
:root{
	font-size:14px
}
~~~

## div:empty

> 选择每个没有任何子级的n元素（包括文本节点）

~~~css
n:empty{
	font-size:14px
}
~~~

## div:target

> 选择当前活动的n元素（包含该锚名称的点击的URL）

~~~css
n:target{
	font-size:14px
}
~~~

## div:enabled

> 选择每一个已启用的输入元素）

~~~css
n:enabled{
	font-size:14px
}
~~~

## div:disabled

> 选择每一个禁用的输入元素

~~~css
n:disabled{
	font-size:14px
}
~~~

## div:checked

> 选择每个选中的输入元素

~~~css
n:checked{
	font-size:14px
}
~~~

## div:not(n)

>  选择每个并非n元素的元素

~~~css
:not(n){
	font-size:14px
}
~~~

## div::selection

> 匹配元素中被用户选中或处于高亮状态的部分

~~~css
::selection{
	font-size:14px
}
~~~

## div:out-of-range

> 匹配值在指定区间之外的input元素

~~~css
input:out-of-range{
	font-size:14px
}
~~~

## div:in-range

> 匹配值在指定区间之内的input元素

~~~css
input:in-range{
	font-size:14px
}
~~~

## div:read-only

> 用于匹配设置 "readonly"（只读） 属性的元素

~~~css
input:read-only{
	font-size:14px
}
~~~

## div:read-write

> 用于匹配可读及可写的元素

~~~css
input:read-write{
	font-size:14px
}
~~~

## div:optional

>  用于匹配可选的输入元素

~~~css
input:optional{
	font-size:14px
}
~~~

## div:vaild

>  用于匹配输入值为合法的元素

~~~css
input:vaild{
	font-size:14px
}
~~~

## div:invaild

> 用于匹配输入值为非法的元素

~~~css
input:invaild{
	font-size:14px
}
~~~













