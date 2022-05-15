{
"wallpaper":"https://picsum.photos/1280/720/?blur=10",
//"spider":"https://notabug.org/tomb003/CatVodTVSpider/raw/master/jar/custom_spider.jar",


# spider (择一使用👇)
## 01.🐼缝合接口
"spider":"https://gitee.com/hd2019/OneClickRun/raw/master/xpath/custom_spider.jar",
## 02.🐉明接口
//"spider":"https://gitee.com/hd2019/OneClickRun/raw/master/xpath/xm.jar",
## 03.🐱S接口
//"spider":"https://gitee.com/hd2019/OneClickRun/raw/master/xpath/baikan.jar",




# 直播 (择一使用👇)
## 01.🦋直播
## --> spider 改 baikan.jar 或 custom_spider.jar
"lives":[{"group":"redirect","channels":[{"name":"live","urls":["proxy://do=live&type=txt&ext=aHR0cHM6Ly9jZG4uanNkZWxpdnIubmV0L2doL1l1YW5Ic2luZy9PbmVDbGlja1J1bkBtYXN0ZXIveHBhdGgvbGl2ZS50eHQ="]}]}],


## 02.🦋直播
## --> spider 改 xm.jar
## --> 使用 "02.🐉明接口"时,直播要改成 "02.🦋直播 ", 适配 "🐉设置直播为首页" 这个功能)
//"lives":[{"group":"redirect","channels":[{"name":"redirect","urls":["proxy://do=tvfix&type=list"]}]}],




"sites":[
## 01.🐼缝合接口
## --> spider 改 custom_spider.jar
{"key":"csp_CZSPP","name":"🐼厂长资源(SP)","type":3,"api":"csp_CZSPP","searchable":1,"quickSearch":1,"filterable":0},
{"key":"csp_Auete","name":"🐼宝全测试(SP)","type":3,"api":"csp_Auete","searchable":1,"quickSearch":0,"filterable":1,"ext":""},
{"key":"csp_AliPanSou","name":"🐼喵狸盘搜（仅支持搜索）","type":3,"api":"csp_AliPanSou","searchable":1,"quickSearch":1,"filterable":0},
{"key":"csp_Lgyy","name":"🐼蓝光影院(SP)","type":3,"api":"csp_Lgyy","searchable":1,"quickSearch":1,"filterable":1,"ext":""},
{"key":"csp_Zxzj","name":"🐼在线之家(SP)","type":3,"api":"csp_Zxzj","searchable":1,"quickSearch":1,"filterable":1,"ext":""},
{"key":"csp_Cokemv","name":"🐼宝全测试(SP)","type":3,"api":"csp_Cokemv","searchable":1,"quickSearch":1,"filterable":1,"ext":""},
{"key":"csp_Fantuan","name":"🐼饭团(SP)","type":3,"api":"csp_Fantuan","searchable":1,"quickSearch":1,"filterable":1,"ext":""},
{"key":"csp_Qicui","name":"🐼奇粹(SP)","type":3,"api":"csp_Qicui","searchable":1,"quickSearch":1,"filterable":1,"ext":""},
{"key":"csp_DY1990","name":"🐼90(SP)","type":3,"api":"csp_DY1990","searchable":1,"quickSearch":1,"filterable":0},




## 02.🐉明接口
## --> spider 改 xm.jar, (XPath系列 不可用, APP影视规则 不可用, 资源网采集 可用)
## --> 直播 改 "02.🦋直播"
## 相较于"缝合接口", 多了"七七" & 正常的"小纸条" & "假窗·氛围·白噪声" & "设置直播为首页", 尝鲜用!
//{"key":"csp_CZSPP","name":"🐉厂长资源","type":3,"api":"csp_CZSPP","searchable":1,"quickSearch":1,"filterable":0},
//{"key":"csp_NaNa","name":"🐉七七","type":3,"api":"csp_NaNa","searchable":1,"quickSearch":1,"filterable":0},
//{"key":"csp_Live","name":"🐉设置直播为首页","type":3,"api":"csp_Live","searchable":0,"quickSearch":0,"filterable":0},




## 03.🐱S接口
## --> spider 改 baikan.jar
//{"key":"360_spider","name":"🐱360(官源)","type":3,"api":"csp_YS360","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/360.json"},
//{"key":"ftys_spider","name":"🐱饭团(SP)","type":3,"api":"csp_Ftys","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/fantuan.bmp"},




## XPath系列, APP影视规则, 资源网采集
{"key":"csp_xpath_huya","name":"虎牙(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/huya2.json"},
{"key":"csp_xpath_kuqimv","name":"酷奇MV(XP)","type":3,"api":"csp_XPath","searchable":0,"quickSearch":0,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/kuqimv.json"},
{"key":"csp_xpath_6d","name":"六度TV(XPF)","type":3,"api":"csp_XPathFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/6d.json"},
{"key":"csp_xpath_zxzj2","name":"在线之家(XPF)","type":3,"api":"csp_XPathFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/zxzj2.json"},
{"key":"csp_xpath_libv","name":"Libvio(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/libv.json"},
{"key":"csp_xpath_4kpianku","name":"4k片库网(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/4kpianku.json"},
{"key":"csp_xpath_doujiaow","name":"豆角网(XPF)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/doujiaow.json"},
{"key":"csp_xpath_auete","name":"Auete影视(XPF)","type":3,"api":"csp_XPathFilter","searchable":1,"quickSearch":0,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/auete.json"},
{"key":"csp_xpath_yanetflix","name":"鸭奈飞(XPF)","type":3,"api":"csp_XPathFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/yanet.json"},
{"key":"csp_xpath_ddg","name":"达达龟(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/dadagui.json"},
{"key":"csp_xpath_789kp","name":"789看片(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/789kp.json"},
{"key":"csp_xpath_348z","name":"348电影(XPF)","type":3,"api":"csp_XPathFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/348z.json"},
{"key":"csp_xpath_dandanzan10","name":"蛋蛋赞(电影)(XPF)","type":3,"api":"csp_XPathFilter","searchable":0,"quickSearch":0,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/dandanzan10.json"},
{"key":"csp_xpath_cokemv","name":"Cokemv(XPF)","type":3,"api":"csp_XPathFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/cokemv.json"},
{"key":"csp_xpath_jpys","name":"极品影视(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/jpys.json"},
{"key":"Jumi","name":"剧迷TV(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/Jumi.json"},
{"key":"csp_xpath_lranc","name":"天天影视(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/lranc.json"},
{"key":"csp_xpath_dmntv","name":"弹幕影院(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/dmntv.json"},
{"key":"csp_xpath_dmw","name":"动漫岛(XPF)","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/dmw.json"},


{"key":"csp_xpath_huohuo99","name":"火火影视(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/huohuo99.json"},
{"key":"csp_XPath_bidiys","name":"哔嘀影视(XP)","type":3,"api":"csp_XPathFilter","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/bidiys.json"},
{"key":"csp_xpath_xqmi","name":"小强迷(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/xqmi.json"},
{"key":"csp_xpath_vip1280","name":"VIP电影(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/vip1280.json"},
{"key":"csp_xpath_zzzlike","name":"周末电影(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/zzzlike.json"},
{"key":"csp_xpath_tjyy","name":"奇优影院(XP)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/huigutongying.json"},
{"key":"csp_xpath_yyotv","name":"小太阳(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/yyotv.json"},
{"key":"csp_xpath_aidi","name":"爱迪影视(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/aidi.json"},
{"key":"csp_xpath_lezhutv","name":"乐猪TV(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/lezhutv.json"},
{"key":"csp_xpath_saohuotv","name":"骚火电影(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/saohuotv2.json"},
{"key":"csp_xpath_pianba","name":"片吧影院(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/pianba.json"},
{"key":"csp_xpath_duboku","name":"独播库(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/duboku2.json"},
{"key":"csp_xpath_lkvod","name":"来看点播(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/lkvod.json"},
{"key":"csp_xpath_94sm","name":"94神马(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/94sm.json"},
{"key":"csp_xpath_zj883","name":"追剧网(XP)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":0,"ext":"https://cdn.jsdelivr.net/gh/YuanHsing/OneClickRun@master/xpath/zj883.json"},




# M浏览器中APP影视规则支持(AppYsV2)
#APP影视(大熊)
{"key":"csp_appysv2_流星","name":"流星(M2)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://fkxs2233.com/mogai_api.php/v1.vod"},
{"key":"csp_appysv2_手指","name":"手指(M2)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://szys5678.com/mogai_api.php/v1.vod"},


#
#优质
{"key":"csp_appysv2_钟特影视","name":"钟特影视(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://app.zteys.com/api.php/v1.vod"},
{"key":"csp_appysv2_影阅阁","name":"影阅阁(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://221.236.18.12:665/api.php/v1.vod"},
//{"key":"csp_appysv2_优视影视","name":"优视影视(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://app.ysys.asia/lvdou_api.php/v1.vod"},
{"key":"csp_appysv2_影视大全","name":"影视大全(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://app.okmedcos.com/api.php/v1.vod"},
//{"key":"csp_appysv2_雨果影视","name":"雨果影视(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://123.youguo520.top/lvdou_api.php/v1.vod"},
{"key":"csp_appysv2_暖光影视","name":"暖光影视(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://app.bl210.com/api.php/v1.vod"},
//{"key":"csp_appysv2_奈非迷","name":"奈非迷(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://app.netflixmi.com/api.php/v1.vod"},
{"key":"csp_appysv2_美剧范","name":"美剧范(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://ttzmz.net/api.php/v1.vod"},
{"key":"csp_appys_美剧虫","name":"美剧虫(优)","type":3,"api":"csp_AppYs","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://meijuchong.com/api.php/v1.vod"},
{"key":"csp_appysv2_麻瓜视频","name":"麻瓜视频(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://aliyun.k8aa.com/mogai_api.php/v1.vod"},
{"key":"csp_appysv2_琅琊影视","name":"琅琊影视(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://fgyuu.top/lehailb_api.php/v1.vod"},
{"key":"csp_appysv2_懒猫电影","name":"懒猫电影(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://lanmao.lanmaoymw.cn/api.php/v1.vod"},
{"key":"csp_appysv2_零刻影院","name":"零刻影院(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://ys.ling00.cn/api.php/v1.vod"},
{"key":"csp_appysv2_看看影视","name":"看看影视(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://kk.ccboke.top/ruifenglb_api.php/v1.vod"},
{"key":"csp_appysv2_飓风影院","name":"飓风影院(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://yidayy.top/lehailb_api.php/v1.vod"},
//{"key":"csp_appysv2_虎猫视频","name":"虎猫视频(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://vv.humaoweb.com/mogai_api.php/gctvapi.vod"},
{"key":"csp_appysv2_狐狸动漫","name":"狐狸动漫(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://ak.baicai.buzz/lvdou_api.php/v1.vod"},
{"key":"csp_appysv2_粉象视界","name":"粉象视界(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://42.157.129.15:34444/lvdou_api.php/v1.vod"},
//{"key":"csp_appysv2_飞捷影视","name":"飞捷影视(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://fjkkk.cn/api.php/v1.vod"},
{"key":"csp_appysv2_饭后电影","name":"饭后电影(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://yinliub.cn/lvdou_api.php/v1.vod"},
{"key":"csp_appysv2_段友影视","name":"段友影视(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://shangjihuoke.com/api.php/tv.vod"},
{"key":"csp_appysv2_段友影视2","name":"段友影视2(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://121.204.249.135:4433/ruifenglb_api.php/v1.vod"},
{"key":"csp_appysv2_独播社","name":"独播社(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://35ys.cc/api.php/v1.vod"},
{"key":"csp_appysv2_嗷呜视频","name":"嗷呜视频(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://www.cx99999.cn/lvdou_api.php/v1.vod"},
{"key":"csp_appysv2_爱酷影视","name":"爱酷影视(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://www.zhanlangbu.com/ruifenglb_api.php/v1.vod"},
{"key":"csp_appysv2_DC影视","name":"DC影视(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://chaorenbb.com/api.php/v1.vod"},
{"key":"csp_appysv2_300看世界","name":"300看世界(优)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://300ys.xyz/mogai_api.php/v1.vod"},
#
#普通
{"key":"csp_appysv2_余生影视","name":"余生影视(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://yu.cuicanys.cn/lvdou_api.php/v1.vod"},
{"key":"csp_appysv2_影视猫","name":"影视猫(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://vip.wscyun.com/api.php/v1.vod"},
{"key":"csp_appysv2_月儿影视","name":"月儿影视(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://yue52.xyz/api.php/v1.vod"},
{"key":"csp_appysv2_熊猫视频","name":"熊猫视频(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://anegh.com/lvdou_api.php/v1.vod"},
{"key":"csp_appys_三日影院","name":"三日影院(普)","type":3,"api":"csp_AppYs","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://www.3ri.net/api.php/v1.vod"},
{"key":"csp_appysv2_日诚影视","name":"日诚影视(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://tv.rcz168.com/api.php/v1.vod"},
{"key":"csp_appysv2_群鑫影视","name":"群鑫影视(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://www.qunxinys.com/api.php/v1.vod"},
{"key":"csp_appysv2_蒲公英视频","name":"蒲公英视频(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://www.pgy1.top/ruifenglb_api.php/v1.vod"},
{"key":"csp_appysv2_美剧迷","name":"美剧迷(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://mj.zjtv.cc/ruifenglb_api.php/v1.vod"},
{"key":"csp_appysv2_冷视TV","name":"冷视TV(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://len.tv/api.php/v1.vod"},
{"key":"csp_appysv2_凌晨影视","name":"凌晨影视(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://vip.wscyun.com/api.php/v1.vod"},
{"key":"csp_appysv2_酷秒视界","name":"酷秒视界(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://cms.kumiaotv.cn/api.php/v1.vod"},
{"key":"csp_appysv2_快看影视","name":"快看影视(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://kuaikys.com/mogai_api.php/v1.vod"},
{"key":"csp_appysv2_看吧VIP","name":"看吧VIP(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://app.ppli.xyz/api.php/v1.vod"},
{"key":"csp_appysv2_玖肆资源","name":"玖肆资源(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://android.jiusi.vip/mogai_api.php/v1.vod"},
{"key":"csp_appysv2_极酷影视","name":"极酷影视(普)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://jiku.vip/mogai_api.php/v1.vod"},
#
#神马
{"key":"csp_appysv2_影视阁","name":"影视阁(神马)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://216.98.10.85/api.php/iptv/vod/"},
{"key":"csp_appysv2_小熊猫TV","name":"小熊猫TV(神马)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://tv2.hetaoys.vip/api.php/iptv/vod/"},
{"key":"csp_appysv2_小南TV","name":"小南TV(神马)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://n293.ngys.xyz/mv/api.php/Chengcheng/vod/"},
{"key":"csp_appysv2_天空TV","name":"天空TV(神马)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://tv.tkys.tv/api.php/iptv/vod/"},
{"key":"csp_appysv2_山楂影视","name":"山楂影视(神马)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://dy6.dcd1.cn/api.php/iptv/vod/"},
//{"key":"csp_appysv2_柠檬TV","name":"柠檬TV(神马)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://106.12.113.90:7575/api.php/iptv/vod/"},
{"key":"csp_appysv2_芒迅TV","name":"芒迅TV(神马)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://www.hdyangtv.com/api.php/iptv/vod/"},
{"key":"csp_appysv2_聚多影视","name":"聚多影视(神马)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://jdys.weetai.cn/api.php/iptv/vod/"},
{"key":"csp_appysv2_盒子视界","name":"盒子视界(神马)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://eh.tvzy.cc/api.php/iptv/vod/"},
{"key":"csp_appysv2_爱西西TV","name":"爱西西TV(神马)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://tv2.aixixi.vip/api.php/iptv/vod/"},
{"key":"csp_appysv2_CV影视","name":"CV影视(神马)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://www.cccvvv.top/api.php/iptv/vod/"},
{"key":"csp_appysv2_369TV","name":"369TV(神马)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://8.142.23.147:555/api.php/Chengcheng/vod/"},
{"key":"csp_appysv2_2号币","name":"2号币(神马)","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://phoebe.cf/api.php/iptv/vod/"},
#




# 广大侠 资源网采集
#官方解析
{"key":"天堂资源","name":"天堂资源(官)","type":1,"api":"http://vipmv.cc/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
{"key":"M3U8.TV资源","name":"M3U8.TV资源(官)","type":1,"api":"http://www.zycaiji.net:7788/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
{"key":"麒麟资源","name":"麒麟资源(官)","type":1,"api":"http://www.qilinzyz.com/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
{"key":"江北资源","name":"江北资源(官)","type":1,"api":"https://gfzycj.hnmj.vip/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
{"key":"思古官采","name":"思古官采(官)","type":1,"api":"http://zy.sgyun.me/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
{"key":"星一官采","name":"星一官采(官)","type":1,"api":"https://gcku.suboyun.vip/api.php/provide/vod/","playUrl":"https://www.xing1.vip/player/dp/?url=","searchable":1,"quickSearch":1},
{"key":"wabc(腾讯直采)","name":"wabc(腾讯直采)(官)","type":1,"api":"https://wabc.ml/mao/1.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
//{"key":"片库","name":"片库(官)","type":1,"api":"https://pianku.wang/api.php/provide/vod/","searchable":0,"quickSearch":0},
{"key":"看猫","name":"看猫(官)","type":1,"api":"http://124.222.83.15:88/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
{"key":"忆梦","name":"忆梦(官)","type":1,"api":"http://anltv.cn/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
//{"key":"土狗官采","name":"土狗官采(官)","type":1,"api":"http://vip-02.tgzy.cc/api.php/provide/vod/","searchable":0,"quickSearch":0},
{"key":"极速官采","name":"极速官采(官)","type":1,"api":"http://gc.zhuijuba.vip/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"奥特曼资源","name":"奥特曼资源(官)","type":1,"api":"https://aotemanzy.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"雪人官采","name":"雪人官采(官)","type":1,"api":"https://zl.chinafix.wang/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"木子看剧","name":"木子看剧(官)","type":1,"api":"https://mzkj.maccms.cf/api.php/provide/vod/","searchable":1,"quickSearch":1},
#
#切片资源
{"key":"FOX资源","name":"FOX资源(切)","type":1,"api":"https://api.foxzyapi.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"神速资源","name":"神速资源(切)","type":1,"api":"https://api.sszyapi.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"光速资源","name":"光速资源(切)","type":1,"api":"https://api.guangsuapi.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"新浪资源","name":"新浪资源(切)","type":1,"api":"http://api.xinlangapi.com/xinlangapi.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"快播资源","name":"快播资源(切)","type":1,"api":"http://www.kuaibozy.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"八戒资源","name":"八戒资源(切)","type":1,"api":"http://cj.bajiecaiji.com/inc/apijson_vod.php","searchable":0,"quickSearch":0},
{"key":"百度资源","name":"百度资源(切)","type":1,"api":"https://api.apibdzy.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"无尽资源2","name":"无尽资源2(切)","type":1,"api":"https://wuzy9.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"无尽资源","name":"无尽资源(切)","type":1,"api":"https://wujinzy.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
//{"key":"天空资源","name":"天空资源(切)","type":1,"api":"https://api.tiankongapi.com/api.php/provide/vod/","searchable":0,"quickSearch":0},
{"key":"乐多资源","name":"乐多资源(切)","type":0,"api":"http://cj.leduocaiji.com/inc/api.php","playUrl":"json:https://api.leduotv.com/wp-api/getvodurl.php?vid=","searchable":1,"quickSearch":1},
//{"key":"聚合资源","name":"聚合资源(切)","type":1,"api":"https://ziyuan.juhesys.com/api.php/provide/vod/","searchable":0,"quickSearch":0},
{"key":"南国影源","name":"南国影源(切)","type":1,"api":"http://api.nguonphim.tv/api.php/provide/vod/","searchable":1,"quickSearch":1},
#
#优质资源
{"key":"影世界","name":"影世界(优)","type":1,"api":"https://video.yingworld.vip/api.php/provide/vod/","searchable":1,"quickSearch":1,"categories":["电影","连续剧","综艺","动漫"]},
{"key":"饭后电影","name":"饭后电影(优)","type":1,"api":"http://yinliub.cn/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"考拉TV","name":"考拉TV(优)","type":1,"api":"https://ikaola.tv/api.php/provide/vod/","playUrl":"https://ikaola.tv/vwnet/dplayer/?url=","searchable":1,"quickSearch":1},
{"key":"一点影视","name":"一点影视(优)","type":1,"api":"https://m3u8.movurl.xyz/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"思古影院","name":"思古影院(优)","type":1,"api":"https://www.siguyy.net/api.php/provide/vod/","searchable":1,"quickSearch":1},


#
#三方聚合
{"key":"影图","name":"影图(聚)","type":1,"api":"https://cj.vodimg.top/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"哇可可影视","name":"哇可可影视(聚)","type":1,"api":"https://www.zwcoco.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"共青春","name":"共青春(聚)","type":1,"api":"https://gqcyy.com/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
{"key":"酷猫影视","name":"酷猫影视(聚)","type":1,"api":"https://www.pgcms10.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"胖猫影视","name":"胖猫影视(聚)","type":1,"api":"http://www.pangmaotv.com/api.php/provide/vod/","searchable":1,"quickSearch":1},
{"key":"嘛哩嘛哩","name":"嘛哩嘛哩(聚)","type":1,"api":"https://malimali3.com/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1,"categories":["国产动漫","日韩动漫","欧美动漫","港台动漫"]},
{"key":"海外电影","name":"海外电影(聚)","type":1,"api":"https://www.200121.com/api.php/provide/vod/","playUrl":"parse:parwix1","searchable":1,"quickSearch":1},
#
// 推送功能扩展（需v2.1.0.Beta6及以上版本）
// 需要在配置文件中，加入key为push_agent的站点，数据返回格式和普通爬虫一致
// 支持推送播放网盘链接
// https://github.com/catvod/CatVodTVSpider
{"key":"push_agent","name":"推送","type":3,"api":"csp_PushAgent","searchable":0,"quickSearch":0,"filterable":0}
#
],
"lives":[
{"group":"redirect","channels":[
{"name":"live","urls":["proxy://do=live&type=txt&ext=aHR0cHM6Ly9jZG4uanNkZWxpdnIubmV0L2doL1l1YW5Ic2luZy9PbmVDbGlja1J1bkBtYXN0ZXIveHBhdGgvbGl2ZS50eHQ="]}
]}
],
"parses":[
{"name":"解析聚合","type":3,"url":"Demo"},
{"name":"Json并发","type":2,"url":"Parallel"},
{"name":"Json轮询","type":2,"url":"Sequence"},
# type1 聚合.并发.轮询
{"name":"Pro","type":1,"url":"http://api.vip123kan.vip/?url=","ext":{"flag":["youku","优酷","mgtv","芒果","qq","腾讯","qiyi","爱奇艺","qq","奇艺"]}},
{"name":"bilibili","type":1,"url":"https://vip.23at.cn/home/api?type=ys&uid=4883852&key=adfimsvxzDKNOVX389&url=","ext":{"flag":["bilibili"]}},
{"name":"leduo","type":1,"url":"https://api.ldjx.cc/wp-api/getvodurl.php?token=1001&vid=","ext":{"flag":["leduo"]}},
{"name":"duoduozy2","type":1,"url":"https://a.dxzj88.com/jxjx/dd.php?url=","ext":{"flag":["duoduozy"]}},
{"name":"renrenmi2","type":1,"url":"https://a.dxzj88.com/jxrrm/jiami.php?url=","ext":{"flag":["renrenmi"]}},
{"name":"renrenmi3","type":1,"url":"https://sz.dxzj88.com/jxrjrm/jiaomi.php?url=","ext":{"flag":["renrenmi"]}},
{"name":"Pro2","type":1,"url":"https://vip.rongxingvr.top/api/?type=ys&key=JJEZkZIhzkA4cUtBfR&url=","ext":{"flag":["ltnb","rx","qiyi","爱奇艺","qq","奇艺","sohu","letv","youku","优酷","mgtv","芒果"]}},
{"name":"2","type":1,"url":"https://jx.mczdyw.com/xg.php?url=","ext":{"flag":["mgtv","芒果"]}},
{"name":"3","type":1,"url":"https://www.aiaine.com/api/?key=kVqmG5dAQ5dZTcECw8&url=","ext":{"flag":["youku","优酷","mgtv","芒果","qq","腾讯","qiyi","爱奇艺","qq","奇艺"]}},
{"name":"4","type":1,"url":"https://svip.rongxingvr.top/api/?key=niBgMGXVdCQhsmeEBK&url=","ext":{"flag":["youku","优酷","mgtv","芒果","qq","腾讯","qiyi","爱奇艺","qq","奇艺"]}},
{"name":"8","type":1,"url":"https://app.iminna.com/jx/?url=","ext":{"flag":["youku","优酷","mgtv","芒果","qq","腾讯","qiyi","爱奇艺","qq","奇艺"]}},
{"name":"初心影视1","type":1,"url":"http://jhpc.manduhu.com/j1217.php?url=","ext":{"flag":["youku","优酷","qq","腾讯","mgtv","芒果"]}},
{"name":"飓风影院2","type":1,"url":"https://vvip.funsline.cn/api/?key=3xWfEoDf4V9p9Y20CR&url=","ext":{"flag":["ziqie","youku","优酷","qiyi","爱奇艺","奇艺","mgtv","芒果","qq","腾讯"]}},
{"name":"我爱电影网","type":1,"url":"https://jhpc.manduhu.com/j1217.php?url=","ext":{"flag":["qiyi","爱奇艺","奇艺","mgtv","芒果","youku","优酷","pptv","PPTV"]}},
{"name":"初心影视9","type":1,"url":"https://api.m3u8.tv:5678/home/api?type=ys&uid=1931000&key=gktuvyzABEORSYZ135&url=","ext":{"flag":["youku","优酷","qq","腾讯","mgtv","芒果"]}},
{"name":"江湖解析","type":1,"url":"http://103.40.240.46/jh/?url=","ext":{"flag":["renrenmi","qq","腾讯","youku","优酷","mgtv","芒果","xigua","西瓜"]}},
{"name":"王牌","type":1,"url":"https://za.kuanjv.com/?url=","ext":{"flag":["qq","腾讯","qiyi","爱奇艺","奇艺","youku","优酷","mgtv","芒果","搜狐","sohu","letv","乐视","bilibili","哔哩哔哩","哔哩","xigua","西瓜"]}},
{"name":"我爱电影网","type":1,"url":"https://jhpc.manduhu.com/j1217.php?url=","ext":{"flag":["qq","腾讯","qiyi","爱奇艺","奇艺","youku","优酷","mgtv","芒果","乐视","letv","PPTV","pptv","bilibili","哔哩哔哩","哔哩"]}},
{"name":"盘古解析","type":1,"url":"https://json.pangujiexi.com:12345/json.php?url=","ext":{"flag":["qq","腾讯","qiyi","爱奇艺","奇艺","youku","优酷","mgtv","芒果"]}},
{"name":"欢雨","type":1,"url":"http://www.youhuifuligou.com/json/?id=7&url=","ext":{"flag":["qq","腾讯","qiyi","爱奇艺","奇艺","youku","优酷","letv","乐视","xigua","西瓜"]}},
{"name":"hfyrw","type":1,"url":"https://json.hfyrw.com/mao.go?url=","ext":{"flag":["ltnb","renrenmi"]}},
{"name":"aiaine02","type":1,"url":"https://vip.aiaine.com/api/?key=8FN8gNAySnvJiMllxZ&url=","ext":{"flag":["ltnb","renrenmi","xfyun","miaoparty","miaoparty2","miaoparty3","longteng","xueren"]}},
{"name":"五一解析","type":1,"url":"https://json.5lp.net/json.php?url=","ext":{"flag":["ltnb","renrenmi","rx","rongxing"]}},
{"name":"RongXingVR","type":1,"url":"https://vip.rongxingvr.top/api/?key=JJEZkZIhzkA4cUtBfR&url=","ext":{"flag":["renrenmi","rx","rongxing","mgtv","芒果","bilibili","哔哩哔哩","哔哩"]}},
{"name":"jx165","type":1,"url":"https://ltjx.kuaixiao.vip/home/api?type=ys&uid=506916&key=dlmpwBHIKLMPQRVW23&url=","ext":{"flag":["ltnb"]}},
{"name":"jx36","type":1,"url":"https://api.m3u8.tv:5678/home/api?type=ys&uid=9105801&key=huwxFGILMOQSTUZ679&url=","ext":{"flag":["qq","腾讯","qiyi","爱奇艺","奇艺","youku","优酷","mgtv","芒果"]}},
{"name":"J13","type":1,"url":"https://languangyingshiziyuan.1080zy.top/longtengzy.php/?url=","ext":{"flag":["ltnb"]}},
{"name":"xfyun云","type":1,"url":"https://vip.xfyun.one/home/api?type=ys&uid=2581923&key=ceijpquvBMOSUVXZ23&url=","ext":{"flag":["xfyun"]}},
{"name":"Wuduzy","type":1,"url":"https://aa.xkys.tv/json.php?url=","ext":{"flag":["wuduzy"]}},
{"name":"LTRX","type":1,"url":"https://svip.spchat.top/api/?type=ys&key=bKemW41JnxmQb4l67h&url=","ext":{"flag":["rx"]}},
{"name":"喵派对资源3","type":1,"url":"https://vip.aiaine.com/api/?key=fOWaGgFU45zlIjvbHI&url=","ext":{"flag":["ltnb","renrenmi"]}},
{"name":"喵派对资源2","type":1,"url":"https://svip.iremind.me/api/?key=A5Db8HF8c8FSIOR6R1&url=","ext":{"flag":["renrenmi","qq","腾讯","qiyi","爱奇艺","奇艺","youku","优酷","mgtv","芒果","bilibili","哔哩哔哩","哔哩","sohu"]}},
{"name":"leduotv","type":1,"url":"https://api.leduotv.com/wp-api/getvodurl.php?vid=","ext":{"flag":["leduo"]}},
# type0 手动解析
{"name":"OJBK","type":0,"url":"https://jmwl.qd234.cn/v/?v=","ext":{"flag":["ltnb","renrenmi","rx","xfyun","muxm3u8","xigua","xueren","qq","腾讯","qiyi","爱奇艺","奇艺","youku","优酷","mgtv","芒果","bilibili","哔哩哔哩","哔哩","pptv","PPTV","sohu","letv"]}},
{"name":"M117","type":0,"url":"http://1.117.152.239:39000/?url="},
{"name":"zui","type":0,"url":"https://jx.zui.cm/?url=","ext":{"flag":["ltnb"]}},
{"name":"parwix1","type":0,"url":"https://jx.parwix.com:4433/player/?url=","ext":{"flag":["qq","腾讯","qiyi","爱奇艺","奇艺","youku","优酷","mgtv","芒果","letv","乐视","pptv","PPTV","sohu","bilibili","哔哩哔哩","哔哩"]}},
{"name":"parwix2","type":0,"url":"https://jx.parwix.com:4433/player/analysis.php?v=","ext":{"flag":["qq","腾讯","qiyi","爱奇艺","奇艺","youku","优酷","mgtv","芒果","letv","乐视","pptv","PPTV","sohu","bilibili","哔哩哔哩","哔哩"]}},
{"name":"xuerenweb","type":0,"url":"https://s.2tu.uk/?url=","ext":{"flag":["xueren"]}},
{"name":"xuerenweb2","type":0,"url":"https://xrm3u8.qd234.cn/?url=","ext":{"flag":["xueren"]}},
{"name":"美剧虫","type":0,"url":"https://jx.daiguaji.com/?url=","ext":{"flag":["zijian"]}},
{"name":"miao","type":0,"url":"https://jx.58g8.com/1/?url=","ext":{"flag":["miaoparty"]}},
{"name":"web1","type":0,"url":"https://www.nxflv.com/?url=","ext":{"flag":["youku","优酷","mgtv","芒果","qq","腾讯","qiyi","爱奇艺","qq","奇艺","sohu","letv"]}},
{"name":"万能解析","type":0,"url":"https://vip.legendwhb.cn/m3u8.php?url=","ext":{"flag":["ltnb","renrenmi","qq","腾讯","qiyi","爱奇艺","奇艺","youku","优酷","mgtv","芒果","bilibili","哔哩哔哩","哔哩"]}},
{"name":"ltnb04","type":0,"url":"https://vip.bljiex.com/?v=","ext":{"flag":["ltnb"]}},
{"name":"ltnb02","type":0,"url":"https://jx.zui.cm/?url=","ext":{"flag":["ltnb"]}},
{"name":"CL4K01","type":0,"url":"https://ys.ling00.cn/CL4K/?url=","ext":{"flag":["CL4K","qq","腾讯"]}},
{"name":"CL4K02","type":0,"url":"https://app.okmedcos.com/4k/?url=","ext":{"flag":["CL4K","qq","腾讯","pptv","PPTV"]}}
],
"flags":["youku","qq","iqiyi","qiyi","letv","sohu","tudou","pptv","mgtv","wasu","bilibili","renrenmi","优酷","芒果","腾讯","爱奇艺","奇艺","ltnb","rx","CL4K","xfyun","wuduzy"],
"ijk":[
{"group":"软解码","options":[
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
{"group":"硬解码","options":[
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


