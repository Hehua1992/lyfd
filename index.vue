
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8">
    <meta name="renderer" content="webkit|ie-comp|ie-stand">
    <title>龙源风电</title>
<meta name="others" content="页面生成时间 2021-01-31 08:05:00" />
    <meta http-equiv="X-UA-Compatible" content="IE=Edge,chrome=1">
    <meta name="others" content="">
    <link rel="stylesheet" href="xhtml/css/reset.css">
    <link rel="stylesheet" href="xhtml/css/main.css">
    <link rel="stylesheet" href="xhtml/css/gp.css">
</head>
<body>
<!--head and nav-->
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8">
    <meta name="renderer" content="webkit|ie-comp|ie-stand">
    <title>龙源风电</title>
<meta name="others" content="页面生成时间 2020-09-17 14:27:24" />
    <link rel="stylesheet" href="../xhtml/css/reset.css">
    <link rel="stylesheet" href="../xhtml/css/main.css">
    <!--Jquery and Javascript-->
    </head><body><script src="/lydlww/xhtml/js/jquery-1.11.3.min.js" type="text/javascript"></script>
    
    <script src="/lydlww/xhtml/js/BreakingNews.js" type="text/javascript"></script>
    <script src="/lydlww/xhtml/js/jquery.SuperSlide.2.1.2.js" type="text/javascript"></script>
    <script>
        $(function() {
            // 底部友链切换
            $('.foot_rtit>li').mouseover(function(){
                $(this).addClass('on').siblings('li').removeClass('on');
                $('.foot_rcon>li').eq($(this).index()).addClass('on').siblings('li').removeClass('on');
            })

            //回车热键
            $("#searchId").keydown(function(e) {
                if (e.keyCode == 13) {
                    submitSearch();
                }
            });
				  
             $('.navi li').hover(function() {
                $(this).addClass('hover');
                $(this).find('.navi_content0').slideDown(200);
							  $(this).find('.navi_content2').hide();
            }, function() {
                $(this).removeClass('hover');
                $(this).find('.navi_content0').stop(true, true).slideUp(200);
            });
					 $('.navi_content0 li').hover(function() {
                $(this).addClass('hover');
                $(this).find('.navi_content2').slideDown(200);
            }, function() {
                $(this).removeClass('hover');
                $(this).find('.navi_content2').stop(true, true).slideUp(200);
            });
            
        })
        
            


        String.prototype.trim = function() {
            return this.replace(/(^\s*)|(\s*$)/g, "");
        }
        var url = '/osearch/s?tab=all&siteCode=lydlww';

        function submitSearch() {
            var val = $("#searchId").val();
            var isNot = true;
            var str = "',and,exec,insert,select,delete,update,count,*,%,chr,mid,master,truncate,char,declare,;,or,-,+,\",\\',\\,(,),=,_,@,CR,LF,<,>,/,/..,print,{,}";
            //这里的东西还可以自己添加
            var strs = new Array(); //定义一数组
            strs = str.split(","); //字符分割
            for (i = 0; i < strs.length; i++) {
                if (val.indexOf(strs[i]) >= 0) {
                    isNot = false;
                }
            }
            if (isNot) {
                if (val == 'undefined' || val.trim().length == 0) {
                    window.open(url = '/osearch/?siteCode=lydlww');
                } else {
                    window.open(url + "&qt=" + encodeURIComponent(val));
                }
            } else {
                alert("对不起，你输入的搜索内容包含非法字符!");
            }
        };
        $("#picnews").slide({
            titCell: ".hd ul",
            mainCell: ".bd ul",
            autoPage: true,
            effect: "fold",
            autoPlay: true,
            trigger: "click"
        });
    </script>


<!--head and nav-->
<div class="top">
    <div class="topc mc">
        <div class="logo fl"><a href="/../../lydlww/index.shtml"><img src="/lydlww/xhtml/images/toplogo.png" alt="" height="80"></a></div>
        <div class="topc_r fr"><a href="http://zhaopin.shenhua.cc/" target="_blank">在线招聘</a>  <a id="StranLink" href="javascript:void(0);" class="webname" title="切換到繁體中文版本">繁體版</a>|<a href="/lydlwwEn/" target="_blank">English</a>
            <div class="search fr"><input id="searchId" value="" type="text"><a href="javascript:submitSearch();" class="submit"></a></div>
        </div>
        <script src="/lydlww/xhtml/js/simplifiedTraditionalSwitching.js" type="text/javascript"></script>
        <div class="nav mc  navi">
        <ul class="nav_con fr">
            <li><a href="/../../lydlww/index.shtml" class="item">首页</a></li>
            <li><a href="/../../lydlww/gsjj/list_gsjj.shtml" class="item">关于我们</a>
              <!--通过listloop获取二级子栏目-->
               <ul class="navi_content navi_content0">
                    <li style="position:relative;" class="dashed_line_d8d8d8"><a href="/../../lydlww/gsjj/list_gsjj.shtml">公司简介</a>
                      <ul class="navi_content navi_content2">
 

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/zzjg/list_gsjj.shtml">组织机构</a></li>

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/dsj/list_gsjj.shtml">大事记</a></li>

                        </ul>
                    </li>
                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/dszzc/list_gywm.shtml" class="item">董事长致辞</a></li>
                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/zjlzc/list_gywm.shtml" class="item">总经理致辞</a></li>
                    <li class="dashed_line_d8d8d8" style="position:relative;"><a href="/../../lydlww/dsh/list_gltd.shtml" class="item">管理团队</a>
                        <ul class="navi_content navi_content2">
 

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/dsh/list_gltd.shtml">董事会</a></li>

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/jsh/list_gltd.shtml">监事会</a></li>

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/ggc/list_gltd.shtml">高管层</a></li>

                        </ul>
                    </li>
                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/qywh/list_gywm.shtml" class="item">企业文化</a></li>
                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/ryzz/list_gywm.shtml" class="item">荣誉资质</a></li>
                
                </ul>
            </li>
            <li><a href="/../../lydlww/gsyw/list.shtml" class="item">新闻中心</a>
                <!--通过listloop获取二级子栏目-->
                <ul class="navi_content navi_content0">
 

                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/gsyw/list.shtml">公司头条</a></li>

                </ul>
            </li>
            <li><a href="/../../lydlww/flfd/list_fl.shtml" class="item">主营业务</a>
                <!--通过listloop获取二级子栏目-->
                <ul class="navi_content navi_content0">
                    <li class="dashed_line_d8d8d8" style="position:relative;"><a href="/../../lydlww/flfd/list_fl.shtml" class="item">风力发电</a>
                        <ul class="navi_content navi_content2">
 

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/fdjd/list_fl.shtml">六大风电基地</a></li>

                        </ul>
                    </li> 
 

                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/tynfd/list_3.shtml">太阳能发电</a></li>

                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/kjyqt/list_3.shtml">科技服务</a></li>

                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/hlfd/list_3.shtml">火力发电</a></li>

                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/drfd/list_3.shtml">地热发电</a></li>

                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/cxfd/list_3.shtml">潮汐发电</a></li>

                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/swzfd/list_3.shtml">生物质发电</a></li>

                   
                   <li class="dashed_line_d8d8d8" style="position:relative;"><a href="/../../lydlww/gczb/list_zb.shtml" class="item">招标信息 </a>
                        <ul class="navi_content navi_content2">
 

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/gczb/list_zb.shtml">工程招标</a></li>

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/hwzb/list_zb.shtml">货物招标</a></li>

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/fwzb/list_zb.shtml">服务招标</a></li>

                        </ul>
                    </li> 
                </ul>
            </li>
            <li><a href="/../../lydlww/zlgy/list_qyzl.shtml" class="item">投资者关系</a>
               <!--通过listloop获取二级子栏目-->
                <ul class="navi_content navi_content0">
                   <li class="dashed_line_d8d8d8" style="position:relative;"><a href="/../../lydlww/zlgy/list_qyzl.shtml" class="item">企业管治</a>
                        <ul class="navi_content navi_content2">
 

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/zlgy/list_qyzl.shtml">治理概要</a></li>

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/dshjsh/list_dshjsh.shtml">董事会监事会</a></li>

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/nkzd/list_qyzl.shtml">内控制度</a></li>

                        </ul>
                    </li> 
                    <li class="dashed_line_d8d8d8" style="position:relative;"><a href="/../../lydlww/nbb/list_gsbg.shtml" class="item">公司报告</a>
                        <ul class="navi_content navi_content2">
 

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/nbb/list_gsbg.shtml">年报</a></li>

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/zbb/list_gsbg.shtml">中报</a></li>

                        </ul>
                    </li> 
 

                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/lsgg/list_tzz.shtml">交易所公告</a></li>

                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/tzzbh/list_tzz.shtml">投资者关系活动</a></li>

                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/tzzcx/list_3.shtml">投资者查询</a></li>

                </ul>
            </li>
            <li><a href="/../../lydlww/rlzp/list.shtml" class="item">人力资源</a>
                <!--通过listloop获取二级子栏目-->
                <ul class="navi_content navi_content0">
 

                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/rlzp/list.shtml">人力招聘</a></li>

                    <li class="dashed_line_d8d8d8"><a href="/../../lydlww/jypx/list_3.shtml">教育培训</a></li>

                </ul>
            </li>
            <li><a href="/../../lydlww/lsxd/list_3.shtml" class="item">环境与社会</a>
                <ul class="navi_content navi_content0">
                     <li class="dashed_line_d8d8d8" style="position:relative;"><a href="/../../lydlww/lsxd/list_3.shtml" class="item">绿色行动</a>
                    </li> 
                     <li class="dashed_line_d8d8d8" style="position:relative;"><a href="/../../lydlww/shzr/list_shzr.shtml" class="item">社会责任</a>
                        <ul class="navi_content navi_content2" style="left:-125px;">
 

                            <li class="dashed_line_d8d8d8"><a href="/../../lydlww/shzrbg/list_shzrcon.shtml">社会责任报告</a></li>

                        </ul>
                    </li> 
                </ul>
            </li>
        </ul>
    </div>
    </div>
    
</div>

// 测试信息
// http://172.16.122.38:8000 映射 http://219.142.82.174:8000
// 后台用户名：test/test 数据库：root/test321


<!--Jquery and Javascript-->
<script src="xhtml/js/jquery-1.11.3.min.js" type="text/javascript"></script>
<!-- <script>
    function turnBanner(bool){
        if(bool){
            $('#banner .bd img').each(function (ind,el) {  
                var strSrc = $(el).attr("src");
                var thisSrc = strSrc.split('xhtml/images/')[1];
                strSrc = strSrc.replace(thisSrc,'ft'+thisSrc);
                $(el).attr("src",strSrc);
            });
        }else{
            $('#banner .bd img').each(function (ind,el) {  
                var strSrc = $(el).attr("src");
                var thisSrc = strSrc.split('xhtml/images/')[1];
                var turnStr = thisSrc.substr(2);
                strSrc = strSrc.replace(thisSrc,turnStr);
                $(el).attr("src",strSrc);
            });
        }
        
    }
</script> -->
<script src="/lydlww/xhtml/js/BreakingNews.js" type="text/javascript"></script>
<script src="/lydlww/xhtml/js/jquery.SuperSlide.2.1.2.js" type="text/javascript"></script>
<script>
    $("#picnews").slide({
        titCell: ".hd ul",
        mainCell: ".bd ul",
        autoPage: true,
        effect: "fold",
        autoPlay: true,
        trigger: "click"
    });
</script>


<script src="xhtml/js/jquery-1.11.3.min.js"></script>
<script src="xhtml/js/jquery.SuperSlide.2.1.2.js"></script>
<script type="text/javascript" src="http://hq.sinajs.cn/list=hk00916" charset="gb2312"></script>
<script type="text/javascript">
//图片滚动 调用方法 imgscroll({speed: 30,amount: 1,dir: "up"});
$.fn.imgscroll = function(o){
	var defaults = {
		speed: 40,
		amount: 0,
		width: 1,
		dir: "left"
	};
	o = $.extend(defaults, o);
	
	return this.each(function(){
		var _li = $("li", this);
		_li.parent().parent().css({overflow: "hidden", position: "relative"}); //div
		_li.parent().css({margin: "0", padding: "0", overflow: "hidden", position: "relative", "list-style": "none"}); //ul
		_li.css({position: "relative", overflow: "hidden"}); //li
		if(o.dir == "left") _li.css({float: "left"});
		
		//初始大小
		var _li_size = 0;
		for(var i=0; i<_li.size(); i++)
			_li_size += o.dir == "left" ? _li.eq(i).outerWidth(true) : _li.eq(i).outerHeight(true);
		
		//循环所需要的元素
		if(o.dir == "left") _li.parent().css({width: (_li_size*5)+"px"});
		_li.parent().empty().append(_li.clone()).append(_li.clone()).append(_li.clone());
		_li = $("li", this);

		//滚动
		var _li_scroll = 0;
		function goto(){
			_li_scroll += o.width;
			if(_li_scroll > _li_size)
			{
				_li_scroll = 0;
				_li.parent().css(o.dir == "left" ? { left : -_li_scroll } : { top : -_li_scroll });
				_li_scroll += o.width;
			}
				_li.parent().animate(o.dir == "left" ? { left : -_li_scroll } : { top : -_li_scroll }, o.amount);
		}
		
		//开始
		var move = setInterval(function(){ goto(); }, o.speed);
		_li.parent().hover(function(){
			clearInterval(move);
		},function(){
			clearInterval(move);
			move = setInterval(function(){ goto(); }, o.speed);
		});
	});
};
</script>
<script type="text/javascript">
$(document).ready(function(){

	$(".scrollleft").imgscroll({
		speed: 40,    //图片滚动速度
		amount: 0,    //图片滚动过渡时间
		width: 1,     //图片滚动步数
		dir: "left"   // "left" 或 "up" 向左或向上滚动
	});
	
});
</script> 
