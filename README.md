체크아웃(Checkout): 중앙 저장소에서 로컬로 코드 사본을 가져와 작업하는 과정입니다.

Jenkins는 저장소에서 최신 소스를 자동으로 체크아웃하여 빌드 파이프라인을 시작합니다.

커밋(Commit): 로컬에서 수정한 내용을 중앙 저장소에 반영하는 작업입니다.

개발자가 코드를 커밋하면 Jenkins가 자동으로 변경 사항을 감지하고 빌드를 시작할 수 있습니다.

버전 추적(Revision Tracking): SVN은 각 커밋마다 **버전 번호(revision number)**를 부여합니다.

Jenkins는 이 버전 정보를 사용해 어떤 버전의 소스를 빌드했는지 추적할 수 있습니다.
