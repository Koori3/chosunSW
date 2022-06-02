# 20213268_강영진_과제
## 리눅스 명령어
### top
- 리눅스 시스템에서 프로세스들의 CPU사용량을 실시간으로 모니터링하거나 관리할 수 있는 유틸리티이다.

#### 요약 정보 필드별 항목
|필드|설명|
|:---:|:---|
|System time|시스템 현재 시간|
|Uptime|업타임, OS가 기동된 시간|
|User|접속중인 유저 세션 수|
|Load Average|CPU Load의 이동 평균 [1분, 5분, 15분]에 대한 평균값 표시|
|Tasks|현재 프로세스들의 상태|
|CPU|CPU의 사용률|
|Memory|메모리 사용량|
<img src="https://i.imgur.com/cr2tP5I.png">

#### 세부 정보 필드별 항목
|필드|설명|
|:---:|:---|
|PID|프로세스 ID(process ID)|
|USER|프로세스를 실행시킨 사용자 ID|
|PR|프로세스의 우선순위(Priority)|
|NI|PR값에 영향을 주는 NICE 값|
|VIRT|가상메모리의 사용량, (SWAP+RES)|
|RES|RAM에서 사용중인 메모리의 크기(Resident Size)|
|SHR|다른 프로세스와의 공유메모리|
|S|프로세스의 현재 상태 (State)
|%CPU|CPU의 사용률|
|%MEM|메모리의 사용률|
|TIME+|프로세스의 런타임|
|COMMAND|실행된 명령어|
<img src="https://i.imgur.com/w5Qio0f.png">
*** 

### ps

### jobs

### kill

## vim에디터에서의 매크로 사용방법




가로줄   
---
가로줄  
***

1) 1
2) 2
3) 3

- 1
- 2
- 3

* 1
* 2
* 3

` 인용문 ` : 인용문입니다

```c
#include<stdio.h>

int main() {
    printf("Hello World!\n");
}
```

*기울임체*  
_기울임체_  
**굵게**  
__굵게__  
***굵은기울임체***  
___굵은기울임체___  

