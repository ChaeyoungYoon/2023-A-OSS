작업 디렉토리와 스테이징 영역을 숨김(stash)에 저장하고 작업 폴더를 정리
$ git stash
$ git stash –m ‘메시지’
$ git stash save
$ git stash save ‘메시지’
최근 또는 지정된 임시 저장소 내용을 가져와 반영하고 삭제
$ git stash pop
$ git stash pop stash@{n}
최근 또는 지정된 임시 저장소 내용을 가져와 반영, 작업 디렉토리에 반영, stash 목록은 그대로
$ git stash apply
$ git stash apply stash@{n}
최근 또는 지정된 임시저장소 내용을 가져와 반영, 작업 디렉토리와 스테이징 영역도 반영, 
stash 목록은 그대로
$ git stash apply --index 
$ git stash apply --index stash@{n}

기준 브랜치에서 hotfix 브랜치 병합
$ git merge hotfix
• fast-forward, 3-way merge
무조건 3-way 병합 수행
$ git merge --no-ff hotfix
fast-forward인 경우에만 병합 진행
$ git merge --ff-only hotfix
현재 브랜치에서 커밋 하나만 생성해서 병합
$ git merge --squash hotfix

비주얼스튜디오코드에서 깃 저장소를 생성하고 파일 생성
탐색기 활동바, 버전 콘트롤 활동바

비주얼스튜디오코드에서 파일을 추가, 커밋
Changes, Staged Changes

Changes, Staged Changes
확장 Git Graph 설치와 활용

비주얼스튜디오코드에서 파일 비교 기능 수행
Changes, Staged Changes
Git Graph
 다음 하부의 파일을 클릭
  Uncommitted changes
  각 커밋

HEAD~2의 내용으로 작업 디렉토리와 스테이징 영역, 깃 저장소에 복사
$ git reset --hard HEAD~2
HEAD~2의 내용으로 스테이징 영역과 깃 저장소에 복사
$ git reset --mixed HEAD~2
HEAD~2의 내용으로 깃 저장소에 복사
$ git reset --soft HEAD~2
이전에 수행한 reset을 바로 취소하는 명령
$ git reset --hard ORIG_HEAD

취소 revert 전체 조건
Nothing to commit, working tree clean
HEAD를 취소해 HEAD~ 상태로 가는 커밋을 생성
$ git revert HEAD
$ git revert HEAD --no-edit
