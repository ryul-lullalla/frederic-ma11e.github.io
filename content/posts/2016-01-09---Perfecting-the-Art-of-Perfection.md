---
title: Javascript How to write function in ES5/ES6
date: "2019-10-08T23:46:37.121Z"
template: "post"
draft: false
slug: "/posts/wecode-javascript-day9/"
category: "Pre-course"
tags:
  - "function in Javascript"
  - "differences between ES5 and ES6"
description:


 # ES5와 ES6 함수 표현식/선언문 차이


 - 예제 
	 - 이름없는 함수 (선언문)
		 - ES5 ```function () {} == Es 6 () => {}```
	 - 표현식
		 - ES5 ```const getName = function() {}   ```
		 - ES6 ```const getName = () => {}```
		 - ES5 ```const getName = function(lastname){}```
		 - ES6 ```const getName = lastname => {}```
 
 - 응용 예제 1
	 - ES5 ```function getName (lastname) {}  ```
	 - ES6 ```const getName = (lastname) {}```
	 - == ```const getName = last name => {}```
 - 응용 예제 2
	 - ES5 ```function getName (lastname) { return name;}```
	 - ES6 ```getName = (lastname) => {return name;}```
	 - ==    ```getName = lastname => name;```
 - 응용 예제 3
	 - ES5 ```const getName= function(last name) { return name;} ```
	 - Es6 ``` const getName = lastname => name;```
	 
socialImage: "/media/image-2.jpg"
---
**Pellentesque habitant morbi tristique** senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. *Aenean ultricies mi vitae est.* Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. 

Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui.  [Donec non enim](#) in turpis pulvinar facilisis.

![Nulla faucibus vestibulum eros in tempus. Vestibulum tempor imperdiet velit nec dapibus](/media/image-0.jpg)

## Header Level 2

+ Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
+ Aliquam tincidunt mauris eu risus.

Donec non enim in turpis pulvinar facilisis. Ut felis. Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, eu vulputate magna eros eu erat. Aliquam erat volutpat. 

<figure>
	<blockquote>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus magna. Cras in mi at felis aliquet congue. Ut a est eget ligula molestie gravida. Curabitur massa. Donec eleifend, libero at sagittis mollis, tellus est malesuada tellus, at luctus turpis elit sit amet quam. Vivamus pretium ornare est.</p>
		<footer>
			<cite>— Aliquam tincidunt mauris eu risus.</cite>
		</footer>
	</blockquote>
</figure>

### Header Level 3

+ Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
+ Aliquam tincidunt mauris eu risus.

Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra.

```css
#header h1 a {
  display: block;
  width: 300px;
  height: 80px;
}
```

Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enim in turpis pulvinar facilisis. Ut felis. Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, eu vulputate magna eros eu erat. Aliquam erat volutpat. Nam dui mi, tincidunt quis, accumsan porttitor, facilisis luctus, metus.