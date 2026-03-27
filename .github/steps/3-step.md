## 단계 3: 사이트 구성하기

홈페이지 업데이트 잘하셨습니다! :sparkles:

이제 **구성**을 추가하여 사이트를 깔끔하게 꾸며봅시다!

### 📖 이론: Jekyll과 \_config.yml

Jekyll은 `_config.yml`이라는 파일을 사용하여 사이트 설정, 테마, 그리고 사이트 제목과 GitHub 핸들 같은 재사용 가능한 콘텐츠를 저장합니다. [Jekyll 구성 문서](https://jekyllrb.com/docs/configuration/)에서 더 자세히 알아보세요.

이 활동에서는 "minima"라는 블로그 전용 테마를 사용합니다.

### ⌨️ 활동: 사이트 구성하기

1. `main` branch에서 `_config.yml` 파일을 찾습니다.
1. 오른쪽 상단에서 파일 편집기를 엽니다.
1. `_config.yml` 파일에 아래와 같이 `theme:`을 **minima**로 설정하여 추가합니다:

   ```yml
   theme: minima
   ```

1. (선택 사항) `title:`, `author:`, `description:` 등의 구성 변수를 수정하여 사이트를 더 커스터마이징할 수 있습니다.

   <details>
   <summary>예시</summary><br/>

   ```yml
   theme: minima
   title: {{ login }}의 개인 블로그
   description: 제 일상에서 멋진 것들을 공유하는 곳입니다
   author: {{ login }}
   ```

   </details>

1. (선택 사항) 블로그 포스트의 날짜/시간 처리를 위한 추가 설정도 가능합니다:

   - **`timezone`**: Jekyll이 날짜를 처리할 때 사용할 시간대를 지정합니다. 한국 시간 기준으로 빌드하려면 `Asia/Seoul`을 설정하세요.
   - **`future`**: 기본적으로 Jekyll은 미래 날짜의 포스트를 빌드하지 않습니다. `true`로 설정하면 미래 날짜의 포스트도 사이트에 표시됩니다.

   <details>
   <summary>예시</summary><br/>

   ```yml
   theme: minima
   timezone: Asia/Seoul
   future: true
   ```

   </details>

1. 변경 사항을 `main` branch에 커밋합니다.
1. 변경 사항을 커밋하면 Mona가 이 실습의 다음 단계를 준비합니다!


<details>
<summary>문제가 있나요? 🤷</summary><br/>

- `main` branch에서 `_config.yml` 파일을 편집하고 있는지 확인하세요.
- YAML 형식을 다시 확인하세요. 들여쓰기와 콜론이 중요합니다!

</details>
