{
"wallpaper":"https://picsum.photos/1280/720/?blur=10",
//"spider":"https://notabug.org/tomb003/CatVodTVSpider/raw/master/jar/custom_spider.jar",


# spider (æ©ä¸ä½¿ç¨ð)
## 01.ð¼ç¼åæ¥å£
"spider":"https://gitee.com/hd2019/OneClickRun/raw/master/xpath/custom_spider.jar",
## 02.ðææ¥å£
//"spider":"https://gitee.com/hd2019/OneClickRun/raw/master/xpath/xm.jar",
## 03.ð±Sæ¥å£
//"spider":"https://gitee.com/hd2019/OneClickRun/raw/master/xpath/baikan.jar",




# ç´æ­ (æ©ä¸ä½¿ç¨ð)
## 01.ð¦ç´æ­
## --> spider æ¹ baikan.jar æ custom_spider.jar
"lives":[{"group":"redirect","channels":[{"name":"live","urls":["proxy://do=live&type=txt&ext=aHR0cHM6Ly9jZG4uanNkZWxpdnIubmV0L2doL1l1YW5Ic2luZy9PbmVDbGlja1J1bkBtYXN0ZXIveHBhdGgvbGl2ZS50eHQ="]}]}],


## 02.ð¦ç´æ­
## --> spider æ¹ xm.jar
## --> ä½¿ç¨ "02.ðææ¥å£"æ¶,ç´æ­è¦æ¹æ "02.ð¦ç´æ­ ", éé "ðè®¾ç½®ç´æ­ä¸ºé¦é¡µ" è¿ä¸ªåè½)
//"lives":[{"group":"redirect","channels":[{"name":"redirect","urls":["proxy://do=tvfix&type=list"]}]}],




"sites":[
## 01.ð¼ç¼åæ¥å£
## --> spider æ¹ custom_spider.jar
{"key":"csp_CZSPP","name":"ð¼åé¿èµæº(SP)","type":3,"api":"csp_CZSPP","searchable":1,"quickSearch":1,"filterable":0},
{"key":"csp_Auete","name":"ð¼å®å¨æµè¯(SP)","type":3,"api":"csp_Auete","searchable":1,"quickSearch":0,"filterable":1,"ext":""},
{"key":"csp_AliPanSou","name":"ð¼åµç¸çæï¼ä»æ¯ææç´¢ï¼","type":3,"api":"csp_AliPanSou","searchable":1,"quickSearch":1,"filterable":0},
{"key":"csp_Lgyy","name":"ð¼èåå½±é¢(SP)","type":3,"api":"csp_Lgyy","searchable":1,"quickSearch":1,"filterable":1,"ext":""},
{"key":"csp_Zxzj","name":"ð¼å¨çº¿ä¹å®¶(SP)","type":3,"api":"csp_Zxzj","searchable":1,"quickSearch":1,"filterable":1,"ext":""},
{"key":"csp_Cokemv","name":"ð¼å®å¨æµè¯(SP)","type":3,"api":"csp_Cokemv","searchable":1,"quickSearch":1,"filterable":1,"ext":""},
{"key":"csp_Fantuan","name":"ð¼é¥­å¢(SP)","type":3,"api":"csp_Fantuan","searchable":1,"quickSearch":1,"filterable":1,"ext":""},
{"key":"csp_Qicui","name":"ð¼å¥ç²¹(SP)","type":3,"api":"csp_Qicui","searchable":1,"quickSearch":1,"filterable":1,"ext":""},
{"key":"csp_DY1990","name":"ð¼90(SP)","type":3,"api":"csp_DY1990","searchable":1,"quickSearch":1,"filterable":0},




## 02.ðææ¥å£
## --> spider æ¹ xm.jar, (XPathç³»å ä¸å¯ç¨, APPå½±è§è§å ä¸å¯ç¨, èµæºç½éé å¯ç¨)
## --> ç´æ­ æ¹ "02.ð¦ç´æ­"
## ç¸è¾äº"ç¼åæ¥å£", å¤äº"ä¸ä¸" & æ­£å¸¸ç"å°çº¸æ¡" & "åçªÂ·æ°å´Â·ç½åªå£°" & "è®¾ç½®ç´æ­ä¸ºé¦é¡µ", å°é²ç¨!
//{"key":"csp_CZSPP","name":"ðåé¿èµæº","type":3,"api":"csp_CZSPP","searchable":1,"quickSearch":1,"filterable":0},
//{"key":"csp_NaNa","name":"ðä¸ä¸","type":3,"api":"csp_NaNa","searchable":1,"quickSearch":1,"filterable":0},
//{"key":"csp_Live","name":"ðè®¾ç½®ç´æ­ä¸ºé¦é¡µ","type":3,"api":"csp_Live","searchable":0,"quickSearch":0,"filterable":0},




## 03.ð±Sæ¥å£
## --> spider æ¹ baikan.jar
//{"key":"360_spider","name":"ð±360(å®æº)","type":3,"api":"csp_YS360","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/360.json"},
//{"key":"ftys_spider","name":"ð±é¥­å¢(SP)","type":3,"api":"csp_Ftys","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/fantuan.bmp"},




## XPathç³»å, APPå½±è§è§å, èµæºç½éé
{"key":"csp_xpath_huya","name":"èç(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/huya2.json"},
{"key":"csp_xpath_kuqimv","name":"é·å¥MV(XP)","type":3,"api":"csp_XPath","searchable":0,"quickSearch":0,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/kuqimv.json"},
{"key":"csp_xpath_6d","name":"å­åº¦TV(XPF)","type":3,"api":"csp_XPathFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/6d.json"},
{"key":"csp_xpath_zxzj2","name":"å¨çº¿ä¹å®¶(XPF)","type":3,"api":"csp_XPathFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/zxzj2.json"},
{"key":"csp_xpath_libv","name":"Libvio(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/libv.json"},
{"key":"csp_xpath_4kpianku","name":"4kçåºç½(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/4kpianku.json"},
{"key":"csp_xpath_doujiaow","name":"è±è§ç½(XPF)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/doujiaow.json"},
{"key":"csp_xpath_auete","name":"Aueteå½±è§(XPF)","type":3,"api":"csp_XPathFilter","searchable":1,"quickSearch":0,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/auete.json"},
{"key":"csp_xpath_yanetflix","name":"é¸­å¥é£(XPF)","type":3,"api":"csp_XPathFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/yanet.json"},
{"key":"csp_xpath_ddg","name":"è¾¾è¾¾é¾(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/dadagui.json"},
{"key":"csp_xpath_789kp","name":"789çç(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/789kp.json"},
{"key":"csp_xpath_348z","name":"348çµå½±(XPF)","type":3,"api":"csp_XPathFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/348z.json"},
{"key":"csp_xpath_dandanzan10","name":"èèèµ(çµå½±)(XPF)","type":3,"api":"csp_XPathFilter","searchable":0,"quickSearch":0,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/dandanzan10.json"},
{"key":"csp_xpath_cokemv","name":"Cokemv(XPF)","type":3,"api":"csp_XPathFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/cokemv.json"},
{"key":"csp_xpath_jpys","name":"æåå½±è§(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/jpys.json"},
{"key":"Jumi","name":"å§è¿·TV(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/Jumi.json"},
{"key":"csp_xpath_lranc","name":"å¤©å¤©å½±è§(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/lranc.json"},
{"key":"csp_xpath_dmntv","name":"å¼¹å¹å½±é¢(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/dmntv.json"},
{"key":"csp_xpath_dmw","name":"å¨æ¼«å²(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/dmw.json"},


{"key":"csp_xpath_huohuo99","name":"ç«ç«å½±è§(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/huohuo99.json"},
{"key":"csp_XPath_bidiys","name":"ååå½±è§(XP)","type":3,"api":"csp_XPathFilter","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/bidiys.json"},
{"key":"csp_xpath_xqmi","name":"å°å¼ºè¿·(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/xqmi.json"},
{"key":"csp_xpath_vip1280","name":"VIPçµå½±(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/vip1280.json"},
{"key":"csp_xpath_zzzlike","name":"å¨æ«çµå½±(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/zzzlike.json"},
{"key":"csp_xpath_tjyy","name":"å¥ä¼å½±é¢(XP)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/huigutongying.json"},
{"key":"csp_xpath_yyotv","name":"å°å¤ªé³(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/yyotv.json"},
{"key":"csp_xpath_aidi","name":"ç±è¿ªå½±è§(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/aidi.json"},
{"key":"csp_xpath_lezhutv","name":"ä¹çªTV(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/lezhutv.json"},
{"key":"csp_xpath_saohuotv","name":"éªç«çµå½±(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/saohuotv2.json"},
{"key":"csp_xpath_pianba","name":"çå§å½±é¢(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/pianba.json"},
{"key":"csp_xpath_duboku","name":"ç¬æ­åº(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/duboku2.json"},
{"key":"csp_xpath_lkvod","name":"æ¥çç¹æ­(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/lkvod.json"},
{"key":"csp_xpath_94sm","name":"94ç¥é©¬(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/94sm.json"},
{"key":"csp_xpath_zj883","name":"è¿½å§ç½(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/zj883.json"},




# Mæµè§å¨ä¸­APPå½±è§è§åæ¯æ(AppYsV2)
#APPå½±è§(å¤§ç)
{"key":"csp_appysv2_æµæ","name":"æµæ(M2)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://fkxs2233.com/mogai_api.php/v1.vod"},
{"key":"csp_appysv2_ææ","name":"ææ(M2)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://szys5678.com/mogai_api.php/v1.vod"},


#
#ä¼è´¨
{"key":"csp_appysv2_éç¹å½±è§","name":"éç¹å½±è§(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://app.zteys.com/api.php/v1.vod"},
{"key":"csp_appysv2_å½±éé","name":"å½±éé(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://221.236.18.12:665/api.php/v1.vod"},
//{"key":"csp_appysv2_ä¼è§å½±è§","name":"ä¼è§å½±è§(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://app.ysys.asia/lvdou_api.php/v1.vod"},
{"key":"csp_appysv2_å½±è§å¤§å¨","name":"å½±è§å¤§å¨(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://app.okmedcos.com/api.php/v1.vod"},
//{"key":"csp_appysv2_é¨æå½±è§","name":"é¨æå½±è§(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://123.youguo520.top/lvdou_api.php/v1.vod"},
{"key":"csp_appysv2_æåå½±è§","name":"æåå½±è§(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://app.bl210.com/api.php/v1.vod"},
//{"key":"csp_appysv2_å¥éè¿·","name":"å¥éè¿·(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://app.netflixmi.com/api.php/v1.vod"},
{"key":"csp_appysv2_ç¾å§è","name":"ç¾å§è(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://ttzmz.net/api.php/v1.vod"},
{"key":"csp_appys_ç¾å§è«","name":"ç¾å§è«(ä¼)","type":3,"api":"csp_AppYs","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://meijuchong.com/api.php/v1.vod"},
{"key":"csp_appysv2_éº»çè§é¢","name":"éº»çè§é¢(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://aliyun.k8aa.com/mogai_api.php/v1.vod"},
{"key":"csp_appysv2_ççå½±è§","name":"ççå½±è§(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://fgyuu.top/lehailb_api.php/v1.vod"},
{"key":"csp_appysv2_æç«çµå½±","name":"æç«çµå½±(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://lanmao.lanmaoymw.cn/api.php/v1.vod"},
{"key":"csp_appysv2_é¶å»å½±é¢","name":"é¶å»å½±é¢(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://ys.ling00.cn/api.php/v1.vod"},
{"key":"csp_appysv2_ççå½±è§","name":"ççå½±è§(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://kk.ccboke.top/ruifenglb_api.php/v1.vod"},
{"key":"csp_appysv2_é£é£å½±é¢","name":"é£é£å½±é¢(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://yidayy.top/lehailb_api.php/v1.vod"},
//{"key":"csp_appysv2_èç«è§é¢","name":"èç«è§é¢(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://vv.humaoweb.com/mogai_api.php/gctvapi.vod"},
{"key":"csp_appysv2_çç¸å¨æ¼«","name":"çç¸å¨æ¼«(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://ak.baicai.buzz/lvdou_api.php/v1.vod"},
{"key":"csp_appysv2_ç²è±¡è§ç","name":"ç²è±¡è§ç(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://42.157.129.15:34444/lvdou_api.php/v1.vod"},
//{"key":"csp_appysv2_é£æ·å½±è§","name":"é£æ·å½±è§(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://fjkkk.cn/api.php/v1.vod"},
{"key":"csp_appysv2_é¥­åçµå½±","name":"é¥­åçµå½±(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://yinliub.cn/lvdou_api.php/v1.vod"},
{"key":"csp_appysv2_æ®µåå½±è§","name":"æ®µåå½±è§(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://shangjihuoke.com/api.php/tv.vod"},
{"key":"csp_appysv2_æ®µåå½±è§2","name":"æ®µåå½±è§2(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://121.204.249.135:4433/ruifenglb_api.php/v1.vod"},
{"key":"csp_appysv2_ç¬æ­ç¤¾","name":"ç¬æ­ç¤¾(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://35ys.cc/api.php/v1.vod"},
{"key":"csp_appysv2_å·åè§é¢","name":"å·åè§é¢(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://www.cx99999.cn/lvdou_api.php/v1.vod"},
{"key":"csp_appysv2_ç±é·å½±è§","name":"ç±é·å½±è§(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://www.zhanlangbu.com/ruifenglb_api.php/v1.vod"},
{"key":"csp_appysv2_DCå½±è§","name":"DCå½±è§(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://chaorenbb.com/api.php/v1.vod"},
{"key":"csp_appysv2_300çä¸ç","name":"300çä¸ç(ä¼)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://300ys.xyz/mogai_api.php/v1.vod"},
#
#æ®é
{"key":"csp_appysv2_ä½çå½±è§","name":"ä½çå½±è§(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://yu.cuicanys.cn/lvdou_api.php/v1.vod"},
{"key":"csp_appysv2_å½±è§ç«","name":"å½±è§ç«(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://vip.wscyun.com/api.php/v1.vod"},
{"key":"csp_appysv2_æå¿å½±è§","name":"æå¿å½±è§(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://yue52.xyz/api.php/v1.vod"},
{"key":"csp_appysv2_çç«è§é¢","name":"çç«è§é¢(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://anegh.com/lvdou_api.php/v1.vod"},
{"key":"csp_appys_ä¸æ¥å½±é¢","name":"ä¸æ¥å½±é¢(æ®)","type":3,"api":"csp_AppYs","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://www.3ri.net/api.php/v1.vod"},
{"key":"csp_appysv2_æ¥è¯å½±è§","name":"æ¥è¯å½±è§(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://tv.rcz168.com/api.php/v1.vod"},
{"key":"csp_appysv2_ç¾¤é«å½±è§","name":"ç¾¤é«å½±è§(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://www.qunxinys.com/api.php/v1.vod"},
{"key":"csp_appysv2_è²å¬è±è§é¢","name":"è²å¬è±è§é¢(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://www.pgy1.top/ruifenglb_api.php/v1.vod"},
{"key":"csp_appysv2_ç¾å§è¿·","name":"ç¾å§è¿·(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://mj.zjtv.cc/ruifenglb_api.php/v1.vod"},
{"key":"csp_appysv2_å·è§TV","name":"å·è§TV(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://len.tv/api.php/v1.vod"},
{"key":"csp_appysv2_åæ¨å½±è§","name":"åæ¨å½±è§(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://vip.wscyun.com/api.php/v1.vod"},
{"key":"csp_appysv2_é·ç§è§ç","name":"é·ç§è§ç(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://cms.kumiaotv.cn/api.php/v1.vod"},
{"key":"csp_appysv2_å¿«çå½±è§","name":"å¿«çå½±è§(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://kuaikys.com/mogai_api.php/v1.vod"},
{"key":"csp_appysv2_çå§VIP","name":"çå§VIP(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://app.ppli.xyz/api.php/v1.vod"},
{"key":"csp_appysv2_çèèµæº","name":"çèèµæº(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://android.jiusi.vip/mogai_api.php/v1.vod"},
{"key":"csp_appysv2_æé·å½±è§","name":"æé·å½±è§(æ®)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://jiku.vip/mogai_api.php/v1.vod"},
#
#ç¥é©¬
{"key":"csp_appysv2_å½±è§é","name":"å½±è§é(ç¥é©¬)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://216.98.10.85/api.php/iptv/vod/"},
{"key":"csp_appysv2_å°çç«TV","name":"å°çç«TV(ç¥é©¬)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://tv2.hetaoys.vip/api.php/iptv/vod/"},
{"key":"csp_appysv2_å°åTV","name":"å°åTV(ç¥é©¬)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://n293.ngys.xyz/mv/api.php/Chengcheng/vod/"},
{"key":"csp_appysv2_å¤©ç©ºTV","name":"å¤©ç©ºTV(ç¥é©¬)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://tv.tkys.tv/api.php/iptv/vod/"},
{"key":"csp_appysv2_å±±æ¥å½±è§","name":"å±±æ¥å½±è§(ç¥é©¬)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://dy6.dcd1.cn/api.php/iptv/vod/"},
//{"key":"csp_appysv2_æ æª¬TV","name":"æ æª¬TV(ç¥é©¬)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://106.12.113.90:7575/api.php/iptv/vod/"},
{"key":"csp_appysv2_èè¿TV","name":"èè¿TV(ç¥é©¬)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://www.hdyangtv.com/api.php/iptv/vod/"},
{"key":"csp_appysv2_èå¤å½±è§","name":"èå¤å½±è§(ç¥é©¬)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://jdys.weetai.cn/api.php/iptv/vod/"},
{"key":"csp_appysv2_çå­è§ç","name":"çå­è§ç(ç¥é©¬)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://eh.tvzy.cc/api.php/iptv/vod/"},
{"key":"csp_appysv2_ç±è¥¿è¥¿TV","name":"ç±è¥¿è¥¿TV(ç¥é©¬)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://tv2.aixixi.vip/api.php/iptv/vod/"},
{"key":"csp_appysv2_CVå½±è§","name":"CVå½±è§(ç¥é©¬)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://www.cccvvv.top/api.php/iptv/vod/"},
{"key":"csp_appysv2_369TV","name":"369TV(ç¥é©¬)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://8.142.23.147:555/api.php/Chengcheng/vod/"},
{"key":"csp_appysv2_2å·å¸","name":"2å·å¸(ç¥é©¬)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://phoebe.cf/api.php/iptv/vod/"},
#




# å¹¿å¤§ä¾  èµæºç½éé
#å®æ¹è§£æ
{"key":"å¤©å èµæº","name":"å¤©å èµæº(å®)","type":1,"api":"http://vipmv.cc/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
{"key":"M3U8.TVèµæº","name":"M3U8.TVèµæº(å®)","type":1,"api":"http://www.zycaiji.net:7788/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
{"key":"éºéºèµæº","name":"éºéºèµæº(å®)","type":1,"api":"http://www.qilinzyz.com/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
{"key":"æ±åèµæº","name":"æ±åèµæº(å®)","type":1,"api":"https://gfzycj.hnmj.vip/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
{"key":"æå¤å®é","name":"æå¤å®é(å®)","type":1,"api":"http://zy.sgyun.me/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
{"key":"æä¸å®é","name":"æä¸å®é(å®)","type":1,"api":"https://gcku.suboyun.vip/api.php/provide/vod/","playUrl":"https://www.xing1.vip/player/dp/?url=","searchable":1,"quickSearch":1},
{"key":"wabc(è¾è®¯ç´é)","name":"wabc(è¾è®¯ç´é)(å®)","type":1,"api":"https://wabc.ml/mao/1.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
//{"key":"çåº","name":"çåº(å®)","type":1,"api":"https://pianku.wang/api.php/provide/vod/","searchable":0,"quickSearch":0},
{"key":"çç«","name":"çç«(å®)","type":1,"api":"http://124.222.83.15:88/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
{"key":"å¿æ¢¦","name":"å¿æ¢¦(å®)","type":1,"api":"http://anltv.cn/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
//{"key":"åçå®é","name":"åçå®é(å®)","type":1,"api":"http://vip-02.tgzy.cc/api.php/provide/vod/","searchable":0,"quickSearch":0},
{"key":"æéå®é","name":"æéå®é(å®)","type":1,"api":"http://gc.zhuijuba.vip/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"å¥¥ç¹æ¼èµæº","name":"å¥¥ç¹æ¼èµæº(å®)","type":1,"api":"https://aotemanzy.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"éªäººå®é","name":"éªäººå®é(å®)","type":1,"api":"https://zl.chinafix.wang/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"æ¨å­çå§","name":"æ¨å­çå§(å®)","type":1,"api":"https://mzkj.maccms.cf/api.php/provide/vod/","searchable":1,"quickSearch":1},
#
#åçèµæº
{"key":"FOXèµæº","name":"FOXèµæº(å)","type":1,"api":"https://api.foxzyapi.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"ç¥éèµæº","name":"ç¥éèµæº(å)","type":1,"api":"https://api.sszyapi.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"åéèµæº","name":"åéèµæº(å)","type":1,"api":"https://api.guangsuapi.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"æ°æµªèµæº","name":"æ°æµªèµæº(å)","type":1,"api":"http://api.xinlangapi.com/xinlangapi.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"å¿«æ­èµæº","name":"å¿«æ­èµæº(å)","type":1,"api":"http://www.kuaibozy.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"å«æèµæº","name":"å«æèµæº(å)","type":1,"api":"http://cj.bajiecaiji.com/inc/apijson_vod.php","searchable":0,"quickSearch":0},
{"key":"ç¾åº¦èµæº","name":"ç¾åº¦èµæº(å)","type":1,"api":"https://api.apibdzy.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"æ å°½èµæº2","name":"æ å°½èµæº2(å)","type":1,"api":"https://wuzy9.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"æ å°½èµæº","name":"æ å°½èµæº(å)","type":1,"api":"https://wujinzy.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
//{"key":"å¤©ç©ºèµæº","name":"å¤©ç©ºèµæº(å)","type":1,"api":"https://api.tiankongapi.com/api.php/provide/vod/","searchable":0,"quickSearch":0},
{"key":"ä¹å¤èµæº","name":"ä¹å¤èµæº(å)","type":0,"api":"http://cj.leduocaiji.com/inc/api.php","playUrl":"json:https://api.leduotv.com/wp-api/getvodurl.php?vid=","searchable":1,"quickSearch":1},
//{"key":"èåèµæº","name":"èåèµæº(å)","type":1,"api":"https://ziyuan.juhesys.com/api.php/provide/vod/","searchable":0,"quickSearch":0},
{"key":"åå½å½±æº","name":"åå½å½±æº(å)","type":1,"api":"http://api.nguonphim.tv/api.php/provide/vod/","searchable":1,"quickSearch":1},
#
#ä¼è´¨èµæº
{"key":"å½±ä¸ç","name":"å½±ä¸ç(ä¼)","type":1,"api":"https://video.yingworld.vip/api.php/provide/vod/","searchable":1,"quickSearch":1,"categories":["çµå½±","è¿ç»­å§","ç»¼èº","å¨æ¼«"]},
{"key":"é¥­åçµå½±","name":"é¥­åçµå½±(ä¼)","type":1,"api":"http://yinliub.cn/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"èæTV","name":"èæTV(ä¼)","type":1,"api":"https://ikaola.tv/api.php/provide/vod/","playUrl":"https://ikaola.tv/vwnet/dplayer/?url=","searchable":1,"quickSearch":1},
{"key":"ä¸ç¹å½±è§","name":"ä¸ç¹å½±è§(ä¼)","type":1,"api":"https://m3u8.movurl.xyz/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"æå¤å½±é¢","name":"æå¤å½±é¢(ä¼)","type":1,"api":"https://www.siguyy.net/api.php/provide/vod/","searchable":1,"quickSearch":1},


#
#ä¸æ¹èå
{"key":"å½±å¾","name":"å½±å¾(è)","type":1,"api":"https://cj.vodimg.top/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"åå¯å¯å½±è§","name":"åå¯å¯å½±è§(è)","type":1,"api":"https://www.zwcoco.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"å±éæ¥","name":"å±éæ¥(è)","type":1,"api":"https://gqcyy.com/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
{"key":"é·ç«å½±è§","name":"é·ç«å½±è§(è)","type":1,"api":"https://www.pgcms10.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"èç«å½±è§","name":"èç«å½±è§(è)","type":1,"api":"http://www.pangmaotv.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"åå©åå©","name":"åå©åå©(è)","type":1,"api":"https://malimali3.com/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1,"categories":["å½äº§å¨æ¼«","æ¥é©å¨æ¼«","æ¬§ç¾å¨æ¼«","æ¸¯å°å¨æ¼«"]},
{"key":"æµ·å¤çµå½±","name":"æµ·å¤çµå½±(è)","type":1,"api":"https://www.200121.com/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
#
// æ¨éåè½æ©å±ï¼év2.1.0.Beta6åä»¥ä¸çæ¬ï¼
// éè¦å¨éç½®æä»¶ä¸­ï¼å å¥keyä¸ºpush_agentçç«ç¹ï¼æ°æ®è¿åæ ¼å¼åæ®éç¬è«ä¸è´
// æ¯ææ¨éæ­æ¾ç½çé¾æ¥
// https://github.com/catvod/CatVodTVSpider
{"key":"push_agent","name":"æ¨é","type":3,"api":"csp_PushAgent","searchable":0,"quickSearch":0,"filterable":0}
#
],
"lives":[
{"group":"redirect","channels":[
{"name":"live","urls":["proxy://do=live&type=txt&ext=aHR0cHM6Ly9jZG4uanNkZWxpdnIubmV0L2doL1l1YW5Ic2luZy9PbmVDbGlja1J1bkBtYXN0ZXIveHBhdGgvbGl2ZS50eHQ="]}
]}
],
"parses":[
{"name":"è§£æèå","type":3,"url":"Demo"},
{"name":"Jsonå¹¶å","type":2,"url":"Parallel"},
{"name":"Jsonè½®è¯¢","type":2,"url":"Sequence"},
# type1 èå.å¹¶å.è½®è¯¢
{"name":"Pro","type":1,"url":"http://api.vip123kan.vip/?url=","ext":{"flag":["youku","ä¼é·","mgtv","èæ","qq","è¾è®¯","qiyi","ç±å¥èº","qq","å¥èº"]}},
{"name":"bilibili","type":1,"url":"https://vip.23at.cn/home/api?type=ys&uid=4883852&key=adfimsvxzDKNOVX389&url=","ext":{"flag":["bilibili"]}},
{"name":"leduo","type":1,"url":"https://api.ldjx.cc/wp-api/getvodurl.php?token=1001&vid=","ext":{"flag":["leduo"]}},
{"name":"duoduozy2","type":1,"url":"https://a.dxzj88.com/jxjx/dd.php?url=","ext":{"flag":["duoduozy"]}},
{"name":"renrenmi2","type":1,"url":"https://a.dxzj88.com/jxrrm/jiami.php?url=","ext":{"flag":["renrenmi"]}},
{"name":"renrenmi3","type":1,"url":"https://sz.dxzj88.com/jxrjrm/jiaomi.php?url=","ext":{"flag":["renrenmi"]}},
{"name":"Pro2","type":1,"url":"https://vip.rongxingvr.top/api/?type=ys&key=JJEZkZIhzkA4cUtBfR&url=","ext":{"flag":["ltnb","rx","qiyi","ç±å¥èº","qq","å¥èº","sohu","letv","youku","ä¼é·","mgtv","èæ"]}},
{"name":"2","type":1,"url":"https://jx.mczdyw.com/xg.php?url=","ext":{"flag":["mgtv","èæ"]}},
{"name":"3","type":1,"url":"https://www.aiaine.com/api/?key=kVqmG5dAQ5dZTcECw8&url=","ext":{"flag":["youku","ä¼é·","mgtv","èæ","qq","è¾è®¯","qiyi","ç±å¥èº","qq","å¥èº"]}},
{"name":"4","type":1,"url":"https://svip.rongxingvr.top/api/?key=niBgMGXVdCQhsmeEBK&url=","ext":{"flag":["youku","ä¼é·","mgtv","èæ","qq","è¾è®¯","qiyi","ç±å¥èº","qq","å¥èº"]}},
{"name":"8","type":1,"url":"https://app.iminna.com/jx/?url=","ext":{"flag":["youku","ä¼é·","mgtv","èæ","qq","è¾è®¯","qiyi","ç±å¥èº","qq","å¥èº"]}},
{"name":"åå¿å½±è§1","type":1,"url":"http://jhpc.manduhu.com/j1217.php?url=","ext":{"flag":["youku","ä¼é·","qq","è¾è®¯","mgtv","èæ"]}},
{"name":"é£é£å½±é¢2","type":1,"url":"https://vvip.funsline.cn/api/?key=3xWfEoDf4V9p9Y20CR&url=","ext":{"flag":["ziqie","youku","ä¼é·","qiyi","ç±å¥èº","å¥èº","mgtv","èæ","qq","è¾è®¯"]}},
{"name":"æç±çµå½±ç½","type":1,"url":"https://jhpc.manduhu.com/j1217.php?url=","ext":{"flag":["qiyi","ç±å¥èº","å¥èº","mgtv","èæ","youku","ä¼é·","pptv","PPTV"]}},
{"name":"åå¿å½±è§9","type":1,"url":"https://api.m3u8.tv:5678/home/api?type=ys&uid=1931000&key=gktuvyzABEORSYZ135&url=","ext":{"flag":["youku","ä¼é·","qq","è¾è®¯","mgtv","èæ"]}},
{"name":"æ±æ¹è§£æ","type":1,"url":"http://103.40.240.46/jh/?url=","ext":{"flag":["renrenmi","qq","è¾è®¯","youku","ä¼é·","mgtv","èæ","xigua","è¥¿ç"]}},
{"name":"çç","type":1,"url":"https://za.kuanjv.com/?url=","ext":{"flag":["qq","è¾è®¯","qiyi","ç±å¥èº","å¥èº","youku","ä¼é·","mgtv","èæ","æç","sohu","letv","ä¹è§","bilibili","åå©åå©","åå©","xigua","è¥¿ç"]}},
{"name":"æç±çµå½±ç½","type":1,"url":"https://jhpc.manduhu.com/j1217.php?url=","ext":{"flag":["qq","è¾è®¯","qiyi","ç±å¥èº","å¥èº","youku","ä¼é·","mgtv","èæ","ä¹è§","letv","PPTV","pptv","bilibili","åå©åå©","åå©"]}},
{"name":"çå¤è§£æ","type":1,"url":"https://json.pangujiexi.com:12345/json.php?url=","ext":{"flag":["qq","è¾è®¯","qiyi","ç±å¥èº","å¥èº","youku","ä¼é·","mgtv","èæ"]}},
{"name":"æ¬¢é¨","type":1,"url":"http://www.youhuifuligou.com/json/?id=7&url=","ext":{"flag":["qq","è¾è®¯","qiyi","ç±å¥èº","å¥èº","youku","ä¼é·","letv","ä¹è§","xigua","è¥¿ç"]}},
{"name":"hfyrw","type":1,"url":"https://json.hfyrw.com/mao.go?url=","ext":{"flag":["ltnb","renrenmi"]}},
{"name":"aiaine02","type":1,"url":"https://vip.aiaine.com/api/?key=8FN8gNAySnvJiMllxZ&url=","ext":{"flag":["ltnb","renrenmi","xfyun","miaoparty","miaoparty2","miaoparty3","longteng","xueren"]}},
{"name":"äºä¸è§£æ","type":1,"url":"https://json.5lp.net/json.php?url=","ext":{"flag":["ltnb","renrenmi","rx","rongxing"]}},
{"name":"RongXingVR","type":1,"url":"https://vip.rongxingvr.top/api/?key=JJEZkZIhzkA4cUtBfR&url=","ext":{"flag":["renrenmi","rx","rongxing","mgtv","èæ","bilibili","åå©åå©","åå©"]}},
{"name":"jx165","type":1,"url":"https://ltjx.kuaixiao.vip/home/api?type=ys&uid=506916&key=dlmpwBHIKLMPQRVW23&url=","ext":{"flag":["ltnb"]}},
{"name":"jx36","type":1,"url":"https://api.m3u8.tv:5678/home/api?type=ys&uid=9105801&key=huwxFGILMOQSTUZ679&url=","ext":{"flag":["qq","è¾è®¯","qiyi","ç±å¥èº","å¥èº","youku","ä¼é·","mgtv","èæ"]}},
{"name":"J13","type":1,"url":"https://languangyingshiziyuan.1080zy.top/longtengzy.php/?url=","ext":{"flag":["ltnb"]}},
{"name":"xfyunäº","type":1,"url":"https://vip.xfyun.one/home/api?type=ys&uid=2581923&key=ceijpquvBMOSUVXZ23&url=","ext":{"flag":["xfyun"]}},
{"name":"Wuduzy","type":1,"url":"https://aa.xkys.tv/json.php?url=","ext":{"flag":["wuduzy"]}},
{"name":"LTRX","type":1,"url":"https://svip.spchat.top/api/?type=ys&key=bKemW41JnxmQb4l67h&url=","ext":{"flag":["rx"]}},
{"name":"åµæ´¾å¯¹èµæº3","type":1,"url":"https://vip.aiaine.com/api/?key=fOWaGgFU45zlIjvbHI&url=","ext":{"flag":["ltnb","renrenmi"]}},
{"name":"åµæ´¾å¯¹èµæº2","type":1,"url":"https://svip.iremind.me/api/?key=A5Db8HF8c8FSIOR6R1&url=","ext":{"flag":["renrenmi","qq","è¾è®¯","qiyi","ç±å¥èº","å¥èº","youku","ä¼é·","mgtv","èæ","bilibili","åå©åå©","åå©","sohu"]}},
{"name":"leduotv","type":1,"url":"https://api.leduotv.com/wp-api/getvodurl.php?vid=","ext":{"flag":["leduo"]}},
# type0 æå¨è§£æ
{"name":"OJBK","type":0,"url":"https://jmwl.qd234.cn/v/?v=","ext":{"flag":["ltnb","renrenmi","rx","xfyun","muxm3u8","xigua","xueren","qq","è¾è®¯","qiyi","ç±å¥èº","å¥èº","youku","ä¼é·","mgtv","èæ","bilibili","åå©åå©","åå©","pptv","PPTV","sohu","letv"]}},
{"name":"M117","type":0,"url":"http://1.117.152.239:39000/?url="},
{"name":"zui","type":0,"url":"https://jx.zui.cm/?url=","ext":{"flag":["ltnb"]}},
{"name":"parwix1","type":0,"url":"https://jx.parwix.com:4433/player/?url=","ext":{"flag":["qq","è¾è®¯","qiyi","ç±å¥èº","å¥èº","youku","ä¼é·","mgtv","èæ","letv","ä¹è§","pptv","PPTV","sohu","bilibili","åå©åå©","åå©"]}},
{"name":"parwix2","type":0,"url":"https://jx.parwix.com:4433/player/analysis.php?v=","ext":{"flag":["qq","è¾è®¯","qiyi","ç±å¥èº","å¥èº","youku","ä¼é·","mgtv","èæ","letv","ä¹è§","pptv","PPTV","sohu","bilibili","åå©åå©","åå©"]}},
{"name":"xuerenweb","type":0,"url":"https://s.2tu.uk/?url=","ext":{"flag":["xueren"]}},
{"name":"xuerenweb2","type":0,"url":"https://xrm3u8.qd234.cn/?url=","ext":{"flag":["xueren"]}},
{"name":"ç¾å§è«","type":0,"url":"https://jx.daiguaji.com/?url=","ext":{"flag":["zijian"]}},
{"name":"miao","type":0,"url":"https://jx.58g8.com/1/?url=","ext":{"flag":["miaoparty"]}},
{"name":"web1","type":0,"url":"https://www.nxflv.com/?url=","ext":{"flag":["youku","ä¼é·","mgtv","èæ","qq","è¾è®¯","qiyi","ç±å¥èº","qq","å¥èº","sohu","letv"]}},
{"name":"ä¸è½è§£æ","type":0,"url":"https://vip.legendwhb.cn/m3u8.php?url=","ext":{"flag":["ltnb","renrenmi","qq","è¾è®¯","qiyi","ç±å¥èº","å¥èº","youku","ä¼é·","mgtv","èæ","bilibili","åå©åå©","åå©"]}},
{"name":"ltnb04","type":0,"url":"https://vip.bljiex.com/?v=","ext":{"flag":["ltnb"]}},
{"name":"ltnb02","type":0,"url":"https://jx.zui.cm/?url=","ext":{"flag":["ltnb"]}},
{"name":"CL4K01","type":0,"url":"https://ys.ling00.cn/CL4K/?url=","ext":{"flag":["CL4K","qq","è¾è®¯"]}},
{"name":"CL4K02","type":0,"url":"https://app.okmedcos.com/4k/?url=","ext":{"flag":["CL4K","qq","è¾è®¯","pptv","PPTV"]}}
],
"flags":["youku","qq","iqiyi","qiyi","letv","sohu","tudou","pptv","mgtv","wasu","bilibili","renrenmi","ä¼é·","èæ","è¾è®¯","ç±å¥èº","å¥èº","ltnb","rx","CL4K","xfyun","wuduzy"],
"ijk":[
{"group":"è½¯è§£ç ","options":[
{"category":4,"name":"opensles","value":"0"},
{"category":4,"name":"overlay-format","value":"842225234"},
{"category":4,"name":"framedrop","value":"1"},
{"category":4,"name":"soundtouch","value":"1"},
{"category":4,"name":"start-on-prepared","value":"1"},
{"category":1,"name":"http-detect-range-support","value":"0"},
{"category":1,"name":"fflags","value":"fastseek"},
{"category":2,"name":"skip_loop_filter","value":"48"},
{"category":4,"name":"reconnect","value":"1"},
{"category":4,"name":"enable-accurate-seek","value":"0"},
{"category":4,"name":"mediacodec","value":"0"},
{"category":4,"name":"mediacodec-auto-rotate","value":"0"},
{"category":4,"name":"mediacodec-handle-resolution-change","value":"0"},
{"category":4,"name":"mediacodec-hevc","value":"0"},
{"category":1,"name":"dns_cache_timeout","value":"600000000"}
]},
{"group":"ç¡¬è§£ç ","options":[
{"category":4,"name":"opensles","value":"0"},
{"category":4,"name":"overlay-format","value":"842225234"},
{"category":4,"name":"framedrop","value":"1"},
{"category":4,"name":"soundtouch","value":"1"},
{"category":4,"name":"start-on-prepared","value":"1"},
{"category":1,"name":"http-detect-range-support","value":"0"},
{"category":1,"name":"fflags","value":"fastseek"},
{"category":2,"name":"skip_loop_filter","value":"48"},
{"category":4,"name":"reconnect","value":"1"},
{"category":4,"name":"enable-accurate-seek","value":"0"},
{"category":4,"name":"mediacodec","value":"1"},
{"category":4,"name":"mediacodec-auto-rotate","value":"1"},
{"category":4,"name":"mediacodec-handle-resolution-change","value":"1"},
{"category":4,"name":"mediacodec-hevc","value":"1"},
{"category":1,"name":"dns_cache_timeout","value":"600000000"}
]}],
"ads":[
"mimg.0c1q0l.cn",
"www.googletagmanager.com",
"www.google-analytics.com",
"mc.usihnbcq.cn",
"mg.g1mm3d.cn",
"mscs.svaeuzh.cn",
"cnzz.hhttm.top",
"tp.vinuxhome.com",
"cnzz.mmstat.com",
"www.baihuillq.com",
"s23.cnzz.com",
"z3.cnzz.com",
"c.cnzz.com",
"stj.v1vo.top",
"z12.cnzz.com",
"img.mosflower.cn",
"tips.gamevvip.com",
"ehwe.yhdtns.com",
"xdn.cqqc3.com",
"www.jixunkyy.cn",
"sp.chemacid.cn",
"hm.baidu.com",
"s9.cnzz.com",
"z6.cnzz.com",
"um.cavuc.com",
"mav.mavuz.com",
"wofwk.aoidf3.com",
"z5.cnzz.com",
"xc.hubeijieshikj.cn",
"tj.tianwenhu.com",
"xg.gars57.cn",
"k.jinxiuzhilv.com",
"cdn.bootcss.com",
"ppl.xunzhuo123.com",
"xomk.jiangjunmh.top",
"img.xunzhuo123.com",
"z1.cnzz.com",
"s13.cnzz.com",
"xg.huataisangao.cn",
"z7.cnzz.com",
"xg.huataisangao.cn",
"z2.cnzz.com",
"s96.cnzz.com",
"q11.cnzz.com",
"thy.dacedsfa.cn",
"xg.whsbpw.cn",
"s19.cnzz.com",
"z8.cnzz.com",
"s4.cnzz.com",
"f5w.as12df.top",
"ae01.alicdn.com",
"www.92424.cn",
"k.wudejia.com",
"vivovip.mmszxc.top",
"qiu.xixiqiu.com",
"cdnjs.hnfenxun.com",
"cms.qdwght.com"
]
}


