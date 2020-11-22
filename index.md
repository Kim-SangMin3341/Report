## About our team project
우리 팀이 선정한 주제는 Korean-News-Crawler입니다. 크롤링이란 웹페이지를 그대로 가져와서 거기서 원하는 데이터를 선별해서 추출하는 행위를 말합니다. 특히, 우리 프로젝트는 한국의 naver 포털 사이트에 올라와 있는 각종 정치, 경제, 생활문화, IT과학, 사회, 세계, 스포츠 등등의 기사를 대상으로 개인이 원하는 카테고리와 날짜 및 기간을 선정하면 해당 항목을 csv 파일로 정리해줍니다.

## How to improve?
프로젝트의 최근 이슈들을 살펴보았더니, 큰 문제점이 있었습니다. 맥의 환경을 제외한 윈도우 10의 os에서 프로그램이 정상 작동하지 않는다는 것입니다. 처음에는 vscode에 환경에서 실행시켜봤으나 실패하였고 후에 커맨드 창에서 다시 실행해 보았으나 결과는 별반 다르지 않았습니다. 이러한 치명적인 문제를 해결하는것을 기준 목표로 삼아서 다음의 것들 또한 함께 개선할 계획입니다.
  1. 년/월 -> 년/월/시간 현재 setdate라는 함수의 파라미터로 start_year, end_year, start_month, end_month 총 4개의 변수가 들어가는데 여기에 추가로 start_date, end_date 까지 추가할 계획입니다. 
  2. sportscrawler의 html 형식이 바뀌어서 현재 사용이 불가합니다. 이를 개선하겠습니다.
  3. 현재 output으로 나오는 csv 파일에는 간단한 제목과 기사 헤드라인 정도가 전부입니다. 가능하다면 csv파일을 하나 더 생성해서 이미지 파일또한 crawling 해볼 예정입니다.

### My works & possibility 
  아직까지는 code level 에서 큰 변화는 없었습니다. (가령, 알고리즘을 수정하는 것) 다만 통일 되지 않은 않은 변수나 가시적으로 코드를 보다 팀원들과 한눈에 알아볼 수 있게 주석을 달면서 코드를 파악중에 있습니다. 또한 기본적인 팀소개와 프로젝트를 위한 정적페이지를 작성하였고 현재는 정적페이지를 담당하는 팀원들이 ui를 다듬고 있습니다. 소프트웨어학을 공부한지 2년정도 되어가는 지금, 저는 c언어,자바, 자로구조, 알고리즘, 시스템프로그래밍 등을 공부했습니다. 본 프로젝트의 언어가 파이썬으로 작성된 코드임에 다소 생소하지만, 이미 여러 알고리즘의 로직을 공부한 저이기에 팀원들의 더 좋은 알고리즘을 제공하기 위해 노력하고 있습니다. 아울러 조장으로서 본 프로젝트의 즉어가는 커뮤니티 활동에 적극적으로 issue 제공 및 commit을 하며 프로젝트를 완성할 예정입니다.

Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Kim-SangMin3341/Report/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
