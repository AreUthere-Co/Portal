# Contributing
이 저장소에 기여하고자 할 때는 먼저 변경하기 전에 이 저장소의 소유자와 Issue 등록, 이메일[softyoon@gmail.com] 또는 기타 방법을 이용하여 변경하려는 사항에 대해 논의하십시오.

우리는 행동 강령을 가지고 있으므로 프로젝트와의 모든 상호 작용에서 이를 준수하여야 합니다.

## 시작전에 알아야 할 사항
- Issues에 질문을 남기지 말아주세요.
    - 이슈는 버그나 기능개선등의 컨트리뷰션 활동과 프로젝트의 변경 대한 이력을 관리하는데 사용합니다. 단순한 기능 문의나 질문등은 [softyoon@gmail.com] 을 통해 해주시기 바랍니다. 
    - 위 항목에 포함되지 않는 Issue등록건은 프로젝트 리더의 판단에 따라 reply없이 삭제되거나 Closed 될 수 있습니다.

## 기여할수 있는 것들
- Bug
- Review
- Document
- Testing
- Design
- Enhancements
- ...and more

## Pull Request Checklist  
1. 빌드시 필요하거나 필요하지 않는 build dependency, install 항목에 대하여 확인하여 정리해야 합니다.
1. 인터페이스 변경에 대한 세부 사항에 대하여 README.md를 업데이트하십시오. 여기에는 새로운 환경 변수, 노출 된 포트, 파일 경로 및 컨테이너 파라미터 등이 포함됩니다.
1. 예제 파일 및 README.md의 버전을 Pull Request 적용을 알수 있도록 버저닝하세요. 우리가 사용하는 버전 관리 체계는 [SemVer](http://semver.org/) 입니다.
1. 다른 두 명 이상의 개발자 리뷰가 만족할 경우, Pull Request를 Merge할 수 있습니다. 권한이없는 경우 두 번째 리뷰어에게 Pull Request를 Merge 요청할 수 있습니다.
1. 기여하고자 하는 모든 리소스의 작성방법은 아래의 스타일 가이드에 따라 작성하여야 합니다.

## 스타일 가이드
### Python
프로젝트는 기본적으로 [PEP8 스타일가이드](https://www.python.org/dev/peps/pep-0008/)에 따라 작성되어야 합니다.  
프로젝트에 상세화된 가이드가 있다면 프로젝트의 스타일가이드가 PEP8 가이드보다 우선됩니다.

### Document
파이썬 프로젝트의 기본 도큐먼트는 [reStructuredText](http://docutils.sourceforge.net/rst.html) 파일의 형식을 따라야 하나 이 프로젝트의 경우 교육의 목적과 편의를 위해 [Markdown](http://guides.github.com/features/mastering-markdown/) 형식의 문서로 작성되며 Github에서 동작하여 html문서형태로 인식되는 구조여야 합니다.  

### Git commit message
- 제목과 본문은 한줄 띄어 분리합니다.
- 제목은 영문기준으로 72자 미만으로 작성합니다.
- 영문 작성시 현재시제로 작성합니다.
- 영문 작성시 명령형으로 작성합니다.
- issue와 pull request 참조는 본문에 작성합니다.
- 메세지 제목의 시작에 이모지을 활용해 보세요.
    * :art: `:art:` when improving the format/structure of the code
    * :racehorse: `:racehorse:` when improving performance
    * :non-potable_water: `:non-potable_water:` when plugging memory leaks
    * :memo: `:memo:` when writing docs
    * :penguin: `:penguin:` when fixing something on Linux
    * :apple: `:apple:` when fixing something on macOS
    * :checkered_flag: `:checkered_flag:` when fixing something on Windows
    * :bug: `:bug:` when fixing a bug
    * :fire: `:fire:` when removing code or files
    * :green_heart: `:green_heart:` when fixing the CI build
    * :white_check_mark: `:white_check_mark:` when adding tests
    * :lock: `:lock:` when dealing with security
    * :arrow_up: `:arrow_up:` when upgrading dependencies
    * :arrow_down: `:arrow_down:` when downgrading dependencies
    * :shirt: `:shirt:` when removing linter warnings
