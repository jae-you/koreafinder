# koreafinder
Finding 'Korea' in International Forms - No More Scrolling!
# Korea Finder - 크롬 익스텐션

국가 선택 드롭다운에서 한국을 쉽게 찾아주는 크롬 익스텐션입니다.

## 기능 소개

* 웹페이지의 국가 선택 드롭다운을 자동으로 감지합니다
* 다양한 한국 표기법을 인식합니다 ("Korea", "South Korea", "Republic of Korea", "대한민국", "한국" 등)
* 한국 옵션을 시각적으로 강조해서 쉽게 찾을 수 있게 합니다
* 선택적으로 한국 옵션을 자동으로 선택할 수 있습니다
* 페이지 로드 후에 드롭다운이 추가되는 동적 페이지도 지원합니다

![스크린샷](assets/screenshot.png)

## 설치 방법

### 크롬 웹 스토어에서 설치 (준비 중)

크롬 웹 스토어에서 "Korea Finder"를 검색하거나 [여기를 클릭](웹스토어_링크)하여 설치하세요.

### 개발자 모드로 설치

1. 이 저장소를 클론하거나 ZIP 파일로 다운로드합니다
2. 압축을 풀고 `/src` 폴더의 내용을 확인합니다
3. Chrome 브라우저에서 `chrome://extensions/` 주소로 이동합니다
4. 오른쪽 상단의 "개발자 모드"를 켭니다
5. "압축해제된 확장 프로그램을 로드합니다" 버튼을 클릭합니다
6. 이 저장소의 `/src` 폴더를 선택합니다

## 사용 방법

1. 설치 후 국가 선택 드롭다운이 있는 웹페이지에 접속하면 자동으로 한국 옵션을 찾고 강조표시합니다
2. 익스텐션 아이콘을 클릭하여 설정을 변경할 수 있습니다:
   - 자동으로 한국 선택하기: 한국 옵션을 찾으면 자동으로 선택합니다
   - 드롭다운에서 한국 강조표시: 한국 옵션을 시각적으로 강조합니다
3. "지금 한국 찾기" 버튼을 눌러 현재 페이지에서 다시 한국 옵션을 찾을 수 있습니다

## 개발 정보

이 익스텐션은 Manifest V3를 사용하여 개발되었습니다.

### 개발 환경 설정

1. 이 저장소를 클론합니다
   ```
   git clone https://github.com/your-username/korea-finder.git
   cd korea-finder
   ```

2. 소스 코드를 수정합니다 (`src` 폴더 내 파일들)

3. 크롬 브라우저에서 `chrome://extensions/`로 이동하여 개발자 모드로 테스트합니다

## 기여하기

1. 이 저장소를 포크합니다
2. 새 브랜치를 만듭니다 (`git checkout -b feature/amazing-feature`)
3. 변경사항을 커밋합니다 (`git commit -m 'Add some amazing feature'`)
4. 브랜치에 푸시합니다 (`git push origin feature/amazing-feature`)
5. Pull Request를 제출합니다

## 라이센스

이 프로젝트는 MIT 라이센스 하에 배포됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

## 연락처

프로젝트 링크: [https://github.com/jae-you/korea-finder](https://github.com/jae-you/korea-finder)
