---
layout: post
title: Ancient ideas and thoughts of the ET Programming Language
---

Here I want to tell from the past.
It's about a some of years ago.

When there was an Android operating system.

I suppose this was for before **2015**.

![App Icon](https://basemax.github.io/assets/image/icon.png)


### A sample project using this technology :


index.design :
```html
<app>
	<page>
		<title>Main</title>
		<style url="main.style">
		<toolbar="true">
		<theme="...">
	</page>
	<content>
		<items layout="index_row.design" style="#listview"/>
	</content>
</app>
```

index.script :
```html
<load>
	<net_get src="http://site.com/news.json" save="data">
	<json_decode input=$data save="input">
	<items target="#listview">
		<list $input = $item>
			<item_add input=[
							 "image":$item['image']
							 ,
							 "title":$item['title']
							 ,
							 "text":$item['text']
							]>
		</list>
	</items>
</load>
```

index_row.design :
```html
<box style="#item">
	<box style="#left">
		<image style="#image">
	</box>
	<box style="#right">
		<label style="#title" size="20px">
		<label style="#text" size="16px">
	</box>
</box>
```



main.style :
```html
<style>
	<item #listview>
		<padding="10px">
		<background="red">
	</item>
</style>
```


setting.android :
```html
<app>
	<name="Name Of App">
	<package="com.mypcname.appname">
	<icon="icon.png">
	<sdk="18">
</app>
```


