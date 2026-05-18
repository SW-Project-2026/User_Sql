# User SQL Generator

가상 회원 데이터 및 배송지 SQL을 생성하는 도구입니다.

## 사용 방법

### 1. 도로명주소 파일 다운로드
[도로명주소 다운로드](https://business.juso.go.kr/jst/jstAddressDownload) 접속 후 최신 파일(2026년 4월) 다운로드

### 2. 파일 준비
다운로드한 `rnaddrkor_seoul.txt` 파일명을 `address_raw.txt`로 변경 후 `convert_address.ipynb` 파일과 같은 경로로 이동

### 3. 라이브러리 설치
```bash
pip install faker bcrypt
```

### 4. 실행
`generate_users.ipynb` → `convert_address.ipynb` 순서로 실행
