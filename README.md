scrap
========================
```html
<body>

	<script src="moni.pc.min.js"></script>
	<script>
		$(window).load(function() {
			moni.lazy.image({
				offset: 100,
				callback: function (element, op) {
					console.log(element, 'has been loaded')
				}
			});
		});
	</script>
</body>
```

window.history
---------------
* https://developer.mozilla.org/ko/docs/Web/API/History_API
* https://opentutorials.org/module/2398/13938

Promise
---------------
* http://han41858.tistory.com/11
* http://bluebirdjs.com/
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/all

React
---------------
* https://velopert.com/775

Plugin
---------------
* http://idangero.us/swiper/api/
* http://momentjs.com/

Mobile
---------------
* web devices capabilities : http://mydevice.io/

HTML5 LocalStorage
---------------
* http://ohgyun.com/417

코드압축
---------------
* https://perfectacle.github.io/2017/04/18/webpack2-optimize/
* https://vnthf.github.io/blog/Front-Gzip%EC%97%90-%EA%B4%80%ED%95%98%EC%97%AC/

JS Browse Test
---------------
* https://jsperf.com/browse
