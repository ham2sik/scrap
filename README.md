scrap
========================

```html
<script type="text/javascript" src="http://its.jobkorea.kr/content/js/lazyUIT.min.js"></script>
<script>
	$(window).load(function() {
		// lazyUIT.js(url, callback function);
		lazyUIT.js("http://m.jobkorea.co.kr/include/js/swiper.min_3.3.1.js", function() {
			var swiperEvent = new Swiper('#event .swiper-container', {
				slidesPerView: 'auto',
				freeMode: true,
				onTouchMove : function(swiper) {
					lazyUIT.render();
				}
			});
		});
	});
</script>
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
