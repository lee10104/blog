---
layout: post
title: "다른 페이지 만들기"
tags: jekyll
---
드디어 빌어먹을 과제러쉬 사이에 여유가 좀 생겼다. 정전이 되었으니 난 아무것도 할 수 없다! 고 핑계를 댈 수 있다. jekyll documentation에서 아무거나 눌렀는데 다른 페이지 만들기가 나왔다. 심심해서 대충 아무거나 끄적여보기로 하고 directory를 만들고 거기에 index.html을 만들었더니 간단하게 다른 페이지가 생겼다. 흠... 뭔가를 꾸미는 데에 익숙하지 않은 관계로 그냥 내용밖에 없지만 대충 [이런 곳](http://emellen.com/Do_You_Know_Kang_Dongwon/)이다. 나중에 css 공부를 하게 되면 이 페이지를 어떻게 꾸밀지 생각해 봐야겠다.<br>
테마를 적용하겠다고 삽질을 하고 있다. 나의 디자인 스탯이 굉장히 낮은 관계로 최대한 깔끔한걸 쓰기로 했다. jekyll dark clean theme이란걸 골라서 받아와서 post를 갖다 넣었다. 그랬더니 메인 페이지는 잘 뜨는데 post를 누르면 404 Not Found가 뜬다... 왜죠..? 음.. clean을 하고 다시 build 해도 안 된다. 뭔가 좀 더 봐야겠다. 으으...<br>
음 아무래도 config.yml의 url이나 baseurl에서 뭔가 꼬이는 모양인데..? 일단 주소 상으론 문제가 없는 것 같기도 하다만 git clone한 것을 그대로 가져와서 url과 baseurl을 바꾸었더니 post가 404가 떴다(..). 으엉 대체 뭐가 문제야.. \_site 들어가서 post가 어떻게 build되었는지 봤는데 딱히 뭐가 문제인지도 모르겠다. 으아앙 짜증나 다른 테마 쓸까... 아 대체 왜 안 되냐고오오오ㅇ<br>
그리고 baseurl에 /blog 넣어놓으면 emellen.com/blog에 index.html이 뜰 줄 알았는데 emellen.com에 css 다 깨져서 나오고 emellen.com/blog에는 404 not found가 뜨던데. 이건 또 왜 그런지 모르겠다. 빌드한거 바로 띄우게 해놔서 그런가? 그냥 모르겠다. 생각하기를 그만둔다! 다음에 또 보면 알겠지 뭐.
