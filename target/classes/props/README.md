service.type=local

 
#########################
##                     ##
##     DB Settings     ##  
##                     ##
#########################

# DB SETTING Oracle
db.type=oracle
jdbc.driverClassName=oracle.jdbc.driver.OracleDriver
jdbc.url=ENC(dSbcF89QDjatPeRzNSbV1eY8D9idtw3dptMtSDdoTsDQTyI0kj0cDdf7tXidrMH6QREaJpI2FXc=)
jdbc.username=ENC(MmeIwHcumkJK4+zRfscC3+E4uh3E2WFI)
jdbc.password=ENC(KlfQMm2dVXikuaC2LuRitNHPmOL77gLA)
 
# DB SETTING MSSQL
#db.type=mssql
#jdbc.driverClassName=com.microsoft.sqlserver.jdbc.SQLServerDriver
#jdbc.url=ENC(8SxZLR3Kzwl/vNjZEwxgJG5ny3GWRXrewvtSRWddwmpTQRoqTFwCl231195vm4HW7HCVDkgOHLs=)
#jdbc.username=ENC(EzK2arPZX89H7f2+e9/iTA==)
#jdbc.password=ENC(aln07wa6Am+sSrbt9ASxBQ==)
 
# DB SETTING Mysql
#db.type=mysql
#jdbc.driverClassName=com.mysql.jdbc.Driver
#jdbc.url=ENC(20Ht9YJ4S+JaANjAXD10QNZ1fQ5i5SRcxFYf0uP8Ehz7LgY5cB/e8U1o4P5PUK54HRtwh4DxCM82G/uRPg6+IqjHF6CKuNta)
#jdbc.username=ENC(wCvLNRxjq1dq43sJODA+Tg==)
#jdbc.password=ENC(I/N1svmelyh14Q54dEr3VA==)


#########################
##                     ##
##   Common Settings   ##  
##                     ##
#########################


# COMMON SETTING
common.hosturl=kscms.ks.ac.kr
common.subhosturl=kscms.ks.ac.kr
common.OperationMode=dev
common.acessecurity=D:/_workplace/UNI_KS/KS2018/src/main/webapp/WEB-INF/config/security/encrypt.key
common.envFile=D:/_workplace/UNI_KS/KS2018/src/main/resources/prop/config.properties

# SITE CODE IMPOSSIBLE CODE LIST
site.impossibleCode = admin,adm,default,share,member,mypage,js,script,site,skin,data,css,convert,template,editor,system,config,cms,search,research,template,cfg,sso,robots

# DEFAULT SITE PATH
site.defalutHome=homepage
site.defaultLayout=_Layout/layout
site.defaultHeader=_Layout/program/inc
site.defaultContetsFile=D:/_workplace/UNI_KS/KS2018/src/main/webapp/WEB-INF/views/_Layout/program/contents/Etc

# BASE PATH
dir.baseDir=D:/_workplace/UNI_KS/KS2018/src/main/webapp
#UPLOAD PATH
dir.baseUploadDir = D:/Data/UploadRoot/
dir.printUploadDir =/attach/
# PATH SETTING
dir.baseWebRoot=/
dir.uploadImage=IMAGE/
dir.uploadContentsPdf=CONTENTS/PDF/
dir.uploadEditor=EDITOR/
dir.uploadFile=FILE/
dir.uploadPdf=PDF/
dir.uploadMovie=MOVIE/
dir.uploadJson=JSON/
dir.templetFolder=D:/_workplace/UNI_KS/KS2018/src/main/webapp/WEB-INF/views/_Templet
dir.widgetFolder=D:/_workplace/UNI_KS/KS2018/src/main/webapp/WEB-INF/views/_Templet/Mwidget
dir.resourceDir=D:/_workplace/UNI_KS/KS2018/src/main/webapp/resources
dir.templetCssDir=D:/_workplace/UNI_KS/KS2018/src/main/webapp/resources/_Templet/
dir.homepageDir=D:/_workplace/UNI_KS/KS2018/src/main/webapp/WEB-INF/views/homepage

page.path =/WEB-INF/views/

# HOMEPAGE MENU TYPE (DB:N, JSON:Y)
json.useYn =Y
 
# Developer SETTING
DevelopMode.isDevelopMode=N
DevelopMode.defaulthost=kscms.ks.ac.kr
DevelopMode.host=ks.ac.kr

 
# MOBILE CERTIFIED
cert.siteCode=G5075
cert.sitePassword=UM0TNW4SRJ9S
cert.requestNumber=REQ0000000001
 
# I-PIN CERTIFIED
cert.ipinCode=Nksac2
cert.ipinSvrNo=N0001N006948


#SNS
sns.fbUrl=https://graph.facebook.com/v3.0/KyungsungUni?fields=id,name,posts{attachments,message,link,created_time,id,updated_time}&access_token=
sns.instaUrl=https://api.instagram.com/v1/users/self/media/recent/?access_token=
sns.naverBlogUrl=https://rss.blog.naver.com/\uB124\uC774\uBC84 \uBE14\uB85C\uADF8 
sns.YotubeUrl=https://www.googleapis.com/youtube/v3/channels?part=contentDetails
sns.YotubeUrl2=https://www.googleapis.com/youtube/v3/playlistItems?part=snippet
sns.YotubeLinkUrl=https://www.youtube.com/watch?v=
sns.execute = Y
sns_schecron=0 0 0/3 * * ?

#DAUM MAP
daum.http=http://dmaps.daum.net/map_js_init/roughmapLoader.js
daum.https=https://ssl.daumcdn.net/dmaps/map_js_init/roughmapLoader.js

#SSO
sso.aesKey=dhkdlwmsptmzharoqkf123#!@#dkdldb

#Board
board.NewsUrl1=https://cms1.ks.ac.kr/JsonBoard.do?mgr_seq=895&category=01&pageSize=5
board.NewsUrl2=https://cms1.ks.ac.kr/JsonBoard.do?mgr_seq=895&category=03&pageSize=5
board.NewsUrl3=https://cms1.ks.ac.kr/JsonBoard.do?mgr_seq=798&pageSize=5
board.NewsUrl4=https://cms1.ks.ac.kr/JsonBoard.do?mgr_seq=565&pageSize=10




