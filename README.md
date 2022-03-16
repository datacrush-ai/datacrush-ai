# datacrush-ai

## github role

1. 제목과 본문을 빈 행으로 구분
2. 제목을 50글자 내로 제한
3. 제목 첫글자는 대문자로 작성
4. 제목 끝에 마침표 넣지 않기
5. 제목은 명령문으로 사용하며 과거형을 사용하지 않음
6. 본문의 각 행은 72글자 내로 제한
7. 어떻게 보다는 무엇과 왜를 설명

 
<br>
### 커밋 작성 패턴

{동작, 타입을 나타내는 접두사, 대문자로 작성}: #번호 - 커밋 제목
상세 커밋 내용은 -(hyphen)을 넣어 계층 목록으로 작성

<br>
### 동작, 타입을 나타내는 접두사 목록

1. ADD : 새로운 파일이 추가된 경우에 대한 커밋
2. FEAT : 새로운 기능에 대한 커밋
3. FIX : 버그 수정에 대한 커밋
4. CHORE : 빌드 업무 수정, 패키지 매니저 수정(ex .gitignore 수정 같은 경우)에 대한 커밋
5. STL : 스타일 관련 기능(코드 포맷팅, 세미콜론 누락, 코드 자체의 변경이 없는 경우)에 대한 커밋
6. DOCS : 문서 수정에 대한 커밋
7. REFACTOR :  코드 리팩토링에 대한 커밋
8. TEST : 테스트 코드 수정에 대한 커밋
9. WIP : Work In Progress, 작업 도중 임시저장에 대한 커밋

 
<br>
### 위 포맷으로 작성한 제목/본문 예시

1. ADD: #1 - kakao 로그인창 구현

(제목과 본문 한 칸 분리)

- kakao 로그인을 위한 config 파일 추가

 

2. FIX: #2 - 자막 불러오기 도중 권한문제 오류 수정

(제목과 본문 한 칸 분리)

- 관계자 테이블 미스매치 오류 수정

- 개인 관계자별 권한 비정확성 수정

 

3.TEST: #3 - 개인별 설정파일 설정 후 테스트 
