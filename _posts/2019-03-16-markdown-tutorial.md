---
title: "자주 사용하는 Markdown 정리"
date: 2019-03-16
categories: Markdown jekyll
---
# Markdown Tutorial!
Markdown에서 자주 사용하는 문법에 대해서 정리한 내용

# Headers
글의 타이틀에 사용되는 Headers, # 하고 띄어쓰기(Space) 한칸 추가하고 내용 입력
```
# H1 // 제일 큰 header
## H2 // 두번째로 큰 header
.
.
.
###### H6 // 여섯번째로 큰 header
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

# Lists
```
리스트를 만들고자 하면
1. 리스트1
2. 리스트2
    1. 서브리스트 2-1
    2. 서브리스트 2-2
3. 리스트3
    - 서브리스트 3-1
    - 서브리스트 3-2

이런 식으로 만들 수 있다. 서브리스트는 Space 4개!
```
1. 리스트1
2. 리스트2
    1. 서브리스트 2-1
    2. 서브리스트 2-2
3. 리스트3
    - 서브리스트 3-1
    - 서브리스트 3-2

# Emphasis
```
강조하고 싶을 때는 *asterisks* 혹은 _underscore_를 사용
Italics는 *asterisks* 혹은 _underscore_ 사용하여 깜싼다.
Strong Emphasis는 **double asterisks** 혹은 __double asterisks__ 사용하여 감싼다.
Italics and Strong Emphasis는 **두 개를 섞어서 _사용한다_**.
Strikethrough는 ~~two tildes~~를 사용한다.
```
강조하고 싶을 때는 *asterisks* 혹은 _underscore_를 사용

Italics는 *asterisks* 혹은 _underscore_ 사용하여 깜싼다.

Strong Emphasis는 **double asterisks** 혹은 __double underscores__ 사용하여 감싼다.

Italics and Strong Emphasis는 **두 개를 섞어서 _사용한다_**.

Strikethrough는 ~~two tildes~~를 사용한다.

# Code and Syntax Highlighting
```
뭔가 코드 박스로 텍스트를 강조하거나 Inline 코드 작성의 경우 `back-ticks around`를 사용한다.
코드 블럭을 만들려면 ```로 감싸고 그 사이에 코드를 작성한다.
```
뭔가 코드 박스로 텍스트를 강조하거나 Inline 코드 작성의 경우 `back-ticks around`를 사용한다.

```python
def description():
    print("해당 코드는 파이썬 관련 코드입니다. 이는 ```로 감싸져 있고 언어를 명시할 때는 언어명을 적어준다.")
```

# Tables
냐중에...
# Links
나중에...
# Images
나중에...
