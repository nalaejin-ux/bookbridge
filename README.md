# 📚 나은·지윤 독서 기록

경북 독서친구 연계 가족 독서 관리 웹앱

## 기능

- **이번 주 추천 3권** — 경북 독서친구 권장도서 기반, 읽은 책 자동 제외
- **이모지 별점 + 한 줄 독서평** 기록
- **경북독서친구 독후활동 연동** — 4단계 절차 안내 (로그인 → 인증 → 독후활동 → 하트)
- **안동시어린이도서관 소장 확인** — 탭 한 번으로 도서관 검색 연결
- **아이별 테마** — 나은(핑크·노랑) / 지윤(파랑·초록)
- **PWA 지원** — 아이폰/아이패드 홈 화면에 추가 가능

## 배포 방법 (GitHub Pages)

### 1. 저장소 생성
```
GitHub → New Repository → 이름 설정 → Create
```

### 2. 파일 올리기
```bash
git init
git add index.html manifest.json README.md
git commit -m "첫 배포"
git remote add origin https://github.com/[계정]/[저장소명].git
git push -u origin main
```

### 3. GitHub Pages 활성화
```
저장소 → Settings → Pages → Source: main branch → Save
```

### 4. 접속
```
https://[계정].github.io/[저장소명]/
```

## 아이폰/아이패드 홈 화면 추가

1. Safari 브라우저로 앱 URL 접속
2. 하단 공유 버튼 탭
3. **"홈 화면에 추가"** 선택
4. 앱처럼 전체화면으로 실행됨

## 경북독서친구 독후활동 절차

1. [경북독서친구 로그인](https://bookfriend.info.go.kr/login/login.do)
2. 독후활동 → 초등학교 → 권장도서/인증 → 읽은 책 인증받기
   - 6문제 중 4개 이상 맞으면 인증 완료
   - 미통과 시 2시간 후 재응시
3. 독후활동 > 권장도서 독후활동 하기
4. 심사위원 하트 평가 → 연 4회 우수학생 시상 🏆

## 안동시어린이시립도서관

[도서관 홈페이지](https://lib.andong.go.kr/child/) — 추천 책 카드에서 바로 소장 확인 가능

---

> 데이터: 경북교육청 독서친구 초등 1학년(120권) / 4학년(120권) 권장도서
