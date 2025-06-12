# Project_VR

### 1. 아이디어 구상
장르 : 리듬 게임

배경 : 현대 오케스트라 공연장

레퍼런스 : Maestro (https://www.meta.com/fr-fr/experiences/maestro/6963344583787383)

### 2. 게임 개요 작성
가제 : Maestro : imitation

핵심 시스템 : VR Hand Tracking

플랫폼 : VR

목표 플레이 시간 : 3~4분

### 3. 핵심 메커니즘 설계
#### 1). 노드
  - 긴 노드 시작 : 손바닥이 하늘을 보게 한 뒤 아래에서 위로 올리면 시작
  - 긴 노드 종료 : 손을 치우면 종료
  - 화살표 노드 : 손을 가볍게 화살표 방향으로 휘둘러 처리 (beat saber)
  - 정점 : 지휘봉을 든 손(환경설정에서 선택)으로 해당 지점을 지휘봉으로 찌르면 처리
  - 크기가 작아지는 정점 : 손바닥을 하늘로 보게 한 뒤 정확한 타이밍에 주먹을 쥐어 처리
#### 2). 타이밍
  - 노드 : 플레이어 쪽으로 천천히 다가오도록
  - Beat Line : 노드가 해당 라인에 걸쳤을 때 처리되면 Perfect 히트 판정
  - Effect : 노드 히트 판정 시 시각적 이펙트
#### 3). 점수
  - 히트 판정시 점수(랭크) 증가
  - Perfect, miss 처리 노드 수 표시

### 4. UI, UX 
메인 메뉴 구성 : 곡 선택(1~2개)

인게임 HUD : 공연장 단상 위(앞 : 연주자, 뒤 : 관객, 위 : 조명, 아래 : 악보)

### 5. 그래픽 스타일 기획
Beat Line : 흰색 실선(radiation)

Node : 노란색 square?

Baton : 흰색 지휘봉

Hand : motion tracking

### 6. 사운드 기획
클래식(사계 봄 or 푸른 도나우강) or Sweet dreams, my dear(Inst)

### 7. 작업 우선순위 및 일정 계획
1일차 : Unity VR setting, GitHub repository, Beat Line 구현

2일차 : 노드 기능 구현

3일차 : 타이밍 기능 구현

4일차 : 점수 구현, 인게임, Score Board UI 구현

5일차 : 곡 구현

6일차 : Title(곡 선택) UI, Esc (일시정지) UI 구현, 빌드

7일차 : 버그 수정, 빌드
