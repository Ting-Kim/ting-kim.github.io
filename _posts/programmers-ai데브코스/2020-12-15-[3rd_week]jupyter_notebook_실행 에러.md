---
layout: post
title: "[3rd_week]jupyter notebook 실행 에러"
categories: (프로그래머스)Ai데브코스1기
tags: [ai, git, jupyter notebook]
use_math: true
comments: true
---

노트북에서는 cmd에 'jupyter notebook' 명령어로 jupyter notebook이 실행되었는데, 데스크탑에서는 계속 

```bash
'jupyter'은(는) 내부 또는 외부 명령, 실행할 수 있는 프로그램, 또는
배치 파일이 아닙니다.
```

라는 오류가 떴다. 찾아보니 환경변수 문제인 것 같은데, 대부불 conda를 이용해서 설치한 경우라 pip install 했을 경우 환경변수 설정 방법을 찾기 힘들었다.

그런데 해당 명령어 대신 **'python -m notebook'** 을 사용하라는 글을 봤다. 이게 해답인 것 같다.

(왜 인지는 아직 모르겠다..)