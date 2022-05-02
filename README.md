# WADE OSS 커밋/버전 규칙

<br>
<br>

### 커밋 메시지 규칙
커밋 메시지 구조 `type(타입) : title(제목)`
<br>
<br>
**타입**<br>
`Feat : 새로운 기능의 추가`<br>
`Fix : 버그 수정`<br>
`Docs : 문서 수정`<br>
`Style : 스타일 관련 기능(코드 포맷팅, 세미콜론 누락, 코드 자체의 변경이 없는 경우)`<br>
`Refactor : 코드 리펙토링`<br>
`Test : 테스트 코트, 리펙토링 테스트 코드 추가`<br>
`Chore : 빌드 업무 수정, 패키지 매니저 수정(ex .gitignore 수정 같은 경우)`<br>
<br>
<br>
**이슈를 포함한 커밋 메시지**<br>
`Resolves : #issue, ...(해결한 이슈 , 생략 가능)`<br>
`See also : #issue, ...(참고 이슈, 생략 가능)`<br>
<br>
**규칙**
<br>
- 제목과 본문을 빈 행으로 구분한다
- 제목을 50글자 내로 제한
- 제목 첫 글자는 대문자로 작성
- 제목 끝에 마침표 넣지 않기
- 제목은 명령문으로 사용하며 과거형을 사용하지 않는다
- 본문의 각 행은 72글자 내로 제한
- 어떻게 보다는 무엇과 왜를 설명한다

<br>
<br>

### 버전 규칙
https://semver.org/lang/ko/ - 유의적 버전 `2.0.0`에 따라 진행됩니다.

<br>
<br>

### 라이선스
모든 프로젝트는 오픈소스로 MIT라이선스를 사용합니다.

<br>
<br>

**코드에 라이선스 삽입법**
```js
/*
 * <프로젝트 이름, 버전>
 *
 * (c) 2022 WADE Open Source Software. and its affiliates.
 * Released under the MIT License.
 * <해당 프로젝트의 라이선스 경로>
 */
```
