    <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-15">
	        <script type="text/javascript">
        var dateTimeOffset = new Date().getTimezoneOffset();
        
        function getElementsByClassNameLocalTimeWrapper() {
            return document.getElementsByClassName("localtime");
        }
        
        (function () {
            var onload = function () {
                var elementArray = [];
                
                if (document.getElementsByClassName) {
                    elementArray = getElementsByClassNameLocalTimeWrapper();
                } else {
                    var re = new RegExp('(^| )localtime( |$)');
                    var els = document.getElementsByTagName("*");
                    for (var i=0,j=els.length; i<j; i++) {
                        if (re.test(els[i].className))
                            elementArray.push(els[i]);
                    }
                }
                
                for (var i = 0; i < elementArray.length; i++) {    
                    var timeLocal = new Date(parseInt(elementArray[i].getAttribute("data-timestamp")));
                    var hour = timeLocal.getHours();
                    var ap = "am";
                    if (hour > 11) {
                        ap = "pm";
                    }
                    else if (hour > 12) {
                        hour = hour - 12;
                    }
                    
                    var string = elementArray[i].getAttribute("data-template");
                    string = string.replace("[Y]", timeLocal.getFullYear());
                    string = string.replace("[m]", ('0' + (timeLocal.getMonth() + 1)).slice(-2));
                    string = string.replace("[d]", ('0' + timeLocal.getDate()).slice(-2));
                    string = string.replace("[H]", ('0' + timeLocal.getHours()).slice(-2));
                    string = string.replace("[g]", ('0' + hour).slice(-2));
                    string = string.replace("[i]", ('0' + timeLocal.getMinutes()).slice(-2));
                    string = string.replace("[s]", ('0' + timeLocal.getSeconds()).slice(-2));
                    string = string.replace("[a]", ap);
                    elementArray[i].childNodes[0].nodeValue = string;
                }
            };
            
            if (window.addEventListener)
                window.addEventListener("DOMContentLoaded", onload);
            else if (window.attachEvent)
                window.attachEvent("onload", onload);
        })();
        </script><link href="https://wtheme.webme.com/img/main/ios_icons/apple-touch-icon.png" rel="apple-touch-icon" />
<link href="https://wtheme.webme.com/img/main/ios_icons/apple-touch-icon-76x76.png" rel="apple-touch-icon" sizes="76x76" />
<link href="https://wtheme.webme.com/img/main/ios_icons/apple-touch-icon-120x120.png" rel="apple-touch-icon" sizes="120x120" />
<link href="https://wtheme.webme.com/img/main/ios_icons/apple-touch-icon-152x152.png" rel="apple-touch-icon" sizes="152x152" />
<meta property="og:title" content="  Arapça Osmanlıca Klavye v5.0" />
<meta property="og:image" content="http://static-cache.tr.uaprom.net/image/se/busines_head_41.jpg?r=143818" />
<meta http-equiv="Content-Language" content="tr-TR">
<meta name="language" content="Turkish">
<meta content="Turkey" name="geo.placename"> 
<meta name="robots" content="index, follow">
<meta name="Resource-Type" content="Document">
<meta name="designer" content="HARUN PEHLİVAN Ardic (HP IT GROUP GLOBAL PROFESYONEL IT GROUP)">
<meta name="author" content="HARUN PEHLİVAN Ardic (HP IT GROUP GLOBAL PROFESYONEL IT GROUP), trcmnhp@hotmail.com">
<meta name="web_author" content="trcmnhp@hotmail.com">
<meta name="copyright" content="2023">
<meta name="reply-to" content="trcmnhp@hotmail.com">
<meta name="distribution" content="global">

<link rel="shortcut icon" href="https://cdn-cms.f-static.com/uploads/1017556/400_5aade1f55d888.png">
<meta http-equiv="X-Frame-Options" content="deny">

<link href="https://fonts.googleapis.com/css?family=Amiri" rel="stylesheet"> 
<script type="text/javascript">
        var oldPath = window.location.pathname;
        var newPath = decodeURIComponent( unescape( unescape(oldPath)));
        
        if (oldPath !== newPath) {
            history.pushState({}, "", newPath);
        }
        
        function recaptchaLoadedCallbackWrapper() {
            if (oldPath !== newPath) {
                history.pushState({}, "", oldPath);
            }
        
            if (typeof recaptchaLoadedCallback === "function") { 
                recaptchaLoadedCallback();
            }
        }
</script>
<script src="https://www.google.com/recaptcha/api.js?onload=recaptchaLoadedCallbackWrapper&render=explicit" async defer></script>
<script type="text/javascript">
  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-48793753-2']);
  _gaq.push(['_setCustomVar',
      1,
      'package',
      'adfree',
      3
   ]);
_gaq.push(['_setCustomVar',
      2,
      'design',
      'iceblue',
      3
   ]);
_gaq.push(['_setCustomVar',
      3,
      'module',
      'false',
      3
   ]);
_gaq.push(['_setCustomVar',
      4,
      'afa',
      'unchecked',
      3
   ]);
_gaq.push(['_setCustomVar',
      5,
      'll',
      '0M',
      3
   ]);

  _gaq.push (['_gat._anonymizeIp']);
  _gaq.push(['_setDomainName', 'tr.gg']);  
  _gaq.push(['_setAllowLinker', true]);  
  _gaq.push(['_trackPageLoadTime']);
  _gaq.push(['_trackPageview']);
  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();

</script>
	<title>Arapça Osmanlıca Klavye v5.0​ Arabic Ottoman keyboard v5.0​ العربية العثمانية لوحة المفاتيح  v5.0 </title>
	<style type="text/css">
	<!--
		body {
			background-color: #2e3839;
			margin: 5px;
			font-family:	tahoma, verdana, arial;
		} 
		td {
			font-family:	tahoma, verdana, arial;
			font-size: 16px;
			color: #000000;
		}
		a {
			font-size: 16px;
			color: #000000;
			text-decoration: none;
		}
		a:visited {
			text-decoration: none;
		}
		a:hover {
			text-decoration: underline;
		}
		a.std {
			color:#436123;
			text-decoration: none;
		}
		a:visited.std { color:#436123; text-decoration: none; }
		a:hover.std { color:#436123; text-decoration: underline; }
		.small	{
			font-family:	tahoma, verdana, arial;
			font-size: 9px;
			color: #000000;
		}
		.small a {
			color: black;
		}
		.headline,.headline2,.headline3 {
			font-family:	tahoma, verdana, arial;
			font-size: 11px;
			color: white;
		}
		.cont {
			font-family:	tahoma, verdana, arial;
			font-size: 11px;
			color: #000000;
		}
		.ro {
			background-color:#b3b3b3;
		}
		html {
			font-family:	tahoma, verdana, arial;
			font-size: 11px;
		}
		.bbc { color:#b3b3b3; background-color:#b3b3b3; border-color:#b3b3b3; border-style:solid; border-width:1px; text-decoration:none;}
		td.nav {
			background-image: url(http://static-cache.tr.uaprom.net/image/se/busines_head_41.jpg?r=143818);
			background-repeat: none;
			height: 33px;
			width: 185px;
			padding-left: 25px;
		}
		td.nav a {
			color: #000000;
			font-size:15px;
		}
		td.nav_heading {
			background-image: url(//theme.webme.com/designs/iceblue/images/heading_left.gif);
			color: white;
			padding-left: 15px;
			line-height: 23px;
			width: 185px;
			height: 23px;
		}
		td.nav_head {
			background-image: url(//theme.webme.com/designs/iceblue/images/head_left.gif);
			color: white;
			padding-left: 15px;
			line-height: 31px;
			width: 185px;
			height: 31px;
		}
		td.sidebar_heading {
			background-image: url(//theme.webme.com/designs/iceblue/images/heading_right.gif);
			color: white;
			padding-left: 15px;
			line-height: 24px;
			width: 168px;
			height: 24px;
		}
		td.sidebar_head {
			background-image: url(//theme.webme.com/designs/iceblue/images/head_right.gif);
			color: white;
			padding-left: 15px;
			line-height: 32px;
			width: 168px;
			height: 32px;
		}
		.shouty,.shouty2,.shouty3,.shouty4,.shouty5,.shoutysky,.shouty_facebook_like_button {
			background-color: #b3b3b3;
			background-image: url(//theme.webme.com/designs/iceblue/images/shouty.gif);
			background-repeat: no-repeat;
			padding: 5px;
		}
        
        .shoutysky {
            padding: 0px;
        }
                
		.shoutbox {
			overflow: auto;
			height: 300px;
			width: 175px;
		}
		.nick {
			font-weight: bold;
		}
		.shoutbox hr {
			border: 0;
			border-bottom: 1px dashed #b3b3b3;
		}
		.shoutbox input, .shoutbox textarea {
			width: 155px;
		}
		.send {
			margin-top: 5px;
			color: black;
			font-weight: bold;
			width: 50px;
			margin-left: auto;
			margin-right: auto;
		}
		.RowLight, .RowDark {
			padding-left: 10px;
			height: 27px;
		}
		.RowLight {
			background-image: url(//theme.webme.com/designs/iceblue/images/stats_bg1.gif);
		}
		.RowDark {
			background-image: url(//theme.webme.com/designs/iceblue/images/stats_bg2.gif);
		}
		img { border: 0;}
		.headline a, .footer_text, .footer_text a.nav {
			color: white;
		}
        			//-->
	</style>
</head>
<body>
<FONT color="white"><style type="text/css">
:root {--main-font: Arial;}

@import url('https://fonts.googleapis.com/css?family=Amiri');

@charset "iso 8859-9";.edit_content_top,.edit_content_top table{width:99% !important;background:#3b5998}

::-moz-selection{background:red;color:#fff}::selection{background:red;color:#fff}

.edit_content_top table{margin:10px 0 0 0;border-radius:25px 25px 3px 3px;-moz-border-radius:25px 25px 3px 3px;-webkit-border-radius:25px 25px 3px 3px;padding:7px 0 7px 0}td.edit_content_top tbody tr td{font:normal 18px/18px 'Quicksand',sans-serif;color:#fff;text-shadow:1px 1px #000;position:relative}html{width:99%;display:table;margin:auto}body>div:nth-child(3){display:fixed}body{overflow:auto;width:100%;max-width:1000px;text-align:center;margin:2px -10pxpx 0 2px;padding:3px 0 0 0;color:#000;font:normal 20px/20px 'Quicksand',sans-serif;display:table-cell;vertical-align:middle}.edit_content_main>div:nth-child(1){max-width:none !important}body,td.edit_rechts_sbg{background:#3b5998 none no-repeat fixed 0 0}table.edit_main_table,font:nth-child(1){margin-left:auto;margin-right:auto;text-align:center}table.edit_main_table,font:nth-child(1),.edit_main_tr,#bannerAlani img{width:100%;max-width:997px!immortant;position:relative}ins:empty{display:none}#bannerAlani div{text-align:center;position:relative}#aswift_1_expand{max-width:600px}.adsbygoogle{padding:0;margin:0}.adsense{background:#c00;text-align:center;padding:5px;border:1px solid #7a2109}a <p{float:left !important}.edit_rechts_cbg{width:100% !important}.edit_content_container{width:100% !important}.edit_content_pre_headline2{width:5%}td.edit_content_main{position:relative;width:100%;overflow:hidden}.edit_content_main>div:nth-child(1){position:relative;width:96%;max-width:618px;overflow:hidden !important}.edit_content_main>div:nth-child(1) a{text-decoration:underline}.reklamOrta{margin:0;padding:0;width:100%;overflow:hidden}.edit_content_main div{margin:0;margin-left:.5em;padding:0;font-size:16px}.edit_content_main sup{font-size:9pt}.edit_content_main a{font-size:13pt}.edit_content_main>div:nth-child(1){background:#fff;padding:10px 9px 0 9px;margin:10px 9px 21px 1px}.tabMenu{list-style:none;margin:0 10%;padding:0;width:90%;overflow-x:hidden;display:block}.tabMenu li{font-family:tahoma,sans-serif;font-size:18px;float:left;background:#f5a748 url(https://img.webme.com/pic/g/gizliilimler/buttonBG_hover.gif);margin:3px 3px 0 0;border:1px solid #ff8a00;match-parent}.tabMenu li:hover{background:url(https://img.webme.com/pic/g/gizliilimler/buttonBG.gif)}.tabMenu li a{color:#fff;font-size:.61em;text-transform:uppercase;margin:6px;text-decoration:none;text-shadow:1px 1px 1px #000}.tabMenu li:first-child{border-bottom-left-radius:1.5em;padding-left:1em}.tabMenu li:last-child{border-bottom-right-radius:1.5em;padding-right:1em}#wysiwyg{padding:5px;width:99%;background:#ffc021;margin:15px 0 10px 0}.linkler{background:#fff;border-radius:8px;-moz-border-radius:8px;-webkit-border-radius:8px}.Son div:first-child,.linkler div:first-child{border-radius:8px 8px 0 0;-moz-border-radius:8px 8px 0 0;-webkit-border-radius:8px 8px 0 0}.linkler div:last-child{border-bottom:0;border-radius:0 0 8px 8px;-moz-border-radius:0 0 8px 8px;-webkit-border-radius:0 0 8px 8px}.Son,.linkler{width:calc(98% -5px);overflow:hidden;border:0!immortant;margin:1;width:150px!immortant;padding:0;margin-right:5px}.Son div{color:#fff}.Son div,.linkler div{padding:5px}.linkler div{border-bottom:1px solid #ccc}.linkler div:hover{background:#b0daff}.Son div:nth-child(2){background:#fff;color:#000}.Son div a,.linkler div a{color:#000}.Son,.linkler,.edit_content_main>div:nth-child(1),.edit_content_top table{-webkit-box-shadow:1px 1px 4px 0 #ccc;-moz-box-shadow:1px 1px 4px 0 #ccc;box-shadow:1px 1px 4px 0 #ccc}.not2{background:#9cf;border:1px dashed #0067ce;padding:10px}.golge,.golgeli,center>form,div.polaroid,.not2,.not3,.coder,.not4,.kaynaklar,.adsbygoogle iframe,#wysiwyg,#bannerAlani img,.edit_main_tr{box-shadow:0 4px 8px 0 rgba(0,0,0,0.2),0 6px 16px 0 rgba(0,0,0,0.19)}.koseli,.not3,.coder,.not4,.kaynaklar,#wysiwyg,.tabMenu li,#bannerAlani img,table.edit_main_table,ins.adsbygoogle{border-radius:5px;-moz-border-radius:5px;-webkit-border-radius:5px}td<tr<td<tbody<table<center{width:300px}center form table{width:94%}center>form{margin:15px 0 10px 0;background:#ffc021;width:100%;box-shadow:0 4px 8px 0 rgba(0,0,0,0.2),0 6px 20px 0 rgba(0,0,0,0.19);border-radius:5px 5px 5px 5px;-moz-border-radius:5px 5px 5px 5px;-webkit-border-radius:5px 5px 5px 5px}#kommentartext{width:100%}input,textarea,select{border:1px solid #c6c6c6;font-size:14px;padding:5px;border-radius:3px;-moz-border-radius:3px;-webkit-border-radius:3px}input:hover,textarea:hover,:focus{box-shadow:inset 0 2px 2px rgba(0,0,0,0.3);-moz-box-shadow:inset 0 2px 2px rgba(0,0,0,0.3)}:focus{border:1px solid #4285f4}.altsayfa{background:#e2e2e2 !important;background:-moz-linear-gradient(top,#e2e2e2 0,#dbdbdb 50%,#d1d1d1 51%,#fefefe 100%) !important;background:-webkit-gradient(left top,left bottom,color-stop(0%,#e2e2e2),color-stop(50%,#dbdbdb),color-stop(51%,#d1d1d1),color-stop(100%,#fefefe)) !important;background:-webkit-linear-gradient(top,#e2e2e2 0,#dbdbdb 50%,#d1d1d1 51%,#fefefe 100%) !important;background:-o-linear-gradient(top,#e2e2e2 0,#dbdbdb 50%,#d1d1d1 51%,#fefefe 100%) !important;background:-ms-linear-gradient(top,#e2e2e2 0,#dbdbdb 50%,#d1d1d1 51%,#fefefe 100%) !important;background:linear-gradient(to bottom,#e2e2e2 0,#dbdbdb 50%,#d1d1d1 51%,#fefefe 100%) !important;filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#e2e2e2',endColorstr='#fefefe',GradientType=0); !important}*,td{font-family:var(--main-font); font-size:16px}.not,.not2,#kategori,.adsense,.katman1,.katman2,.katman3,.katman4,.katman5,a,span,div,.kaynaklar{width:100%!immortant}h1,h2,h3,h3 span{max-width:100%;margin:10px 0;-10px 0;padding:0;text-shadow:2px 2px #ccc}h1{font:bold 30px/30px var(--main-font)}h2{font:bold 24px/24px var(--main-font);color:#499bea}h3,h3 span{font:bold 19px/19px var(--main-font);text-shadow:none}.maviKutu{background:rgba(73,155,234,1);background:-moz-linear-gradient(left,rgba(73,155,234,1) 0,rgba(32,124,229,1) 100%);background:-webkit-gradient(left top,right top,color-stop(0%,rgba(73,155,234,1)),color-stop(100%,rgba(32,124,229,1)));background:-webkit-linear-gradient(left,rgba(73,155,234,1) 0,rgba(32,124,229,1) 100%);background:-o-linear-gradient(left,rgba(73,155,234,1) 0,rgba(32,124,229,1) 100%);background:-ms-linear-gradient(left,rgba(73,155,234,1) 0,rgba(32,124,229,1) 100%);background:linear-gradient(to right,rgba(73,155,234,1) 0,rgba(32,124,229,1) 100%);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#499bea',endColorstr='#207ce5',GradientType=1)}.Son div:first-child{font-weight:bold;border-bottom:0;background:#3b5998}#sidebar_heading_1>tbody:nth-child(1)>tr:nth-child(1)>td:nth-child(1),.edit_navi_headbg>table:nth-child(1)>tbody:nth-child(1)>tr:nth-child(1){display:none}td.nav{height:1.5em;overflow:hidden;background-image:none;background:0;font-size:.857em;display:inline-block;border:1px solid #d0d0d3;line-height:1em;padding:.6em .7em;margin-top:6px;text-indent:0;text-align:center;-webkit-border-radius:.769em;-moz-border-radius:769em;border-radius:769em;text-shadow:0 0 0 rgba(255,255,255,.01));width:84%;background-color:#666;background-image:url(none);-webkit-box-shadow:1px 1px 3px 0 rgba(0,0,0,0.75);-moz-box-shadow:1px 1px 3px 0 rgba(0,0,0,0.75);box-shadow:1px 1px 3px 0 rgba(0,0,0,0.75);vertical-align:middle}.checked_menu .nav{background:#f85032 !important;background:-moz-linear-gradient(top,#f85032 0,#f16f5c 50%,#f6290c 51%,#f02f17 71%,#e73827 100%) !important;background:-webkit-gradient(left top,left bottom,color-stop(0%,#f85032),color-stop(50%,#f16f5c),color-stop(51%,#f6290c),color-stop(71%,#f02f17),color-stop(100%,#e73827)) !important;background:-webkit-linear-gradient(top,#f85032 0,#f16f5c 50%,#f6290c 51%,#f02f17 71%,#e73827 100%) !important;background:-o-linear-gradient(top,#f85032 0,#f16f5c 50%,#f6290c 51%,#f02f17 71%,#e73827 100%) !important;background:-ms-linear-gradient(top,#f85032 0,#f16f5c 50%,#f6290c 51%,#f02f17 71%,#e73827 100%) !important;background:linear-gradient(to bottom,#f85032 0,#f16f5c 50%,#f6290c 51%,#f02f17 71%,#e73827 100%) !important;filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#f85032',endColorstr='#e73827',GradientType=0) !important}td.nav{background:#fceabb;background:-moz-linear-gradient(top,#fceabb 0,#fccd4d 50%,#f8b500 51%,#fbdf93 100%);background:-webkit-gradient(left top,left bottom,color-stop(0%,#fceabb),color-stop(50%,#fccd4d),color-stop(51%,#f8b500),color-stop(100%,#fbdf93));background:-webkit-linear-gradient(top,#fceabb 0,#fccd4d 50%,#f8b500 51%,#fbdf93 100%);background:-o-linear-gradient(top,#fceabb 0,#fccd4d 50%,#f8b500 51%,#fbdf93 100%);background:-ms-linear-gradient(top,#fceabb 0,#fccd4d 50%,#f8b500 51%,#fbdf93 100%);background:linear-gradient(to bottom,#fceabb 0,#fccd4d 50%,#f8b500 51%,#fbdf93 100%);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#fceabb',endColorstr='#fbdf93',GradientType=0)}td.nav:hover{background:#b7deed !important;background:-moz-linear-gradient(top,#b7deed 0,#71ceef 50%,#21b4e2 51%,#b7deed 100%) !important;background:-webkit-gradient(left top,left bottom,color-stop(0%,#b7deed),color-stop(50%,#71ceef),color-stop(51%,#21b4e2),color-stop(100%,#b7deed)) !important;background:-webkit-linear-gradient(top,#b7deed 0,#71ceef 50%,#21b4e2 51%,#b7deed 100%);background:-o-linear-gradient(top,#b7deed 0,#71ceef 50%,#21b4e2 51%,#b7deed 100%) !important;background:-ms-linear-gradient(top,#b7deed 0,#71ceef 50%,#21b4e2 51%,#b7deed 100%) !important;background:linear-gradient(to bottom,#b7deed 0,#71ceef 50%,#21b4e2 51%,#b7deed 100%) !important;filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#b7deed',endColorstr='#b7deed',GradientType=0) !important}td.nav a,.altsayfa a,.altsayfa a:hover{color:#000}.checked_menu td.nav a,td.nav:hover a{color:#fff}td.edit_header_full{background-position:center;background-repeat:no-repeat;border-top-left-radius:1em;border-top-right-radius:1em}td.edit_header_full,table.edit_second_table,td.edit_main_tr,td.edit_header_full table,table.edit_third_table,table.edit_rechts_tabelle{width:100% !important}td.edit_navi_headbg,td.edit_rechts_bottom{width:17% !important}td.edit_below_nav,td.edit_content_left_spacer{background:0;visible:hidden;display:none}td.edit_below_nav,td.edit_content,td.edit_content_top,td.edit_rechts_cbg,td.sidebar_heading,td.edit_content_bottom2,td.edit_content_bottom,td.shouty,td.shouty2,td.shouty3,td.shouty4,td.shouty5,td.edit_navi_headbg,td.edit_rb_footer,td.edit_rechts_bottom{background:url:();background:0;background-color:#f0f8ff;color:#000;text-align:left;font-size:15px}td.sidebar_heading,td.shouty,td.shouty2,td.shouty3,td.shouty4,td.shouty2{text-align:left;min-width:168px}.pagination a{text-decoration:none !important}a:link,a:active,a:visited{color:#002bb8}a:link,a:active,a:visited,a:hover{text-decoration:none;border:0;box-shadow:none}a:hover,hr{color:#000}div img:not:(.sosyal-ag),div object,embed{box-shadow:3px 3px 3px #888;border-radius:10px;-moz-border-radius:10px;-khtml-border-radius:10px;-webkit-border-radius:10px}.shouty select{width:100%;margin-bottom:3px}td[width]{white-space:normal}td[width] i,td[width] i b{font-style:normal}td[width] i b{text-transform:capitalize}td[width] i b:before{content:""}.katman1{background:#fff8c4;color:#000;border:1px solid #e6b868}.katman1 a{color:red}.katman2{background:#FFF;border:1px solid #000}.not3{border:1px solid #000;background:#efc5ca;background:-moz-linear-gradient(top,#efc5ca 0,#d24b5a 50%,#ba2737 51%,#f18e99 100%);background:-webkit-gradient(left top,left bottom,color-stop(0%,#efc5ca),color-stop(50%,#d24b5a),color-stop(51%,#ba2737),color-stop(100%,#f18e99));background:-webkit-linear-gradient(top,#efc5ca 0,#d24b5a 50%,#ba2737 51%,#f18e99 100%);background:-o-linear-gradient(top,#efc5ca 0,#d24b5a 50%,#ba2737 51%,#f18e99 100%);background:-ms-linear-gradient(top,#efc5ca 0,#d24b5a 50%,#ba2737 51%,#f18e99 100%);background:linear-gradient(to bottom,#efc5ca 0,#d24b5a 50%,#ba2737 51%,#f18e99 100%);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#efc5ca',endColorstr='#f18e99',GradientType=0);padding:10px}.not4{width:98%;background:red;padding:5px;text-align:center}.not5{background:#fff8c4;color:#000;padding:5px;border:1px solid #e6b868;text-align:center;width:97%}.not4,.not4 a{color:#fff;text-shadow:1px -1px #000}.not5 b:first-child{color:#7a2109}.coder{background:#fff3a5;border:1px solid #e6b868;text-align:center}.coder b:not(:first-child){font-weight:normal;background:rgba(0,0,0,.1);padding:2px;border-radius:3px;font-size:14px;line-height:14px}.coder b:first-child{color:#7a2109}

*[id^=kategori]{padding:5px;width:97%}*[id^=kategori] a{text-decoration:none !important;color:#000}*[id^=kategori] a:hover{text-decoration:underline !important}*[id^=kategori] *{list-style-image:url("https://img.webme.com/pic/g/gizliilimler/file_icon.gif");margin:0}*[id^=kategori] * li{padding:1px;margin-left:-15px;width:100%}

.arabic,arabic b{text-shadow:2px 2px 2px #ccc;font-family:'Amiri', serif;font-size:28px !important;line-height:52px}.kaynaklar{background:#fff8c4;padding:5px;width:98%}div.polaroid{width:80%;background-color:#fff;margin-bottom:25px;text-align:center}div.polaroid div{text-align:center;padding:10px 30px 10px 1px;margin-left:0}p.arabic{margin:0}.invert{filter:invert(100%);-webkit-filter:invert(100%)}.alinti{background:maroon radial-gradient(circle,#a01010 0,#800000 80%) center center / cover no-repeat;color:#fff;padding:5px;text-align:center;text-rendering:optimizeLegibility;font-size:1.1em;font-family:Georgia,"Times New Roman",Times,Serif;font-size:120%;text-shadow:2px 2px 4px #000;line-height:30px}.ayet{position:relative;padding:10px;color:#000;font-family:var(--main-font);font-size:100%;text-shadow:2px 2px 4px #ccc;background:url("https://img.webme.com/pic/g/gizliilimler/mermer.jpg"); background-size: 100% auto; border:7px solid #000;border-radius:5px;-moz-border-radius:5px;-webkit-border-radius:5px;-webkit-box-shadow:0 0 4px rgba(0,0,0,0.2),inset 0 0 50px rgba(0,0,0,0.1);-moz-box-shadow:0 0 4px rgba(0,0,0,0.2),inset 0 0 50px rgba(0,0,0,0.1);box-shadow:0 0 5px rgba(0,0,0,0.2),inset 0 0 50px rgba(0,0,0,0.1);box-shadow:inset 0 0 .6em #000,0 0 4px rgba(0,0,0,0.2)}#nav_Zaman,#nav_ZamaninKisaTarihi{margin-bottom:5px}button,input[type=button],input[type=submit]{display:inline-block;padding:4px 12px;margin-bottom:0;line-height:20px;color:#333;text-align:center;text-shadow:0 1px 1px rgba(255,255,255,0.75);vertical-align:middle;cursor:pointer;background-color:#f5f5f5;background-image:linear-gradient(to bottom,#fff,#e6e6e6);background-repeat:repeat-x;border:1px solid #ccc;border-color:rgba(0,0,0,0.1) rgba(0,0,0,0.1) rgba(0,0,0,0.25);border-bottom-color:#b3b3b3;border-radius:4px;margin:3px 0 3px 0;font-weight:bold}button:hover,input[type=button]:hover,input[type=submit]:hover{color:#333;background-image:linear-gradient(to bottom,#e6e6e6,#fff);box-shadow:1px 1px 1px 0 rgba(0,0,0,0.24),0 1px 1px 0 rgba(0,0,0,0.19)}input[type=search]{width:70%;margin-right:0;border-radius:4px 0 0 4px}button{width:29%;margin:-1px 0 0 -5px;border-radius:0 4px 4px 0;font-size:14px}input:-moz-placeholder{color:#999}input::-webkit-input-placeholder{color:#999}.sosyal{padding:10px}.sosyal span{font-size:20px}.edit_content_bottom2_left_spacer,.edit_content_left_spacer,.edit_content_botom2_right_spacer,.edit_content_right_spacer{display:none}.copyright{font-size:14px;width:calc(98%+2px);overflow:hidden;text-shadow:2px 2px 2px #000;padding:0:margin:0}.kirmizi,h3 span{color:#a30}.copyright a{color:#ff9}td[width="100%"]{white-space:-moz-pre-wrap !important;white-space:-pre-wrap;white-space:-o-pre-wrap;white-space:pre-wrap;word-wrap:break-word;max-width:600px !important}.smiley{font-size:125%}

.documentary{font-size:125% !important}
</style>

<div id="bannerAlani"></div><br style="clear both;">

<script type="text/javascript" async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- akhepedia forum top 1 -->
<ins class="adsbygoogle"
 style="display:inline-block;width:728px;height:90px"
 data-ad-client="ca-pub-9497855579350422"
 data-ad-slot="8441358067"></ins>
<script type="text/javascript">
(adsbygoogle = window.adsbygoogle || []).push({});
</script><br><br></FONT>
 <a href="https://codepen.io/harunpehlivan/full/mQyMXm" target="_blank">Arapça / Osmanlı Türkçesi Klavyesi V.01 
</a><br>
 <a href="https://codepen.io/harunpehlivan/full/LXENPW" target="_blank">Arapça Osmanlıca Klavye v4.0 </a>
																		<table width="100%"	border="0" cellspacing="0" cellpadding="0">
																				<td class="edit_content_main" width="94%">
																					<div style="width: 510; overflow: auto;"><h1>Arapça Osmanl&#305;ca Klavye v5.0</h1><h2>BU PROGRAM 
 2005 İMAM-HATİP LİSESİ MEZUNU <a href="https://harunpehlivantebimtebitagem.carrd.co" target="_blank"> FOUNDER,CEO BLOGGER</a> Geli&#351;tiren:  HARUN PEHLİVAN </h2><script type="text/javascript">function yazdir(b){var e=document.conversion.saisie;if(document.selection){e.focus();sel=document.selection.createRange();sel.text=String.fromCharCode(b);document.conversion.focus()}else{if(document.conversion.saisie.selectionStart||document.conversion.saisie.selectionStart=="0"){var d=document.conversion.saisie.selectionStart;var c=document.conversion.saisie.selectionEnd;var a=document.conversion.saisie.value;e.value=a.substring(0,d)+String.fromCharCode(b)+a.substring(c,a.length)}else{e.value+=String.fromCharCode(b)}}var f=document.conversion.saisie;f.focus();f.scrollTop=f.scrollHeight}function copy(){textRange=document.conversion.saisie.createTextRange();textRange.execCommand("Copy");textRange=""}var car;function transcrire(){car=document.conversion.saisie.value;car=car.replace(/g|q/gi,"&#1602;").replace(/w/gi,"&#1608;").replace(/A/g,"&#1614;&#1593;&#1614;").replace(/E/g,"&#1614;").replace(/e|a/g,String.fromCharCode(1614)).replace(/r/gi,"&#1585;").replace(/t/gi,"&#1578;").replace(/y/gi,"&#1610;").replace(/Ö|O|U|Ü/g,"&#1575;&#1615;").replace(/u|ü|o|ö/g,"&#1615;").replace(/i|&#305;/gi,"&#1616;").replace(/p/gi,"&#1662;").replace(/\&#286;|\&#287;/gi,"&#1594;").replace(/s/g,"&#1587;").replace(/d/gi,"&#1583;").replace(/f/gi,"&#1601;").replace(/H/g,"&#1581;").replace(/h/g,"&#1607;").replace(/j/g,"&#1688;").replace(/K/g,"&#1582;").replace(/k/g,"&#1603;").replace(/l/g,"&#1604;").replace(/&#351;/gi,"&#1588;").replace(/z/gi,"&#1586;").replace(/Z/gi,"&#1592;").replace(/x/gi,"&#1582;").replace(/c/gi,"&#1580;").replace(/v/gi,"&#1608;").replace(/b/gi,"&#1576;").replace(/n/gi,"&#1606;").replace(/m/gi,"&#1605;").replace(/ç/gi,"&#1670;").replace(/a/g,"&#1575;").replace(/&#1578;'/g,"&#1579;").replace(/&#1581;'/g,"&#1582;").replace(/&#1583;'/g,"&#1584;").replace(/&#1585;'/g,"&#1586;").replace(/&#1587;'/g,"&#1588;").replace(/S/g,"&#1589;").replace(/&#1589;'/g,"&#1590;").replace(/D/g,"&#1590;").replace(/T/g,"&#1591;").replace(/&#1591;'/g,"&#1592;").replace(/&#1594;'/g,"&#1594;").replace(/&#1607;'/g,"&#1577;").replace(/o/g,"&#1608;").replace(/&#1608;&#1608;/g,"&#1608;").replace(/-/g,"&#1569;").replace(/&#1608;&#1569;/g,"&#1572;").replace(/&#1610;&#1569;/g,"&#1574;").replace(/A/g,"&#1573;").replace(/&#1569;&#1575;/g,"&#1571;").replace(/"/g,"&#1593;").replace(/â/g,"&#1570;").replace(/[\u015B\u015A\u0161\u015F]/gi,"&#1588;").replace(/[\u011F]/gi,"&#1594;");

document.getElementById("gizli-div").innerHTML=car;car=document.getElementById("gizli-div").innerHTML;document.conversion.saisie.value=car;var a=document.conversion.saisie;a.focus();a.scrollTop=a.scrollHeight};</script>

<div style="width: 98%;"><form name="conversion">
 
<p class="arabic-klavye"><input type="button" class="bf" onclick="conversion.saisie.select();copy()" value="Kopyala"> 
<input type="button" class="bf" onclick="reset();conversion.saisie.focus()" value="Hepsini Sil "></p>

 <p><textarea id="area" class="arabic" accept-charset="UTF-8" dir="rtl" onkeyup="transcrire()" style="padding: 5px; font-size: 23pt; width: 99%; color: rgb(0, 0, 0);" name="saisie" rows="5" cols="40"></textarea></p>
 
<h3 class="arabic-klavye">Arapça ve Osmanl&#305;ca Harfler</h3>
 
<p class="arabic-klavye" dir="rtl">
<input class="tus arabic" type="button" onclick="yazdir(1569)" value="&#1569;"> 

<input class="tus arabic" type="button" onclick="yazdir(1570)" value="&#1570;">
<input class="tus arabic" type="button" onclick="yazdir(1573)" value="&#1573;"> 
<input class="tus arabic" type="button" onclick="yazdir(1571)" value="&#1571;">  
<input class="tus arabic" type="button" onclick="yazdir(1649)" value="&#1649;"> 
<input class="tus arabic" type="button" onclick="yazdir(1575)" value="&#1575;">
<input class="tus arabic" type="button" onclick="yazdir(1576)" value="&#1576;"> 
<input class="tus arabic" type="button" onclick="yazdir(1662)" value="&#1662;"> 
<input class="tus arabic" type="button" onclick="yazdir(1578)" value="&#1578;"> 
<input class="tus arabic" type="button" onclick="yazdir(1579)" value="&#1579;"> 
<input class="tus arabic" type="button" onclick="yazdir(1580)" value="&#1580;"> 
<input class="tus arabic" type="button" onclick="yazdir(1581)" value="&#1581;"> 
<input class="tus arabic" type="button" onclick="yazdir(1670)" value="&#1670;"> 
<input class="tus arabic" type="button" onclick="yazdir(1582)" value="&#1582;"> 
<input class="tus arabic" type="button" onclick="yazdir(1583)" value="&#1583;"> 
<input class="tus arabic" type="button" onclick="yazdir(1584)" value="&#1584;"> 
<input class="tus arabic" type="button" onclick="yazdir(1585)" value="&#1585;"> 
<input class="tus arabic" type="button" onclick="yazdir(1586)" value="&#1586;"> 
<input class="tus arabic" type="button" onclick="yazdir(1688)" value="&#1688;"> 
<input class="tus arabic" type="button" onclick="yazdir(1587)" value="&#1587;">
<input class="tus arabic" type="button" onclick="yazdir(1588)" value="&#1588;"> 
<input class="tus arabic" type="button" onclick="yazdir(1589)" value="&#1589;"> 
<input class="tus arabic" type="button" onclick="yazdir(1590)" value="&#1590;"> 
<input class="tus arabic" type="button" onclick="yazdir(1591)" value="&#1591;"> 
<input class="tus arabic" type="button" onclick="yazdir(1592)" value="&#1592;"> 
<input class="tus arabic" type="button" onclick="yazdir(1593)" value="&#1593;"> 
<input class="tus arabic" type="button" onclick="yazdir(1594)" value="&#1594;"> 
<input class="tus arabic" type="button" onclick="yazdir(1601)" value="&#1601;"> 
<input class="tus arabic" type="button" onclick="yazdir(1602)" value="&#1602;"> 
<input class="tus arabic" type="button" onclick="yazdir(1603)" value="&#1603;"> 
<input class="tus arabic" type="button" onclick="yazdir(1709)" value="&#64467;"> 
<input class="tus arabic" type="button" value="&#1711;" onclick="yazdir(1711)">
<input class="tus arabic" type="button" onclick="yazdir(1604)" value="&#1604;"> 
<input class="tus arabic" type="button" onclick="yazdir(1605)" value="&#1605;">
<input class="tus arabic" type="button" onclick="yazdir(1606)" value="&#1606;"> 
<input class="tus arabic" type="button" onclick="yazdir(1608)" value="&#1608;"> 
<input class="tus arabic" type="button" onclick="yazdir(1572)" value="&#1572;"> 
<input class="tus arabic" type="button" onclick="yazdir(1607)" value="&#1607;"> 
<input class="tus arabic" type="button" onclick="yazdir(1577)" value="&#1577;"> 
<input class="tus arabic" type="button" onclick="yazdir(1610)" value="&#1610;"> 
<input class="tus arabic" type="button" onclick="yazdir(1574)" value="&#1574;"> 
<input class="tus arabic" type="button" onclick="yazdir(1609)" value="&#1609;"> 
<input class="tus" type="button" onclick="yazdir(0040)" value="BO&#350;LUK"></p>

 <h3 class="arabic-klavye">Harekeler</h3>
 <p class="arabic-klavye">
<input class="tus full arabic" type="button" onclick="yazdir(1619)" value="&#1619;&nbsp;&#1614;"> 
<input class="tus full arabic" type="button" onclick="yazdir(1614)" value="&nbsp;&#1614;"> 
<input class="tus full arabic" type="button" onclick="yazdir(1616)" value="&nbsp;&#1616;"> 
<input class="tus full arabic" type="button" onclick="yazdir(1615)" value="&nbsp;&#1615;"> 
<input class="tus full arabic" type="button" onclick="yazdir(1611)" value="&nbsp;&#1611;"> 
<input class="tus full arabic" type="button" onclick="yazdir(1613)" value="&nbsp;&#1613;">
<input class="tus full arabic" type="button" onclick="yazdir(1612)" value="&nbsp;&#1612;"> 
<input class="tus full arabic" type="button" onclick="yazdir(1617)" value="&nbsp;&#1617;"> 
<input class="tus full arabic" type="button" onclick="yazdir(1618)" value="&nbsp;&#1618;"> 
</p>

<p><script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block; text-align:center;" data-ad-format="fluid" data-ad-layout="in-article" data-ad-client="ca-pub-9497855579350422" data-ad-slot="9535069048"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script></p>

<h3 class="arabic-klavye">Kal&#305;plar</h3>
<p class="arabic-klavye" dir="rtl">
<input class="tus arabic" type="button" value="&#65021;" onclick="yazdir(65021)"> 
<input class="tus arabic" type="button" value="&#65010;" onclick="yazdir(65010)"> 
<input class="tus arabic" type="button" value="&#65019;" onclick="yazdir(65019)"> 
<input class="tus arabic" type="button" value="&#65012;" onclick="yazdir(65012)"> 
<input class="tus arabic" type="button" value="&#65018;" onclick="yazdir(65018)"> 
<input class="tus arabic" type="button" value="&#65014;" onclick="yazdir(65014)"> 
<input class="tus arabic" type="button" value="&#65017;" onclick="yazdir(65017)"> 
<input class="tus arabic" type="button" value="&#65015;" onclick="yazdir(65015)"> 
<input class="tus arabic" type="button" value="&#65016;" onclick="yazdir(65016)"> 
<input class="tus arabic" type="button" value="&#65013;" onclick="yazdir(65013)"> 
<input class="tus arabic" type="button" value="&#65011;" onclick="yazdir(65011)"> 
<input class="tus arabic" type="button" value="&#65009;" onclick="yazdir(65009)"> 
</p>

 <h3 class="arabic-klavye">Say&#305;lar</h3>
 <p class="arabic-klavye">
<input class="tus arabic" type="button" onclick="yazdir(1776)" value="&#1776;"> 
<input class="tus arabic" type="button" onclick="yazdir(1777)" value="&#1777;"> 
<input class="tus arabic" type="button" onclick="yazdir(1778)" value="&#1778;"> 
<input class="tus arabic" type="button" onclick="yazdir(1779)" value="&#1779;"> 
<input class="tus arabic" type="button" onclick="yazdir(1780)" value="&#1636;"> 
<input class="tus arabic" type="button" onclick="yazdir(1781)" value="&#1637;"> 
<input class="tus arabic" type="button" onclick="yazdir(1782)" value="&#1638;"> 
<input class="tus arabic" type="button" onclick="yazdir(1783)" value="&#1639;"> 
<input class="tus arabic" type="button" onclick="yazdir(1784)" value="&#1640;"> 
<input class="tus arabic" type="button" onclick="yazdir(1785)" value="&#1641;"></p>
 
<h3 class="arabic-klavye">Semboller</h3>
 <p class="arabic-klavye">
</p>

 <p class="arabic-klavye" dir="rtl">

<input class="tus arabic" type="button" onclick="yazdir(46)" value="."> 
<input class="tus arabic" type="button" onclick="yazdir(1548)" value="&#1548;"> 
<input class="tus arabic" type="button" onclick="yazdir(1563)" value="&#1563;"> 
<input class="tus arabic" type="button" onclick="yazdir(58)" value=":"> 
<input class="tus arabic" type="button" onclick="yazdir(1567)" value="&#1567;"> 
<input class="tus arabic" type="button" onclick="yazdir(33)" value="!"> 
<input class="tus arabic" type="button" onclick="yazdir(1566)" value="&#1566;"> 
<input class="tus arabic" type="button" onclick="yazdir(95)" value="_"> 
<input class="tus arabic" type="button" onclick="yazdir(96)" value="`"> 
<input class="tus arabic" type="button" onclick="yazdir(39)" value="'"> 
<input class="tus arabic" type="button" onclick="yazdir(94)" value="^"> 
<input class="tus arabic" type="button" onclick="yazdir(1624)" value="&#1626;"> 
<input class="tus arabic" type="button" onclick="yazdir(34)" value="&ldquo;"> 

<input class="tus arabic" type="button" onclick="yazdir(1757)" value="&#1757;"> 
<input class="tus arabic" type="button" onclick="yazdir(1758)" value="&#1758;"> 
<input class="tus arabic" type="button" onclick="yazdir(1769)" value="&#1769;"> 
<input class="tus arabic" type="button" onclick="yazdir(64831)" value="&#64831;"> 
<input class="tus arabic" type="button" onclick="yazdir(64830)" value="&#64830;"> 
<input class="tus" type="button" onclick="yazdir(41)" value="("> 
<input class="tus" type="button" onclick="yazdir(40)" value=")"> 
<input class="tus" type="button" onclick="yazdir(123)" value="{"> 
<input class="tus" type="button" onclick="yazdir(125)" value="}"> 
<input class="tus" type="button" onclick="yazdir(93)" value="["> 
<input class="tus" type="button" onclick="yazdir(91)" value="]"> 

<input class="tus" type="button" onclick="yazdir(42)" value="*"> 
<input class="tus arabic" type="button" onclick="yazdir(1645)" value="&#1645;"> 
<input class="tus" type="button" onclick="yazdir(92)" value="\"> 
<input class="tus" type="button" onclick="yazdir(47)" value="/"> 
<input class="tus" type="button" onclick="yazdir(43)" value="+"> 
<input class="tus" type="button" onclick="yazdir(45)" value="-"> 
<input class="tus" type="button" onclick="yazdir(126)" value="~"> 
<input class="tus" type="button" onclick="yazdir(62)" value="&lt;" _=""> 
<input class="tus" type="button" onclick="yazdir(61)" value="="> 
<input class="tus" type="button" onclick="yazdir(60)" value="&gt;"> 
<input class="tus" type="button" onclick="yazdir(124)" value="|"> 
<input class="tus arabic" type="button" onclick="yazdir(1542)" value="&#1542;"> 
<input class="tus arabic" type="button" onclick="yazdir(1543)" value="&#1543;"> 

<input class="tus" type="button" onclick="yazdir(35)" value="#"> 
<input class="tus" type="button" onclick="yazdir(36)" value="$"> 
<input class="tus" type="button" onclick="yazdir(37)" value="%"> 
<input class="tus" type="button" onclick="yazdir(38)" value="&amp;"> 
<input class="tus" type="button" onclick="yazdir(64)" value="@"> 

<input class="tus arabic" type="button" onclick="yazdir(1646)" value="&#1646;"> 
<input class="tus arabic" type="button" onclick="yazdir(1657)" value="&#1657;"> 
<input class="tus arabic" type="button" onclick="yazdir(1706)" value="&#1706;"> 
<input class="tus arabic" type="button" onclick="yazdir(1722)" value="&#1722;"> 
<input class="tus arabic" type="button" onclick="yazdir(1723)" value="&#1723;"> 
<input class="tus arabic" type="button" onclick="yazdir(1647)" value="&#1647;"> 

<input class="tus arabic" type="button" onclick="yazdir(65143)" value="&#65143;"> 
<input class="tus arabic" type="button" onclick="yazdir(65147)" value="&#65147;"> 
<input class="tus arabic" type="button" onclick="yazdir(65145)" value="&#65145;"> 
<input class="tus arabic" type="button" onclick="yazdir(65137)" value="&#65137;"> 
<input class="tus arabic" type="button" onclick="yazdir(65151)" value="&#65151;"> 
<input class="tus arabic" type="button" onclick="yazdir(65149)" value="&#65149;"> 

</p></form></div>

<p class="pagination"><a href="https://arapcaosmanlicaklavye.glitch.me/">HARUN PEHLİVAN'ın Yazd&#305;&#287;&#305; Di&#287;er Arapça Osmanlıca Klavye &#10095;</a></p><style type="text/css">.pagination{display:inline-block; width:none}.pagination a{color:black; float:left; padding:8px 16px; text-decoration:none; transition:background-color.3s; border:1px solid #ddd; margin-right:4px}.pagination a.active{background-color:#6699FF; color:white; border:1px solid #0066FF}.pagination a:hover:not(.active){background-color:#ddd; border:1px solid #000}</style>

<div id="gizli-div" style="display:none"></div>

<style type="text/css">
.arabic-klavye{text-align:right}
input.arabic{font-size:23px}
input.full{min-width:50px;}
.red{color:#a30 !immortant;}
.tus{min-height:50px;}
</style><br />
