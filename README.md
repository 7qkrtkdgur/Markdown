#  마크다운이란?

마크다운(Markdown)은 텍스트 기반의 마크업언어이다. README 파일이나 온라인 문서, 혹은 일반 텍스트 편집기로 문서 양식을 편집할 때 쓰인다. 마크다운을 이용해 작성된 문서는 쉽게 HTML 등 다른 문서형태로 변환이 가능하다. 2004년에 존그루버에 의해 만들어졌으며, 사람들이 읽기 쉽고 쓰기 쉬운 플레인 텍스트 포맷을 사용하여 쓸 수 있으면서 구조적으로 유효한 XHTML(또는 HTML)로 선택적 변환이 가능하게 하는 것이 목표이다.




# 문법

## 제목 (HEADERS)

### #을 하나 쓰면 HTML의 h1 태그를, #을 두개 쓰면 h2 태그를 의미한다. 1~6개까지 쓸 수 있고, #이 늘어날때마다 글씨 크기가 작아진다.

```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
```
 
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
인용 (BLOCK QUOTE)
인용된 글을 표시하고자 할 때, > 기호를 사용합니다.

> This is a blockqute.


This is a blockqute.

# 목록 (LISTS)

순서가 없는 목록(Bullet Lists)은 *, +, - 기호를 사용하여, 계층이 필요한 경우에는 들여쓰기를 하면 된다.

```
* one
  * two
    * three
```

```
+ one
  + two
    + three
```

```
- one
- two
- three
```


## 순서있는 목록(Numbered Lists)은 숫자를 사용합니다. 특징으로는 숫자의 순서와 상관없이 무조건 차례대로 표시된다.

```
1. one
2. two
3. tree
```

1.one <br>
2.two <br>
3.tree <br>

```
1. one
1. two
1. tree
```

1.one <br>
1.two <br>
1.tree <br>

```
2. one
1. two
3. tree
```

1.one <br>
2.two <br>
3.tree <br>

## 수평선 (HORIZONTAL RULES)
--, ***, ___ 기호 3개이상은 수평선으로 삽입된다.

```
***
```
***


## 강조(EMPPHASIS)

```
*single asterisks*
```

single asterisks

```
_single underscores_
```

single underscores

```
**double asterisks**
```

double asterisks

```
__double underscores__
```

double underscores

```
++underline++
```

++underline++

```
~~cancelline~~
```

cancelline

## 링크 (LINKS)

```
[구글](http://www.google.com)
```

구글

## 이미지 (IMAGES)
이미지 경로는 http:// 로 URL 경로 전체를 쓰셔도 되고, 같은 서버 경로에서 써도 됩니다.

```
![사진이름](사진경로)
![Alt text](/resources/images/logo/64x64.png)
![Alt text](/resources/images/logo/64x64.png "Optional title")
```



## 코드 (CODE)
```
 `코드 내용`
```

코드 내용

## 코드 블록 (CODE BLOCKS)
코드 블록 표시는 `로 시작해서 3개으로 닫는다.

```
```java
 Sptring str = "this is Code Blocks";   
` ``
```

 Spring str = "this is Code Blocks";
 
## Markdown에 이미 사용되는 기호 표시(BACKSLASH ESCAPES)

Markdown 문법에 사용되는 기호를 있는 그대로 표시하고 싶을 경우가 있다. 예를 들어 # 마크를 그냥 쓰면 실제로는 H1 제목으로 출력되기 때문에 이 기호를 그대로 출력하고 싶다면 기호 앞에 \(=back slash) 문자를 써주면 된다. \(=back slash)를 그대로 사용하고 싶은 경우에는 \\를 2개를 쓰면 됩니다.

Markdown에서 사용하는 기호는 아래와 같습니다.

\   backslash
`   backtick
*   asterisk
_   underscore
{}  curly braces
[]  square brackets
()  parentheses
#   hash mark
+   plus sign
-   minus sign (hyphen)
.   dot
!   exclamation mark
