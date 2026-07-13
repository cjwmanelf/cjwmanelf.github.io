# 종우의 기록 (cjwmanelf.github.io)

미국주식 투자와 아이펠(AIFFEL) AI 에이전트 KDT 과정 학습 내용을 기록하는 블로그입니다.

- 블로그 주소: <https://cjwmanelf.github.io>
- 테마: [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy)
- 배포: GitHub Actions (push하면 자동으로 빌드·배포됨)

## 글 쓰는 법

1. `_posts/` 폴더에 `YYYY-MM-DD-제목.md` 형식으로 파일 생성 (파일명은 영문 권장)
2. 파일 맨 위에 아래 형식(front matter)을 작성

```yaml
---
title: 글 제목
date: 2026-07-13 20:00:00 +0900
categories: [미국주식, 투자공부]   # 또는 [AIFFEL, 학습기록]
tags: [태그1, 태그2]
---
```

3. 그 아래에 마크다운으로 본문 작성
4. 커밋 후 push하면 1~2분 안에 블로그에 반영됨

```bash
git add .
git commit -m "post: 글 제목"
git push
```

### 자주 쓰는 문법 (Chirpy 전용)

```markdown
> 팁 박스
{: .prompt-tip }

> 경고 박스
{: .prompt-warning }
```

이미지는 `assets/img/` 폴더에 넣고 `![설명](/assets/img/파일명.png)`으로 삽입.

## 구글 애드센스 (추후 진행)

애드센스 승인을 받으려면 보통 **글 20~30개 이상, 운영 2~3개월**이 필요합니다.
승인 신청 시점에 할 일:

1. [Google AdSense](https://adsense.google.com) 가입 → 사이트 `https://cjwmanelf.github.io` 등록
2. 발급받은 애드센스 코드(`ca-pub-XXXX`)를 사이트 `<head>`에 삽입
3. 저장소 루트에 `ads.txt` 파일 추가 (애드센스에서 제공하는 내용)
4. 승인 후 광고 단위 코드를 원하는 위치에 배치

## 로컬 미리보기 (선택)

로컬에 Ruby가 없어도 push만 하면 배포되지만, 미리 보고 싶으면:

```bash
bundle install
bundle exec jekyll serve
# http://127.0.0.1:4000 접속
```
