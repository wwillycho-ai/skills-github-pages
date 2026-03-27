## 단계 4: 블로그 게시물 작성하기

홈페이지가 멋지게 완성되었네요! :cowboy_hat_face:

### 📖 이론: Jekyll 블로그 게시물과 frontmatter

Jekyll은 특별한 이름의 파일과 frontmatter를 사용하여 블로그 게시물을 만듭니다. 파일은 `_posts/YYYY-MM-DD-title.md` 형식으로 이름을 지어야 하며, **front matter**에 `title`과 `date`를 포함해야 합니다.

**Front matter**는 파일 **상단**에 위치하는 yaml 섹션으로, 다음과 같이 생겼습니다:

```yaml
---
title: "내 블로그에 오신 것을 환영합니다"
date: 2026-03-15
---
```

> [!NOTE]
> [Jekyll frontmatter 문서](https://jekyllrb.com/docs/front-matter/)에서 더 자세히 알아보세요.

### ⌨️ 활동: 블로그 게시물 작성하기

1. `main` branch로 이동합니다.
1. `Add file` 드롭다운 메뉴를 클릭한 다음 `Create new file`을 클릭합니다.
1. `_posts/YYYY-MM-DD-title.md` 형식에 따라 파일 이름을 지정합니다.
1. `YYYY-MM-DD`를 오늘 날짜로 바꾸고, 원하시면 첫 번째 블로그 게시물의 `title`을 변경합니다.
   > 제목을 편집하는 경우, 단어 사이에 하이픈(-)이 있는지 확인하세요.
   > 블로그 게시물 날짜가 올바른 날짜 규칙을 따르지 않으면 오류가 발생하고 사이트가 빌드되지 않습니다. 자세한 내용은 "[페이지 빌드 실패: 잘못된 게시물 날짜](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/troubleshooting-jekyll-build-errors-for-github-pages-sites)"를 참조하세요.
1. 블로그 게시물 상단에 다음 내용을 입력합니다:

   ```yaml
   ---
   title: "제목을 입력하세요"
   date: YYYY-MM-DD
   ---
   ```

   1. `제목을 입력하세요`를 블로그 게시물 제목으로 바꿉니다.
   1. `YYYY-MM-DD`를 오늘 날짜로 바꿉니다.
1. 블로그 게시물의 간단한 초안을 작성합니다. 나중에 언제든지 편집할 수 있습니다.
1. 변경 사항을 `main` branch에 커밋합니다.
1. 변경 사항을 커밋하면 Mona가 이 실습의 다음 단계를 준비합니다!

<details>
<summary>문제가 있나요? 🤷</summary><br/>

- 파일 이름과 날짜 형식을 다시 확인하세요.
- frontmatter가 파일 맨 위에 있고 올바른 형식인지 확인하세요.

</details>
