Markdown 사용법
--------------

제목
--------------
# 제목 1
## 제목 2
제목2
----
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

단락 Pragraphs
-------------

안녕하세요.  
저는 ooo입니다.  
만나서 반갑습니다.  
  
  나도 만나서 반갑습니다.  
      Hi

기울임(Italic)
-------------

안녕하세요. *저는 OOO 입니다*.  
안녕하세요. _저는 OOO 입니다_.  

볼드(Bold)
---------

안녕하세요. **저는 OOO 입니다**.  
안녕하세요. __저는 OOO 입니다__.  


기울임+볼드
---------

안녕하세요. ***저는 OOO 입니다***.  
안녕하세요. ___저는 OOO 입니다___.  
안녕하세요. __*저는 OOO 입니다*__.  
안녕하세요. **_저는 OOO 입니다_**.

인용문
-----
> 안녕하세요.  
>   
>> 저는 OOO 입니다.  
>>> hello wolrd

> ### 제목3
> 안녕하세요. 저는 **OOO** 입니다.

목록
---
- 목록1
- 목록2
- 목록3
  + 목록3-1
  + 목록3-2
    * 목록3-2-1
      - 목록3-2-1-1
- 목록 4

1. 목록1
2. 목록2
3. 목록3
  - 목록3-1
  - 목록3-2
4. 목록4

1) 목록1
2) 목록2
3) 목록3

- hello
- markdown  
  world
  korea
- korea
  > South Korea  
  > North Korea

코드블록
------
Ansible AWX에서 ```Login```을 하세요.

```python
print("hello world")
```

```shell
ls -l
```

수평줄
----

***
---
___


링크
---

http://www.google.com   
[Google](http://www.google.com)  
[Google](http://www.google.com "구글")  
<http://www.google.com>  
<c1t1d0s7@gmail.com>

이미지
-----

![tux](./tux.png "리눅스 마스코드" width="10" height="10")

탈출문자
------
hello **world** korea  
hello \*\*world\*\* korea

- hello  
\- hello

-------
확장 문법
-------

테이블
-----

|A|B|
|-|-|
|X|Y|
|S|T|

| syntax | description | summary descrition |
| :- | :-: | -: |
| header | title | abc |
| paragraph | text | xyz |

각주
---

위 내용은 [^1]다음을 참조하세요.
아래 내용은 [^kubespray]다음을 참조하세요.

[^1]: http://www.google.com
[^kubespray]: 쿠베스프레이는 프로덕션 레디~~

testtest

정의
---
kubespray  
: abc  

ansible  
: xyz  

취소선
-----
안녕하세요. ~~저는 OOO 입니다.~~

작업 목록
-------
- [X] 테스트
- [X] 개발
- [ ] 릴리즈

링크 비활성화
----------
http://www.google.com  
`http://www.google.com`

