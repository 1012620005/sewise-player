# [Sewise Player](http://player.sewise.com/) : HTML5 Video Player

Support for [jQuery](http://jquery.com/) HTML player skins.

## What is Sewise Player?

### Sewise Player��һ��רҵ�������ҳ��Ƶ������������������ǿ�����С����ƽ̨��ʹ�÷����ࡢ����������
* ����������Ҫ��HTML5����Ϊƽ̨������ͬʱ����flash������ʵ���˿�ƽ̨����������ݵ���Ƶ���š�ʹ��Sewise Player��������Windows, MacOS, Linux��Windows Phone, Android, IOS������ƽ̨�ϣ�ͨ����Ӧ�������������Ƶ��
* Sewise Playerʹ�÷ǳ��򵥣�ֻҪ��ҳ���Ӧ��DIV��Ƕ��һ��JS�ļ����ɣ���������ͨ���Զ�ʶ��������Ĺ���������HTML5��flashģʽ������Ƶ���㲻��Ҫ�����κ�רҵ��JavaScript��ActionScript�����Ϳ���������רҵ����ҳ��Ƶ��������
* Sewise Player��������Ϊ��һ��ǰ̨����������ҳ���ϲ�����Ƶ��Ҳ���Խ��Sewise Server��̨����ʵ��רҵ�Ŀɽ����ĵ㲥��ֱ����Ƶ���š�

### �����б�
* ֧��HTML5, Flash��Ƶ���ż�����
* ֧�ֶ�ƽ̨��PC����Windows, MacOS, Linux�ȡ�Mobile����Android, IOS, Windows Phone�ȡ�
* ֧�ֶ���������ݣ�IE6/7/8/9/10��Google Chrome��Firefox��safari��Opera�ȡ�
* ֧�ֶ�����Ƶ��ʽ��mp4��m3u8��oga��webm��theora��flv��f4v�ȡ�
* ֧�ֶ���Э��ֱ������rtmp��udp��http ts��rtsp��ֱ���ͻطš�
* ֧��Flash����m3u8�ļ����Լ�AES-128���벥�š�
* ֧��PC��Mobileƽ̨�������Զ�ʶ���ܡ�
* ֧�������HTML5��Flash���Լ�⡣
* ֧�ֲ��ŵ�ַAMF, AJAX, JOSNP��������
* ֧���Զ���HTML5��FlashƤ���������˽���򣬼����Լ��������������Ƥ����
* ֧��ǰ�ù�棨swf, ͼƬ, ��Ƶ����
* ֧����Ļ��
* ֧�ֶ��ֲ��Ų����趨��
* ֧�ַḻ��api�ӿڣ����ٴ��칦��ǿ��Ĳ����


### �ļ����ܣ�
* sewise.player.min.js���������ļ�
* html��HTML5Ƥ��Ŀ¼��
* html\skins\vodWhite, HTML5Ƥ��vodWhiteĿ¼��
* html\skins\vodWhite\skin.html, HTML5Ƥ��vodWhite DomԪ�ء�
* html\skins\vodWhite\skin.html.js, HTML5Ƥ��vodWhite DomԪ�ض������ڼ��ݿ�����ء�
* html\skins\vodWhite\skin.css, HTML5Ƥ��vodWhite CSS��ʽ��
* html\skins\vodWhite\skin.js, HTML5Ƥ��vodWhite JS�߼����롣

* flash, flash������Ŀ¼
* flash\SewisePlayer.swf�� Flash���������ļ���
* flash\skins, FlashƤ��Ŀ¼
* flash\skins\vodWhite.swf, Flash�㲥��ɫƤ����
* flash\skins\liveWhite.swf, Flashֱ����ɫƤ����
* flash\skins\vodOrange.swf, Flash�㲥��ɫƤ����
* flash\skins\liveOrange.swf, Flashֱ����ɫƤ����


### ҳ�沥����Ƕ�뷽ʽ��
* �㲥��ַsourceid���󲥷�
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="http://192.168.1.24/libs/swfplayer/player/sewise.player.min.js?server=vod&sourceid=ZIM6n32R&autostart=true&starttime=2&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&buffer=5&skin=vodWhite"></script>
</div>
```
���ӣ�[demos/vod_sourceid.html](demos/vod_sourceid.html)

* �㲥��ַvideourlֱ�Ӳ���
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="player/sewise.player.min.js?server=vod&type=mp4&videourl=http://www.w3schools.com/html/mov_bbb.mp4&sourceid=&autostart=true&starttime=0&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=VodVideo&buffer=5&skin=vodWhite"></script>
</div>
```
���ӣ�[demos/vod_videourl_mp4.html](demos/vod_videourl_mp4.html)

* ֱ����ַpid���󲥷�
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="http://192.168.1.21/libs/swfplayer/player/sewise.player.min.js?server=live&autostart=true&pid=e4f9i5sk&shifttime=&buffer=5&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&skin=liveWhite"></script>
</div>
```
���ӣ�[demos/live_pid.html](demos/live_pid.html)

* ֱ����ַstreamurlֱ�Ӳ���
```html
<div style="width: 640px; height: 360px; ">
	<script type="text/javascript" src="player/sewise.player.min.js?server=live&type=rtmp&streamurl=rtmp://192.168.1.21/livestream/ijzj7292&autostart=true&pid=&shifttime=&buffer=5&lang=en_US&logo=http://onvod.sewise.com/libs/swfplayer/skin/images/logo.png&title=LiveVideo&skin=liveWhite"></script>
</div>
```
���ӣ�[demos/live_streamurl_rtmp.html](demos/live_streamurl_rtmp.html)


### ����������ԭ��:
* ��һ����ҳ�����sewise.player.min.js�ļ��󣬸ýű��Ὣ��Ӧ�Ĳ���������������������ǰ���豸ƽ̨����������ԣ�ͬʱ�������JS�ļ���·��ȡ��host��ַ�����ڲ��ŵ�ַ����
* �ڶ�����ͨ������������vod��type�����뼰��������ԣ���ȷ��������������HTML5����Flashģ�顣���ڲ�ͬƽ̨�������ͬʱ֧�ֵ���Ƶ��ʽ����Э�飬����������HTML5����ģ�顣
* �����������ض�Ӧ��Ƥ���ļ�����ļ���
* ���Ĳ�����Ƥ��������ɺ󽫸��ݸ����Ĳ�������ʼ������������������ʼ����ɺ󣬻��ڵ�ǰҳ���лص�playerReady()������HTML5��Flash����������ص��÷���������ʾ������API�ӿ��ѿ��á�


### ������������
* Sewise Player�������ṩ�����Ĳ������ù��ܣ�ͨ�����ò�ͬ�Ĳ���ֵ�����ò��������в�ͬ�Ĳ������ԡ�
* ��ϸ����˵��������"����˵��.md"�ļ���


### API�ӿڵ��ã�
* Sewise Player�����������ṩ�˷ḻ��API�ӿڣ�ͨ��API�ӿڵ��ÿ������ɿ��Ʋ��������š�
* ��ϸ�ӿ�˵��������"�ӿ�˵��.md"�ļ���
* �㲥�ӿ����ӣ�[demos/vod_api.html](demos/vod_api.html)
* ֱ���ӿ����ӣ�[demos/live_api.html](demos/live_api.html)


### ������Ƥ����
* Sewise Player������Ƥ����Ϊ�����֣���HTML5��FlashƤ����
* HTML5Ƥ����HTML��CSS��JS�ļ����ɣ�һ���ļ�Ŀ¼��Ӧһ��Ƥ����
* FlashƤ����SWF�ļ����ɣ�һ��SWF�ļ���Ӧһ��Ƥ����
* HTML5��FlashƤ�����÷�����ͬ��ֻҪ������skin����Ϊ��Ӧ��Ƥ��������skin=vodWhite��ʾ��ɫ�㲥Ƥ����
* HTML5��FlashƤ����Դ�����ѿ��ţ���[sourceĿ¼](source)��


## License
[Sewise Player](http://player.sewise.com/) is licensed under the [MIT license](http://opensource.org/licenses/MIT).


## More information:
* [sewise.com](http://www.sewise.com/)
* [player.sewise.com](http://player.sewise.com/)


## Author:
Jack Zhang [jackzhang1204@gmail.com](http://www.gmail.com)
[sewise.com](http://www.sewise.com/)







