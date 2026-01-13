# Order-Zero 와이어프레임

픽업 주문 서비스 화면 설계 문서

## 📁 폴더 구조

```
docs/
├── index.html          # 전체 화면 목록 페이지
├── c01-a.html          # C-01-A 모바일 와이어프레임
└── README.md           # 이 문서
```

## 🚀 GitHub Pages 설정 방법

### 1단계: 파일 복사 및 푸시

```bash
# 1. 프로젝트 루트로 이동
cd /path/to/order-zero

# 2. docs 폴더를 프로젝트에 복사 (이미 압축 해제한 상태)
# docs/ 폴더가 프로젝트 루트에 있어야 합니다

# 3. Git에 추가 및 커밋
git add docs/
git commit -m "Add wireframes for Phase 1"
git push origin main
```

### 2단계: GitHub Pages 활성화

1. GitHub 저장소 접속: https://github.com/reolino/order-zero
2. **Settings** 탭 클릭
3. 왼쪽 메뉴에서 **Pages** 클릭
4. Source 섹션에서:
   - **Deploy from a branch** 선택
   - Branch: **main** 선택
   - Folder: **/docs** 선택
   - **Save** 버튼 클릭

### 3단계: 접속 확인 (1-2분 후)

- **메인 페이지**: https://reolino.github.io/order-zero/
- **C-01-A**: https://reolino.github.io/order-zero/c01-a.html

## 📝 새 화면 추가 방법

1. `docs/` 폴더에 새 HTML 파일 추가 (예: `c02.html`)
2. `docs/index.html` 업데이트:
   ```html
   <!-- 새 화면 카드 추가 -->
   <a href="c02.html" class="screen-card">
       <div class="screen-header">
           <div>
               <div class="screen-title">메뉴 상세 + 옵션 선택</div>
               <div class="screen-id">C-02</div>
           </div>
           <div class="screen-badges">
               <span class="badge badge-mobile">Mobile</span>
               <span class="badge badge-complete">완료</span>
           </div>
       </div>
       <p class="screen-desc">
           메뉴 상세 정보 및 옵션 선택 화면
       </p>
   </a>
   ```
3. Git 커밋 & 푸시:
   ```bash
   git add docs/
   git commit -m "Add C-02 wireframe"
   git push
   ```

## 🎨 노션에 링크 추가

### 방법 1: Embed (임베드)
```
노션에서:
/embed 입력
→ https://reolino.github.io/order-zero/c01-a.html 붙여넣기
→ 노션에서 바로 미리보기 가능
```

### 방법 2: Bookmark (북마크)
```
노션에서:
URL 붙여넣기
→ 자동으로 북마크 카드 생성
→ 클릭하면 새 탭으로 열림
```

## 📊 현재 진행 상황

- [x] C-01-A: 매장 상세 (모바일, 검색 유입) ✅
- [ ] C-01-A: 매장 상세 (웹, 검색 유입) 🔄
- [ ] C-01-B: 매장 상세 (SNS 유입) 📝
- [ ] C-02: 메뉴 상세 + 옵션 선택 📝
- [ ] C-04: 전체 메뉴 목록 📝
- [ ] C-07: 주문서 작성 📝
- [ ] C-12: 주문 조회 📝

## 🔗 링크

- **GitHub 저장소**: https://github.com/reolino/order-zero
- **와이어프레임 사이트**: https://reolino.github.io/order-zero/
- **Notion 문서**: [링크 추가 예정]

## 📧 Contact

- Email: reolino@gmail.com
- GitHub: @reolino
