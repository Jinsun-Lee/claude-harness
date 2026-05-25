# 레포 명명 규칙

## 기본 원칙

- 기본적으로 `kebab-case`를 사용한다.
- 일반 레포는 `{접두어}-{주제}[-{추가요소}]` 구조를 따른다.
- `접두어`는 레포를 묶는 기준이며, 카테고리, 플랫폼, 제품명, 도메인이 될 수 있다.
- `주제`는 레포가 무엇에 대한 것인지 나타내는 핵심 도메인이다.
- `추가요소`는 같은 주제를 더 구체화할 때 사용한다. 타입, 버전, 공개 범위, 대상, 환경 등을 나타낼 수 있다.

예:

- `study-algorithm-private`
- `study-llm-local`
- `youtube-upload-agent`
- `ai-template`

## 접두어

### 카테고리

- `study`: 계속 관리하거나 참고하는 학습 자료
- `lecture`: 정해진 기간 내에 수강하는 과목
- `project`: 정해진 기간 내에 진행한 프로젝트
- `job`: 취업, 지원, 면접 준비 자료
- `race`: 자율주행 레이스, 경진대회, 경기 운영/참가 프로젝트

### 플랫폼

플랫폼이나 제품을 중심으로 묶이는 도구는 `{플랫폼}-{주제}[-{추가요소}]` 형식을 허용한다.

현재 사용하는 플랫폼 접두어:

- `claude`
- `github`
- `youtube`

## 템플릿

템플릿 레포는 `{도메인}-template` 형식을 사용하고, `template`은 항상 suffix로만 둔다.

- `ai-template`
- `cs-template`
- `devops-template`
- `embedded-template`
- `misc-template`

단, `ROS2-template`은 기존 호환성 때문에 유지한다.

## ROS2

ROS2 레포는 빌드/워크스페이스 호환성을 위해 일반 규칙과 분리한다.

- 구조: `ros2_{주제}_{추가요소}`
- `ros2_` 접두어를 유지한다.
- 뒤쪽은 `snake_case`로 작성한다.

## 예외

다음 레포는 GitHub 시스템, 개발환경 관례, 또는 짧은 고유명사 성격이 있으므로 이름을 유지한다.

- `.github`
- `Jinsun-Lee`
- `Jinsun-Lee.github.io`
- `dotfiles`
- `gitbook`
- `pin`
- `tistory`
