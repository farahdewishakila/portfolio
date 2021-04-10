# 📚 GSAP Documentation
Here's the documentation of my portfolio project.

## 💡 Basic of GSAP
There’s three basic function to animate element with GSAP:
 
 1. GSAP from
	 ```js
	gsap.from(".target", {condition});
	```
	To animate an element from the conditions inside our GSAP function to the 	condition in our CSS. Here’s the example: [Codepen Link](https://codepen.io/sweetcheeses/pen/YzNpoob)
	
	So in that case, we animated the element with class “box” from 0 width (condition inside our function) to 200px width (condition in our CSS) with 1s of duration.

2. GSAP to
	 ```js
	gsap.to(".target", {condition});
	```
	To animate an element from the condition that we’ve write in our CSS to the condition inside our GSAP function. Here’s the example: [Codepen Link](https://codepen.io/sweetcheeses/pen/zYNogPy)

3. GSAP fromTo
	```js
	gsap.fromTo(".target", {From condition}, {To condition});
	```
	This function needs ‘from’ and ‘to’ condition inside our GSAP function. Here's the code example: [Codepen Link](https://codepen.io/sweetcheeses/pen/WNRoVzX)

## 🤓 Learning Source

Here's video tutorials that I’ve learned from before. I hope it will help to understand.

| Videos | Uploader |
|--|--|
| [Create Awesome Animations With Javascript](https://www.youtube.com/watch?v=5RyrIPCs47A) | Dev Ed |
| [GSAP 3.0 Crash Course](https://www.youtube.com/watch?v=YqOhQWbouCE) | DesignCourse |
| [Learn GSAP In 23 Minutes](https://www.youtube.com/watch?v=m6PDUIF24v4) | Kyle |
| [GSAP's NEW ScrollTrigger Plugin! -Tutorial](https://www.youtube.com/watch?v=ygcEKd0RIGg) | DesignCourse |
| [Introducing ScrollTrigger for GSAP](https://www.youtube.com/watch?v=X7IBa7vZjmo) | GSAP |
| [Advanced stagger effects in GSAP 3](https://www.youtube.com/watch?v=wDnUtY5KcOc) | GSAP |