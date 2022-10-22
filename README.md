# svelte 학습 - 인프런 Svelte.js [Core API] 완벽 가이드

## 시작하기
1. 선언적 렌더링
2. 조건문과 반복문
3. 이벤트 핸들링
4. 컴포넌트
5. 스토어
6. Todo 예제 만들기

## 라이프 사이클

1. 기본 개념
2. 잠깐! Vscode로 Svelte 프로젝트 시작하기 복습 및 'code' 명령어 사용
3. onMount, onDestroy
4. beforeUpdate, afterUpdate
5. 라이프사이클 모듈화
6. tick

## 보간법
1. 내용/속성/표현식 보간ㄹ
2. 원시 HTML, 데이터 디버깅

## 반응성
1. 데이터의 불변성과 가변성
2. 할당
3. 자바스크립트 Label 구문의 이해
4. 반응성 구문의 이해
5. 반응성 구문 패턴 정리

## 클래스와 스타일
1. 클래스와 스타일 속성 바인딩
2. 클래스 바인딩 패턴 저일(class 지시어)
3. 스타일 유효범위(Hash)와 전역화(Global)
4. @keyframes 전역화

## 요소 바인딩
1. 일반 요소 바인딩(this)
2. 입력 요소 바인딩(Properties, group) 패턴 정리
3. 편집 가능 요소 바인딩(contenteditable)

## 조건과 반복과 키
1. 조건 블록 패턴 정리
2. 반복 블록의 Key 사용
3. 반복 블록 패턴 정리
4. 키 블록

## 비동기
1. 자바스크립트 비동기 처리의 이해와 사용 패턴 정리 - 1부
2. 자바스크립트 비동기 처리의 이해와 사용 패턴 정리 - 2부
3. 영화 검색 API 예제 만들기
4. Await 블록
5. Await 블록으로 영화 검색 API 예제 리펙토링

## 사용자 입력 핸들링
1. 인라인 이벤트 핸들러
2. 다중 이벤트 핸들러
3. 이벤트 수식어

## 컴포넌트
1. 컴포넌트 개요(with 컴포넌트 바인딩)
2. 부모에서 자식으로(Props)
3. Props 양방향 바인딩
4. 자식에서 부모로(Event Dispatcher)
5. 기본/커스텀 이벤트 포워딩(Forwarding)
6. ContextAPI(getContext, setContext)
7. 모듈 상황(Module context)에서 데이터 정의
8. 오디오 플레이어 예제
9. $$props와 $$restProps

## 슬롯
1. 단일 슬롯과 Fallback content
2. 이름을 가지는 슬롯
3. 범위를 가지는 슬롯(Props)
4. 슬롯 포워딩(Forwarding)
5. $$slots

## 스토어
1. 쓰기 가능 스토어(writable) & 수동 구독과 자동 구독
2. 읽기 전용 스토어(readable)
3. 계산된 스토어(derived)
4. 스토어 값 얻기(get)
5. 커스텀 스토어 개념과 예제

## 액션
1. 사용 패턴 정리
2. 요소 Zoom In-Out 예제

## 특별한 요소
1. 컴포넌트 재귀 호출(self)
2. 동적 컴포넌트 렌더링(component)
3. window
4. head, body
5. options - 불변성 선언(immutable)
6. options - 접근 허용(accessors)
