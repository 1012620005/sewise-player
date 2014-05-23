# [Sewise Player](http://player.sewise.com/) : HTML5 Video Player

Support for [jQuery](http://jquery.com/) HTML player skins.


## What is Sewise Player?


### Sewise Player��һ��רҵ�������ҳ��Ƶ������������������ǿ�����С����ƽ̨��ʹ�÷����ࡢ����������
* ����������Ҫ��HTML5����Ϊƽ̨������ͬʱ����flash������ʵ���˿�ƽ̨����������ݵ���Ƶ���š�ʹ��Sewise Player��������Windows, MacOS, Linux��Windows Phone, Android, IOS������ƽ̨�ϣ�ͨ����Ӧ�������������Ƶ��
* Sewise Playerʹ�÷ǳ��򵥣�ֻҪ��ҳ���Ӧ��DIV��Ƕ��һ��JS�ļ����ɣ���������ͨ���Զ�ʶ��������Ĺ���������HTML5��flashģʽ������Ƶ��������Ҫ�����κ�JavaScript��ActionScript���뼼���Ϳ���������רҵ����ҳ��Ƶ��������
* Sewise Player��������Ϊ��һ��ǰ̨����������ҳ���ϲ�����Ƶ������Ҳ���Խ��Sewise Server��̨����ʵ��רҵ�Ŀɽ����ĵ㲥��ֱ����Ƶ���š�


### �����б�
* ֧��HTML5��Flash��Ƶ���ż�����
* ֧�ֶ�ƽ̨��PC����Windows, MacOS, Linux�ȡ�Mobile����Android, IOS, Windows Phone�ȡ�
* ֧�ֶ���������ݣ���IE6/7/8/9/10��Google Chrome��Firefox��safari��Opera�ȡ�
* ֧�ֶ�����Ƶ��ʽ����mp4��m3u8��oga��webm��theora��flv��f4v�ȡ�
* ֧�ֶ���Э��ֱ��������rtmp��udp��http ts��rtsp�ȡ�
* ֧��Flash����m3u8�ļ����Լ�AES-128���벥�š�
* ֧��PC��Mobileƽ̨�������Զ�ʶ���ܡ�
* ֧�������HTML5��Flash���Լ�⡣
* ֧�ֲ��ŵ�ַAMF, AJAX, JOSNP��������
* ֧���Զ���HTML5��FlashƤ�������������˽�רҵ�ı��뼼��Ҳ������������������Ƥ����
* ֧��ǰ�ù�棨swf, ͼƬ, ��Ƶ����
* ֧����Ļ��
* ֧�ֶ��ֲ��Ų����趨����֧�������������á�
* ֧�ַḻ��api�ӿڣ��Դ˿��Կ��ٴ��칦��ǿ��Ĳ����


### �ļ����ܣ�
* sewise.player.min.js���������ļ���
* html��HTML5Ƥ��Ŀ¼��
* html\skins\vodWhite, HTML5�㲥��ɫƤ��Ŀ¼��
* html\skins\vodWhite\skin.html, HTML5�㲥��ɫƤ��DomԪ�ء�
* html\skins\vodWhite\skin.html.js, HTML5�㲥��ɫƤ��DomԪ�ض������ڼ��ݿ�����ء�
* html\skins\vodWhite\skin.css, HTML5�㲥��ɫƤ��CSS��ʽ��
* html\skins\vodWhite\skin.js, HTML5�㲥��ɫƤ��JS�߼����롣
* flash, flash������Ŀ¼��
* flash\SewisePlayer.swf�� Flash���������ļ���
* flash\skins, FlashƤ��Ŀ¼��
* flash\skins\vodWhite.swf, Flash�㲥��ɫƤ����
* flash\skins\liveWhite.swf, Flashֱ����ɫƤ����
* flash\skins\vodOrange.swf, Flash�㲥��ɫƤ����
* flash\skins\liveOrange.swf, Flashֱ����ɫƤ����


### ҳ�沥����Ƕ�뷽ʽ��
* �㲥��ʵ�ʵ�ַ���š�
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="../player/sewise.player.min.js?server=vod&type=mp4&videourl=http://www.w3schools.com/html/mov_bbb.mp4&sourceid=&autostart=true&starttime=0&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=VodVideo&buffer=5&skin=vodWhite"></script>
</div>
```

* �㲥����ĿID���š�
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="http://219.232.161.202/libs/swfplayer/player/sewise.player.min.js?server=vod&sourceid=eQgPHj4N&autostart=true&starttime=0&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&buffer=5&skin=vodWhite"></script>
</div>
```

* ֱ����ʵ�ʵ�ַ���š�
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="../player/sewise.player.min.js?server=live&type=rtmp&streamurl=rtmp://219.232.161.204/livestream/mtzysunq&autostart=true&pid=&shifttime=&buffer=5&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=LiveVideo&skin=liveWhite"></script>
</div>
```

* ֱ������ĿID���š�
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="http://219.232.161.204/libs/swfplayer/player/sewise.player.min.js?server=live&autostart=true&pid=vk5nx2cj&shifttime=&buffer=5&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&skin=liveWhite"></script>
</div>
```


### ����������ԭ��:
* ��һ����ҳ�����sewise.player.min.js�ļ��󣬸ýű��Ὣ��Ӧ�Ĳ���������������������ǰ���豸ƽ̨����������ԣ�ͬʱ�������JS�ļ���·��ȡ��host��ַ�����ڲ��ŵ�ַ����
* �ڶ�����ͨ������������vod��type�����뼰��������ԣ���ȷ��������������HTML5����Flashģ�顣���ڲ�ͬƽ̨�������ͬʱ֧�ֵ���Ƶ��ʽ����Э�飬����������HTML5����ģ�顣
* �����������ض�Ӧ��Ƥ���ļ�����ļ���
* ���Ĳ�����Ƥ��������ɺ󽫸��ݸ����Ĳ�������ʼ������������������ʼ����ɺ󣬿�ʼ������Ƶ����ͬʱ���ڵ�ǰҳ���лص�playerReady()��HTML5��Flash����������ص�playerReady��������ʾ������API�ӿ��ѿ��ã�����Ӧ�Ĳ������ص�������


### ������������
* Sewise Player�������ṩ�����Ĳ������ù��ܣ�ͨ�����ò�ͬ�Ĳ���ֵ�����ò��������в�ͬ�Ĳ������ԡ�
* ��ϸ����˵��������[����˵��.md](docs/����˵��.md)�ļ���


### ������Ƥ����
* Sewise Player������Ƥ����Ϊ�����֣���HTML5��FlashƤ����
* HTML5Ƥ����HTML��CSS��JS�ļ����ɣ�һ���ļ�Ŀ¼��Ӧһ��Ƥ����
* FlashƤ����SWF�ļ����ɣ�һ��SWF�ļ���Ӧһ��Ƥ����
* HTML5��FlashƤ�����÷�����ͬ��ֻҪ������skin����Ϊ��Ӧ��Ƥ��������skin=vodWhite��ʾ��ɫ�㲥Ƥ����
* HTML5��FlashƤ����Դ�����ѿ��ţ���[source](source)Ŀ¼��


### API�ӿڵ��ã�
* Sewise Player�����������ṩ�˷ḻ��API�ӿڣ�ͨ��API�ӿڵ��ÿ������ɿ��Ʋ��������š�
* ��ϸ�ӿ�˵��������[�ӿ�˵��.md](docs/�ӿ�˵��.md)�ļ���
* �㲥�ӿ�
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="../player/sewise.player.min.js?server=vod&type=mp4&videourl=http://www.w3schools.com/html/mov_bbb.mp4&sourceid=&autostart=true&starttime=0&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=VodVideo �㲥����&buffer=5&skin=vodWhite&fallbackurls=%7B%0A%09%22ogg%22%3A%20%22http%3A%2F%2Fwww.w3schools.com%2Fhtml%2Fmov_bbb.ogg%22%2C%0A%09%22webm%22%3A%20%22http%3A%2F%2Fwww.w3schools.com%2Fhtml%2Fmov_bbb.webm%22%0A%7D"></script>
</div>
<script>
	//�㲥�ӿڵ��÷���
	function startPlay(){
		SewisePlayer.doPlay();
	}
	function playPause(){
		SewisePlayer.doPause();
	}
	function seekTo(){
		SewisePlayer.doSeek(5);
	}
	function playStop(){
		SewisePlayer.doStop();
	}
	function changeVolume(){
		SewisePlayer.setVolume(0.1);
	}
	function getDuration(){
		alert(SewisePlayer.duration());
	}
	function getPlayTime(){
		alert(SewisePlayer.playTime());
	}
	// function switchProgram(){
	// 	SewisePlayer.playProgram("xqfa3cZn", 0, true);
	// }
	function switchVideo(){
		SewisePlayer.toPlay("http://media.w3.org/2010/05/sintel/trailer.mp4", "Sintel", 0, true);
	}

	//�������ص�����
	function playerReady(name){
		console.log("Sewise Player On Ready");
		//SewisePlayer.toPlay("http://www.w3school.com.cn/i/movie.mp4", "title", 0, false);
	}
	function onStart(name){
        console.log("onStart");
	}
	function onStop(name){
		 console.log("onStop");
	}
	function onMetadata(meta, name){
		console.log("onMetadata");
	}
	function onClarity(clarity, name){
		console.log("onClarity");
	}
	function onPause(name){
		console.log("onPause");
	}
	function onSeek(time, name){
		console.log("onSeek: " + time);
	}
	function onPlayTime(time, name){
		console.log("onPlayTime: " + time);
	}
</script>
<div style="padding-top: 20px;">
	<div style="padding-right: 20px;float: left;">[�㲥�ӿ�]</div>
	<div style="padding-right: 20px;float: left;"><a href="javascript:startPlay();">����</a></div>
	<div style="padding-right: 20px;float: left;"><a href="javascript:playPause();">��ͣ</a></div>
	<div style="padding-right: 20px;float: left;"><a href="javascript:seekTo();">��ת</a></div>
	<div style="padding-right: 20px;float: left;"><a href="javascript:playStop();">ֹͣ</a></div>
	<div style="padding-right: 20px;float: left;"><a href="javascript:changeVolume();">��������</a></div>
	<div style="padding-right: 20px;float: left;"><a href="javascript:getDuration();">��ȡ��ʱ��</a></div>
	<div style="padding-right: 20px;float: left;"><a href="javascript:getPlayTime();">��ȡ��ǰʱ��</a></div>
	<!-- <div style="padding-right: 20px;float: left;"><a href="javascript:switchProgram();">�л���Ŀ</a></div> -->
	<div style="padding-right: 20px;float: left;"><a href="javascript:switchVideo();">�л���Ƶ</a></div>
	<br clear="all"/>
</div>
```
���ӣ�[demos/vod_api.html](demos/vod_api.html)

* ֱ���ӿ�
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="http://219.232.161.204/libs/swfplayer/player/sewise.player.min.js?server=live&autostart=true&pid=vk5nx2cj
&shifttime=&buffer=5&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&skin=liveWhite"></script>
</div>
<script>
	//ֱ���ӿڵ��÷���
	function startPlay(){
		SewisePlayer.doPlay();
	}
	function playPause(){
		SewisePlayer.doPause();
	}
	function seekTo(){
		SewisePlayer.doSeek("20140224160520");
	}
	function playStop(){
		SewisePlayer.doStop();
	}
	function livePlay(){
		SewisePlayer.doLive();
	}
	function changeVolume(){
		SewisePlayer.setVolume(0.3);
	}
	function getLiveTime(){
		alert(SewisePlayer.liveTime());
	}
	function getPlayTime() {
		alert(SewisePlayer.playTime());
	}
	function switchChannel(){
		SewisePlayer.playChannel("br9anah3", "", true);
	}
	function switchStream(){
		SewisePlayer.toPlay("rtmp://192.168.1.219/livestream/7gw3yt3h", "title", "", true);
	}
	
	//�������ص�����
	function playerReady(name){
		console.log("Sewise Player On Ready");
		//SewisePlayer.toPlay("http://www.w3school.com.cn/i/movie.mp4", "title", 0, false);
	}
	function onStart(name){
        console.log("onStart");
	}
	function onStop(name){
		 console.log("onStop");
	}
	function onMetadata(meta, name){
		console.log("onMetadata");
	}
	function onClarity(clarity, name){
		console.log("onClarity");
	}
	function onPause(name){
		console.log("onPause");
	}
	function onSeek(time, name){
		console.log("onSeek: " + time);
	}
	function onPlayTime(time, name){
		console.log("onPlayTime: " + time);
	}
</script>
<div style="padding-top: 20px;">
	<div style="padding-right: 15px;float: left;">[ֱ���ӿ�]</div>
	<div style="padding-right: 15px;float: left;"><a href="javascript:startPlay();">����</a></div>
	<div style="padding-right: 15px;float: left;"><a href="javascript:playPause();">��ͣ</a></div>
	<div style="padding-right: 15px;float: left;"><a href="javascript:seekTo();">��ת</a></div>
	<div style="padding-right: 15px;float: left;"><a href="javascript:playStop();">ֹͣ</a></div>
	<div style="padding-right: 15px;float: left;"><a href="javascript:livePlay();">ֱ��</a></div>
	<div style="padding-right: 15px;float: left;"><a href="javascript:changeVolume();">��������</a></div>
	<div style="padding-right: 15px;float: left;"><a href="javascript:getLiveTime();">ֱ��ʱ��</a></div>
	<div style="padding-right: 15px;float: left;"><a href="javascript:getPlayTime();">����ʱ��</a></div>
	<div style="padding-right: 15px;float: left;"><a href="javascript:switchChannel();">�л�Ƶ��</a></div>
	<div style="padding-right: 15px;float: left;"><a href="javascript:switchStream();">�л���</a></div>
	<br clear="all"/>
</div>
```
���ӣ�[demos/live_api.html](demos/live_api.html)


### Demos��
* �㲥MP4��Ƶ����
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="../player/sewise.player.min.js?server=vod&type=mp4&videourl=http://www.w3schools.com/html/mov_bbb.mp4&sourceid=&autostart=true&starttime=0&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=VodVideo&buffer=5&skin=vodWhite&fallbackurls=%7B%0A%09%22ogg%22%3A%20%22http%3A%2F%2Fwww.w3schools.com%2Fhtml%2Fmov_bbb.ogg%22%2C%0A%09%22webm%22%3A%20%22http%3A%2F%2Fwww.w3schools.com%2Fhtml%2Fmov_bbb.webm%22%0A%7D"></script>
</div>
```
���ӣ�[demos/vod_videourl_mp4.html](demos/vod_videourl_mp4.html)

* �㲥FLV��Ƶ����
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="../player/sewise.player.min.js?server=vod&type=flv&videourl=http://219.232.161.202:5080/flvseek/data/userdata/vod/resource/201402/OVNNwRk1.flv&sourceid=&autostart=true&starttime=0&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=Vod-FLV&buffer=5&skin=vodOrange"></script>
</div>
```
���ӣ�[demos/vod_videourl_flv.html](demos/vod_videourl_flv.html)

* �㲥��ĿID��Ƶ����
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="http://219.232.161.202/libs/swfplayer/player/sewise.player.min.js?server=vod&sourceid=eQgPHj4N&autostart=true&starttime=0&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&buffer=5&skin=vodWhite"></script>
</div>
```
���ӣ�[demos/vod_sourceid.html](demos/vod_sourceid.html)

* ֱ��RTMP������
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="../player/sewise.player.min.js?server=live&type=rtmp&streamurl=rtmp://219.232.161.204/livestream/mtzysunq&autostart=true&pid=&shifttime=&buffer=5&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=LiveVideo&skin=liveWhite"></script>
</div>
```
���ӣ�[demos/live_streamurl_rtmp.html](demos/live_streamurl_rtmp.html)

* ֱ��HTTP������
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="../player/sewise.player.min.js?server=live&type=http&streamurl=http://219.232.161.204:5080/livestream/mtzysunq.flv&autostart=true&pid=&shifttime=&buffer=5&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=LiveVideo&skin=liveOrange"></script>
</div>
```
���ӣ�[demos/live_streamurl_http.html](demos/live_streamurl_http.html)

* ֱ����ĿID����
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="http://219.232.161.204/libs/swfplayer/player/sewise.player.min.js?server=live&autostart=true&pid=vk5nx2cj&shifttime=&buffer=5&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&skin=liveWhite"></script>
</div>
```
���ӣ�[demos/live_pid.html](demos/live_pid.html)

* Flash m3u8����
```html
<div style="width: 600px;height: 400px;">
	<script type="text/javascript" src="../player/sewise.player.min.js?server=vod&type=m3u8&videourl=http://www.codecomposer.net/hls/playlist.m3u8&sourceid=&autostart=true&starttime=0&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=Play-M3u8&buffer=5&claritybutton=disable&skin=vodWhite"></script>
</div>
```
���ӣ�[demos/flash_m3u8.html](demos/flash_m3u8.html)

* Flash m3u8 AES-128���벥��
```html
<div style="width: 600px;height: 400px;">
	<script type="text/javascript" src="../player/sewise.player.min.js?server=vod&type=m3u8&videourl=http://playertest.longtailvideo.com/adaptive/customIV/prog_index.m3u8&sourceid=&autostart=true&starttime=0&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=Play-AES-M3u8&buffer=5&claritybutton=disable&skin=vodWhite"></script>
</div>
```
���ӣ�[demos/flash_m3u8_aes_128.html](demos/flash_m3u8_aes_128.html)

* ������������ģʽ
```html
<div style="width: 640px; height: 360px; ">
	<!-- 1.���ݸ�����Ƶ��ַ���� -->
	<script type="text/javascript" src="../player/sewise.player.min.js"></script>
	<script type="text/javascript">
		SewisePlayer.setup({
			server: "vod",
			type: "mp4",
			title:"Tile ����",
			videourl: "http://www.w3schools.com/html/mov_bbb.mp4",
		       skin: "vodWhite"
		});
	</script>

	<!-- 2.���ݸ�����Ƶ��ĿID���� -->
	<!-- <script type="text/javascript" src="http://192.168.1.24/player/sewise.player.min.js"></script>
	<script type="text/javascript">
		SewisePlayer.setup({
			sourceid: "uWHj4JDB",
			server: "vod",
		    skin: "vodWhite",
		    fallbackurls:{
				ogg: "http://www.w3schools.com/html/mov_bbb.ogg",
				webm: "http://www.w3schools.com/html/mov_bbb.webm"
			}
		});
	</script> -->
</div>
```
���ӣ�[demos/setup_parameters.html](demos/setup_parameters.html)

* HTML5���Ż��˼��ݵ�ַ
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="../player/sewise.player.min.js"></script>
	<script type="text/javascript">
		SewisePlayer.setup({
			server: "vod",
			type: "mp4",
			videourl: "http://www.w3schools.com/html/mov_bbb.mp4",
		    skin: "vodWhite",
		    fallbackurls:{
			ogg: "http://www.w3schools.com/html/mov_bbb.ogg",
			webm: "http://www.w3schools.com/html/mov_bbb.webm"
			}
		});
	</script>
</div>
```
���ӣ�[demos/fallback_url.html](demos/fallback_url.html)

* Flash����HTML5���ݵ�ַ����
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="../player/sewise.player.min.js"></script>
	<script type="text/javascript">
		SewisePlayer.setup({
			server: "vod",
			type: "flv",
			videourl: "http://219.232.161.202:5080/flvseek/data/userdata/vod/resource/201402/OVNNwRk1.flv",
	        skin: "vodWhite",
	        claritybutton: "false",
			title: "flash fallback html5 ���ݵ�ַ����",
	        fallbackurls:{
				mp4: "http://www.w3schools.com/html/mov_bbb.mp4",
        		ogg: "http://www.w3schools.com/html/mov_bbb.ogg",
				webm: "http://www.w3schools.com/html/mov_bbb.webm"
			}
		});
	</script>
</div>
```
���ӣ�[demos/flash_fallback_html5.html](demos/flash_fallback_html5.html)

* ��Ƶ����
```html
<div style="width: 250px; height: 30px; ">
	<script type="text/javascript" src="../player/sewise.player.min.js"></script>
	<script type="text/javascript">
		SewisePlayer.setup({
			server: "vod",
			type: "mp3",
			videourl: "http://www.html5rocks.com/en/tutorials/audio/quick/test.mp3",
	        fallbackurls:{
        		ogg: "http://www.html5rocks.com/en/tutorials/audio/quick/test.ogg"
			}
		});
	</script>
</div>
```
���ӣ�[demos/audio.html](demos/audio.html)

* ʱ��Ƭ�ϲ���
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=0, minimum-scale=1.0, maximum-scale=1.0">
<title>Sewise Player</title>
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js"></script>
</head>
<body>
	<div>
		<div id="container" style="width: 650px; height: 360px; border: solid 1px #DDD"></div>
			<script type="text/javascript">
				var srcPath = "../player/sewise.player.min.js?server=vod&type=flv&autostart=true&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=VodVideo&buffer=5&skin=vodWhite";
				var videoUrl = "http://219.232.161.206:5080/flvseek/data/userdata/vismam/downfile/201307/02005220p.flv?starttime=100&endtime=150";
				var script = document.createElement('script');
				script.type = "text/javascript";
				script.src = srcPath + "&videourl=" + encodeURIComponent(videoUrl);
				$("#container").append(script);
			</script>
		<div>
		<div style="padding: 20px;float: left;">ע������Web������Ԥ�����ļ���</div>
	</div>
</body>
</html>
```
���ӣ�[demos/play_piece_time.html](demos/play_piece_time.html)

* ���ɾ��������
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=0, minimum-scale=1.0, maximum-scale=1.0">
<title>Sewise Player</title>
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js"></script>
<script type="text/javascript">
	var srcPath = "../player/sewise.player.min.js?server=vod&type=mp4&videourl=http://www.w3schools.com/html/mov_bbb.mp4&sourceid=&autostart=true&starttime=0&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=VodVideo&buffer=5&skin=vodWhite";
	var fallbackurls = {
		ogg: "http://www.w3schools.com/html/mov_bbb.ogg",
		webm: "http://www.w3schools.com/html/mov_bbb.webm"
	}
	var state = "removed";
	function addPlayer(){
		if(state == "removed"){
			var script = document.createElement('script');
			script.type = "text/javascript";
			script.src = srcPath + "&fallbackurls=" + encodeURIComponent(JSON.stringify(fallbackurls, "", "\t"));
			$("#container").append(script);
			state = "added";
		}
	}
	function removePlayer(){
		if(state == "added"){
			$("#container").empty();
			state = "removed";
		}
	}
</script>
</head>
<body>
	<div>
		<div id="container" style="width: 650px; height: 360px; border: solid 1px #DDD"></div>
		<div>
		<ul>
			<button onclick="addPlayer()">Add Player</button>
			<button onclick="removePlayer()">Remove Player</button>
		</ul>
		</div>
		<div style="padding: 20px;float: left;">ע������Web������Ԥ�����ļ���</div>
	</div>
</body>
</html>
```
���ӣ�[demos/add_remove_player.html](demos/add_remove_player.html)

* ����Ԥ��
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="../player/sewise.player.min.js?server=vod&type=mp4&videourl=http://www.w3schools.com/html/mov_bbb.mp4&sourceid=&autostart=false&starttime=0&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=Vod Video ��Ƶ&buffer=5&poster=http://www.sewise.com/data/attachment/portal/201402/10/120117q992dwsgns5cxzoz.png&skin=vodWhite&fallbackurls=%7B%0A%09%22ogg%22%3A%20%22http%3A%2F%2Fwww.w3schools.com%2Fhtml%2Fmov_bbb.ogg%22%2C%0A%09%22webm%22%3A%20%22http%3A%2F%2Fwww.w3schools.com%2Fhtml%2Fmov_bbb.webm%22%0A%7D"></script>
</div>
```
���ӣ�[demos/poster.html](demos/poster.html)

* ��ɫƤ��
```html
<div style="width: 640px;height: 362px;">
	<script type="text/javascript" src="../player/sewise.player.min.js?server=vod&type=flv&videourl=http://219.232.161.202:5080/flvseek/data/userdata/vod/resource/201402/OVNNwRk1.flv&sourceid=&autostart=true&starttime=0&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=Color-Skin&buffer=5&claritybutton=disable&skin=vodVspaas"></script>
	<script type="text/javascript">
		var player;
		function playerReady() {
			player = document.getElementById("sewise_player");
		}
		function setUiColor()
	    {
	        var uiColorArray = [0x333333, 0x56be8e, 0x3ea9f5, 0xf27398, 0xffff00, 0xff0000];
	        var randomIndex = Math.floor(Math.random() * uiColorArray.length);
	        player.setUiColor(uiColorArray[randomIndex]);
	    }
		</script>
        <div style="padding-top: 20px;">
        	<div style="padding-right: 20px;float: right;"><a href="javascript:setUiColor();">Switch UI Color</a></div>
        </div>
</div>
```
���ӣ�[demos/color_skin.html](demos/color_skin.html)

* ���ز���
```html
<div>
	<div style="padding-right: 20px;float: left;">HTML5 ����</div><br>
	<div style="width: 640px; height: 360px; ">
		<script type="text/javascript" src="../player/sewise.player.min.js?server=vod&type=mp4&videourl=http://media.w3.org/2010/05/sintel/trailer.mp4&sourceid=&autostart=true&starttime=0&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=HTML5 ����&buffer=5&skin=vodWhite&fallbackurls=%7B%0A%09%22ogg%22%3A%20%22http%3A%2F%2Fwww.w3schools.com%2Fhtml%2Fmov_bbb.ogg%22%2C%0A%09%22webm%22%3A%20%22http%3A%2F%2Fwww.w3schools.com%2Fhtml%2Fmov_bbb.webm%22%0A%7D"></script>
	</div>
	<br>
	<div style="padding-right: 20px;float: left;">Flash ����</div><br>
	<div style="width: 640px; height: 360px; ">
		<object type="application/x-shockwave-flash" id="sewise_player" name="sewise_player" data="../player/flash/SewisePlayer.swf" width="100%" height="100%">
		<param name="allowfullscreen" value="true">
		<param name="wmode" value="transparent">
		<param name="allowscriptaccess" value="always">
		<param name="flashvars" value="autoStart=true&programId=&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&buffer=5&type=flv&serverPath=&serverApi=ServerApi.execute&skin=../player/flash/skins/vodWhite.swf&title=Flash����&draggable=true&published=0&videoUrl=http://219.232.161.202:5080/flvseek/data/userdata/vod/resource/201402/OVNNwRk1.flv&startTime=0&playerName=Sewise Player&copyright=(C) All right reserved the SEWISE inc 2011-2013&clarityButton=disable&timeDisplay=enable&controlBarDisplay=enable&topBarDisplay=enable&customStrings="></object>
	</div>
</div>
```
���ӣ�[demos/multiplay.html](demos/multiplay.html)

* ��Ļ
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
"http://www.w3.org/TR/html4/loose.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
	<head>
		<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
		<title>Sewise Player-Subtitles</title>
		<script charset="utf-8" type="text/javascript" language="JavaScript" src="../player/js/swfobject.js"></script>
		<script language="JavaScript" charset="utf-8" type="text/javascript">
			var player;
            var host = "http://219.232.161.206/";
            var video_url = "http://219.232.161.206:5080/flvseek/data/userdata/vismam/downfile/201307/02005220p.flv";
            var subtitles_id = "2UtWdAUZ";
            var subtitles_lang = "en";    //��ʾ��Ļ����, Ӣ��: en, ����: zh_CN
            
			var flashvars = {
                serverPath       : host + 'flashservice/gateway.php',
				serverApi        : 'ServerApi.execute',
				autoStart        : 'true',
				logo             : 'http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png',
                title            : 'Subtitles Test',
                clarityButton	 : 'disable',
                lang             : 'en_US',
				skin             : '../player/flash/skins/vodWhite.swf',
                type             : 'flv',
				videoUrl         : video_url,
                
                subtitlesPlayer  : '../player/flash/plugins/SubtitlesPlayer.swf',
                subtitlesId      : subtitles_id,
                subtitlesLang    : subtitles_lang
			};
			var params = {
				allowfullscreen   : true,
				wmode             : "transparent",
				allowscriptaccess : 'always'
			};
			var attributes = {
				id : 'sewise_x_player',
				name : 'sewise_x_player'
			};
			window.onload = function() {
				swfobject.embedSWF("../player/flash/SewisePlayer.swf", "swf-container", "100%", "100%", "9.0.115", false, flashvars, params, attributes);
			}
			function playerReady() {
				player = document.getElementById("sewise_x_player");
			}
            function switchVideo(){
                player.toPlay("http://219.232.161.206:5080/flvseek/data/userdata/vismam/downfile/201307/020058352.flv", 'test toPlay', 0, true, '', 'xMRgJgIP', 'en');
			}
		</script>
	</head>
	<body>
		<div style="width: 600px;height: 400px;">
			<div id="swf-container">
				���ز�����......
			</div>
            <div style="padding-top: 20px;">
                <div style="padding-right: 20px;float: left;"><a href="javascript:switchVideo();">Switch Video</a></div>
            </div>
		</div>
	</body>
</html>
```
���ӣ�[demos/subtitles.html](demos/subtitles.html)


## License
[Sewise Player](http://player.sewise.com/) is licensed under the [MIT license](http://opensource.org/licenses/MIT).


## More information:
* [sewise.com](http://www.sewise.com/)
* [player.sewise.com](http://player.sewise.com/)


## Author:
Jack Zhang [jackzhang1204@gmail.com](http://www.gmail.com)
[sewise.com](http://www.sewise.com/)