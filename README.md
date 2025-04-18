# 아이템 관리 기능 구현하기

## 문제 1: 필터 기능 추가

### 문제 1 요구사항

- 아이템 페이지 우측 상단의 '추가' 버튼 옆에 토글 버튼을 추가합니다. (버튼 UI 자유)
- 토글 버튼은 "음수 아이템 숨기기" 기능을 수행합니다.
  - ON 상태: 가격이 0 이상인 아이템만 표시
  - OFF 상태: 모든 아이템 표시 (기본값)

## 문제 2: 삭제 확인 모달 구현

### 문제 2 요구사항

1. 아이템 클릭 시 수정 모달이 열립니다.
2. 수정 모달의 삭제 버튼 클릭 시:
   - 확인 모달이 추가로 열립니다.
   - 확인 모달에는 "정말 삭제하시겠습니까?"와 같은 경고 메시지가 표시됩니다.
   - 확인 버튼을 클릭해야만 최종 삭제가 이루어집니다.

## 문제 3: 음수 가격 아이템 강조 표시

### 문제 3 요구사항

- 아이템 목록에서 가격이 음수(<0)인 아이템의 이름을 빨간색으로 표시합니다.
- 적용 대상: DataTable의 name 컬럼
