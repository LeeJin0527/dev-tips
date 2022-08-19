# 발생원인: node의 npm 폴더와 npm cahe폴더 데이터와 패키지 설치 데이터의 충돌

## for window : 

Option 1
1. C:\Users(your username)\AppData\Roaming
2. Delete the npm folder and if there is one npm cache folder.
3. Run npm clean cache —force ( — force is now required to clean cache)


Option 2
1. C:\Users(your username)\AppData\Roaming
2. Delete the npm folder and if there is one mom cache folder.
3. Run npm clean cache —force ( — force is now required to clean cache)
4. Make sure everything to do with Nodejs is deleted and uninstalled.
5. Reinstall Nodejs.


## for mac : 
1. npm root -g 
2. remove ~/node_modules/ 
3. brew install npm 

install npm  시간 꽤 오래걸리니 참고 기다려야함 ^^ 

참고 링크 https://github.com/nodejs/help/issues/2874
