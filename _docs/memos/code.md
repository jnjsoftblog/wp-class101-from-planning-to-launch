# 011_02_04_4. 워드프레스의 기본 개념들을 둘러봅시다 1

## [wp-admin](http://wp-class101-from-planning-to-launch.local/wp-admin/)

### Pages / Add New Page(페이지 / 새 페이지 추가)

#### title
소개

#### content

안녕하세요, **7년차 일러스트레이터 &그래픽 디자이너 푸르릉**입니다.

공공기관 콜라보부터 동화책 작업까지 다양한 프로젝트에 참여했습니다. 제 그림을 좋아해주시는 분들은 제 그림에서만 느낄 수 있는 따뜻함, 몽글함, 포근함이 있다고 해요.

저는 경기도 교육청 초등학생 어휘 카드, 북한산국립공원 굿즈, 법제처 영상툰 등 공공기관 작업에 참여했으며, EBS, TBS 등의 방송에 삽입될 일러스트 제작에도 참여했습니다. 뿐만 아니라 다양한 회사 및 소규모 브랜드와 함께 일러스트 작업을 진행하고 있어요. 결혼기념일, 프로포즈 등 소중한 기념일을 더 뜻깊게 만들어줄 개인 일러스트 작업도 하고 있어요.

저는 제 그림을 통해 따뜻한 감정을 전달하고자 합니다. 그림은 혼자만의 만족이 아니기에 고객 분들이 원하시는 색감, 그림체, 느낌을 최대한 반영해서 작업하고 있어요. 또한 책 표지, 제품 상세페이지, SNS 콘텐츠, 브로슈어, 입간판 등 다양한 디자인 작업도 함께하고 있습니다.

그림 요청이 처음이셔도 부담없이 문의주세요! 제가 어떤 그림이 좋을지, 어떤 방식으로 표현하면 좋을지부터 같이 도와드릴게요 🙂

#### 'Publish(공개)' 클릭

### Post 삭제
- 목록 중 'Hello World!' 제목 hover / 'Trash' 클릭

### Posts / Add New Post(글 / 새 글 추가)

#### title
웹사이트 일시 중지 안내

#### content
안녕하세요. 일러스트레이터 푸르릉입니다.

제가 호스팅하고 있는 업체의 정비 작업으로 인해서 설 연휴 동안 사이트가 일시 중지됩니다. 다음 시간 동안 사이트에 정상적으로 접속할 수 없게 되니 참고해 주세요.

**일시 : 2024.02.08(목)[18:00] ~ 2024.02.12(월) [09:00]**

※ 업체 사정에 따라 웹사이트 운영 재개 일시가 조금 바뀔 수 있습니다.

#### 'Publish(공개)' 클릭

### Settings / Permalinks(설정 / 고유주소)

- Common Settings
  - Permalink structure
    - 'Numeric' 클릭
    - Custom Structure: /a/%post_id%
  - 'Save Changes' 클릭

### Permalink 변경 확인

- Posts
  - 목록 중 '웹사이트 일시 중지 안내' 제목 hover / 'View' 클릭
- chrome(browser) url 확인
  - "http://wp-class101-from-planning-to-launch.local/a/11"

### Page 주소 변경
- Pages
  - 목록 중 '소개' 제목 hover / Edit' 클릭
  - Link '/소개'(우측 Page 탭 메뉴) 클릭
  - '/소개' -> '/about' 변경
  - 'Save' 클릭
- chrome(browser) 확인
  - "http://wp-class101-from-planning-to-launch.local/about"


### Category(카테고리) 추가
- Posts / Categories / Add New Category
  - Name: 공지사항
  - Slug: notice
  - 'Add New Category' 클릭

  - Name: 그림일기
  - Slug: drawing-diary
  - 'Add New Category' 클릭

### Category(카테고리) 변경
- Posts / All Posts
  - 목록 중 '소개' 제목 hover / 'Edit' 클릭
  - 'Categories'(우측 Post 탭 메뉴 하단) 클릭
    - 'Uncategorized' 체크 해제
    - '공지사항' 체크
  - 'Save' 클릭


# 012_02_05_5. 워드프레스의 기본 개념들을 둘러봅시다 2

## [wp-admin](http://wp-class101-from-planning-to-launch.local/wp-admin/)

### Posts / Add New Post(글 / 새 글 추가)

#### title
눈 오는 밤 포근한 방

#### content
눈 오는 밤 포근한 방에서 수필집을 읽는 모습을 그려 봤습니다.
옆 방석에는 뽀삐가 잠들어 쌔근댔고, 아직 오지 않은 크리스마스를 기다리는 트리가 있었습니다.
절로 따스한 마음에 매일이 오늘만 같으면 좋겠다는 생각을 했습니다.

#### 이미지 추가
- '+' 클릭
  - 'image(이미지)' / upload(업로드)
  - 'sample_1 크리스마스.jpg'

#### category 설정
- '그림일기'

#### 공개 저장
- 'Publish' 클릭

### 이미지 업로드

- Media / Add New Media File / Select Files

### Posts / Add New Post(글 / 새 글 추가)

#### title
북극곰

#### content
엄마 북극곰, 아기 북극곰과 함께 웅크려 잠드는 꿈을 꿨습니다.
북극곰이 춥다고 집에 들여보내 달라고 했어요.
아이가 추워 보여서 얼른 문을 열었지요.
깨어보니 우스웠지만 그림으로 남겼습니다.
아마 얼음이 녹아 고통받고 있는 북극곰 이야기를 본 것이 기억에 남았나 봅니다.

#### 이미지 추가
- '+' 클릭
  - 'image(이미지)' / 'media library(미디어 라이브러리)'
  - 검색 'sample_4'

#### category 설정
- '그림일기'

#### 공개 저장
- 'Publish' 클릭


### 이미지 정보 변경

- Media / Library
  - '_4' 검색
  - 'sample_4.jpg' 클릭
  - Title: '북극곰'
  - 'X' 클릭

- Media / Library
  - '북극곰' 검색
  - 'sample_4.jpg' 검색됨