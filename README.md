# Html
	
`<!DOCTYPE html>` 定義使用html5

`<meta charset = "UTF-8">` html用中文編碼

`<link rel="stylesheet" href="">` 插入css檔案  
* * *
## css撰寫方式
選擇器{  
&nbsp; 屬性：設定值;  
}  

選擇器:擬態選擇器行為{  
&nbsp; 屬性：設定值;  
} 
 
###後代選擇器  
選擇器1 選擇器2{  
&nbsp; 屬性：設定值;  
}

###css rest 
 [meyerweb](https://meyerweb.com/eric/tools/css/reset/ "")
 
###css 3盒模型
*{   
	&nbsp;  box-sizing:border-box;  
	&nbsp; -moz-box-sizing:border-box;  
	&nbsp; -webkit-box-sizing:border-box;  
}  

預設值box-sizing:content-box;  
-moz-box- 舊firfox前綴詞  
-webkit-box- 舊chorm前綴詞

不會因為border padding影響實際大小

##css相對定位/絕對定位
###絕對定位
.class{  
   &nbsp;position:absolute;  
   &nbsp;top:0;  
   right:0;  
}  
position:fixed  不因滾輪滑動，固定在網頁上

### jpg沒有透明效果(一定會有底色)  
### png可透明

