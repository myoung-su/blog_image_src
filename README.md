# blog_image_src

블로그 발행용 이미지 호스팅 저장소.
Blogger API에는 이미지 업로드 기능이 없어서, 본문 `<img src>`가 가리킬 공개 URL이 필요하다.

## 구조
```
<slug>/images/*.png   본문 삽입 이미지
<slug>/thumbnail.png  썸네일
```

## 사용
```
BLOG_IMAGE_BASE_URL = https://raw.githubusercontent.com/myoung-su/blog_image_src/main/<slug>
```
