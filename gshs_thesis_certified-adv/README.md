﻿# 경기과학고 졸업논문 양식 - advanced ver.

## 글꼴 : 바탕(한글), Times New Roman(영문)
xelatex을 사용하여 글꼴을 바꾸었습니다. 
`% !TeX program = xelatex`

## sub files 이용
고쳐진 부분만 컴파일되기 때문에 조판 속도가 빨라집니다.

## images 폴더 사용
편리해진 이미지 관리
`\graphicspath{{images/}}`
(이미 preamble.tex 에 포함되어 있습니다.)

## bibtex 이용
thebibliography 모드 대신 이것을 사용하면 인용순 정렬, 스타일링 등이 자동으로 됩니다.
`\usepackage[numbers,sort&compress]{natbib}`
`\setlength{\bibsep}{0em}`
`\bibliographystyle{mynewapa}`
APA style에 최대한 가깝게 구현하였습니다. (mynewapa.bst)