`Git-flow`는 Git이 새롭게 활성화되기 시작하는 10년전 쯤에 Vincent Driessen이라는 사람의 블로그 글에 의해 널리 퍼지기 시작했고 현재는 Git으로 개발할 때 거의 표준과 같이 사용되는 방법론입니다.

말하자면 Git-flow는 기능이 아니고 `서로간의 약속인 방법론`이라는 점입니다. Vincent Driessen도 언급했듯이 Git-flow가 완벽한 방법론은 아니고 각자 개발 환경에 따라 수정하고 변형해서 사용하라고 언급했습니다.

Git-flow는 총 5가지의 브랜치를 사용해서 운영을 합니다.

+ master : 기준이 되는 브랜치로 제품을 배포하는 브랜치 입니다.
+ develop : 개발 브랜치로 개발자들이 이 브랜치를 기준으로 각자 작업한 기능들을 합(Merge)칩니다.
+ feature : 단위 기능을 개발하는 브랜치로 기능 개발이 완료되면 develop 브랜치에 합칩니다.
+ release : 배포를 위해 master 브랜치로 보내기 전에 먼저 QA(품질검사)를 하기위한 브랜치 입니다.
+ hotfix : master 브랜치로 배포를 했는데 버그가 생겼을 떄 긴급 수정하는 브랜치 입니다.


## 출처
 ux공작소 [https://ux.stories.pe.kr/183](https://ux.stories.pe.kr/183) 