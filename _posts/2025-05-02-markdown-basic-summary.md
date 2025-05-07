---
layout: post
title: "Markdown 문법기초 필기자료"
date: 2025-05-02 15:40 +0900
categories: [ ”Markdown”, ”DSH2025” ]
tags: [ ”마크다운기초”, ”수업필기”, "인문데이터과학개론" ]
---

### 1. Italics and Bold 
* Italics: _text_ (텍스트 앞뒤로 _를 써서 표기)
* Bold: **text** (텍스트 앞뒤로 **를 써서 표기)
* Italics & Bold 동시표기: **_text_** / _**text**_  (**, _ 표기순서 무관)




### 2. Headers 
* 총 6가지 headers 존재 (header 1 ~ 6 점차 사이즈 감소)
* #header one ~ ######header six
* text 앞에 #로 표현, #개수에 따라 헤더종류 상이
* header 안에서도 Italics and Bold 적용가능




### 3. Links 
#### 3.1 Inline Link 
* [text] (링크)로 표기 시, 링크는 보이지않으며, 텍스트를 누르면 해당 링크로 이동함
* ex. [Visit GitHub!](www.github.com)
* 링크가 걸려있는 text도 볼드체 적용가능
* header에서도 링크 적용가능


#### 3.2 Reference Link  
* 문서 내의 다른 위치에 정의된 링크를 참조하는 방식
* 문서 중간) [링크 텍스트][참조 이름]
* 문서 하단) [참조 이름]: 실제 URL
* 같은 링크를 여러 곳에서 쓸 때, URL을 한 곳만 수정하면 전체가 바뀌므로 편리함


> Here's [a link to something else][another place].
> 
> Here's [yet another link][another-link].
> 
> And now back to [the first link][another place].
>
> [another place]: 링크
> [another-link]: 링크



### 4. Images 
링크와 같이 2가지 방식. 느낌표(!)를 찍어주는 것이 구현방식에서의 차이점.
#### 4.1 Inline Image Link
* ![text] (링크)


#### 4.2 Reference Image Link 
* ![링크 텍스트][참조 이름]
* ![참조 이름]: 실제 URL



### 5. Blockquotes 
* ">" 텍스트 (텍스트 앞에 > 작성)
* 여러 문단을 하나의 인용문으로 묶고 싶을 경우, 공백 라인까지 포함하여 모두 앞에 > 작성
* 인용문 안에 이탤릭체, 볼드체, 이미지, 링크 등 다른 마크다운 요소 포함 가능



### 6. Lists 
#### 6.1 Unordered Lists
* _* text_ 로 열거하면 불렛포인트로 나열됨


#### 6.2 Ordered Lists 
* '*' 대신 숫자 적기 (numbering)
* 리스트에서도 (unordered / ordered 모두) 이탤릭체,  볼드체, 링크 모두 가능
* 리스트 간의 위계를 표기하고 싶을 경우, 하위에 들어가는 항목 * 앞에 스페이스바 삽입
* 리스트 하위에 들어갈 본문은 엔터 친 뒤, 스페이스바를 두 칸 작성해야 함


### 7. Paragraphs
* hard break: 마크업 언어에서 줄바꿈이 적용되려면 엔터를 두 번 쳐서 공백의 라인을 만들어야 함
* soft break: hard break보다 더 좁은 간격의 줄바꿈(ex. 시)이 필요할 경우, 줄 맨 끝에 스페이스바 2번 입력

