

## How to remove `^M`

1. launch vi
2. type as below

`:g/^M/s///g`

> Note : to type ^M 'ctrl + v , m `

## 특수문자 제거하기( http://egloos.zum.com/head93/v/554926 )

1. DOS 파일을 Unix에서 읽을 경우 발생하는 ^M를 제거하려면..

2. vi에서 `:g/^M/s///g` 또는 `:%s/^M//g`를 실행한다.
> 참고:  ^M은 Ctrl+V,M으로 입력.


## Tip.terminal 
터미널에서 파인더 실행하기
To open your current directory in Finder from Terminal, type open .
open Downloads
open / Library

## Vi 101
 
### 커맨드 모드 

탈출`:q` 

저장  `:w` 

강제 종료  `:q!` 

강제 저장 후 종료 `:wq!`


### 이동하기 

맨우측으로 이동 (현재 줄) `$`

첫문자로 이동하기  `^`

첫행으로 `gg`

마지막행으로 `G`

아래위: jk

좌우: hl  ( jk의 좌우에 붙은 키라고 기억함 )

### 편집명령어들
문자삭제 `x` 

수정내용 취소 `u`

수정내용 취소했다가 다시 redo 하기  `ctrl+R` 
 
line number를 표시 `:set number`

credits
```
how to use: vi editor
http://www.leafcats.com/115
http://kthan.tistory.com/entry/리눅스Linux-빔vim-에디터-명령어-단축키-및-활용-팁

Regarding /bin/sh^M: bad interpreter
http://blog.whitelife.co.kr/284
http://tod2.tistory.com/28

```
 
pod sample 
```rb
use_frameworks!

target 'ViaCircleDebug' do
	pod 'ChameleonFramework', '2.1.0'
	pod 'SnapKit', '3.1.2'
end

```
