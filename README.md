$ rm -rf .git                                   : 기존에 git을 사용하던 main branch 해제
$ git init                                      : 해당 파일에서 git을 사용하겠다고 선언
$ git branch branchName                         : branchName을 가진 branch 생성
$ git switch branchName                         : branchName이란 branch로 변경
$ git add .                                     : 해당 branch에서 작성한 모든 파일을 stagingarea로 이동
$ git commit -m "message"                       : stagingarea에 있는 파일에 남길 메세지 작성
$ git push  githubRepositoryAddress  branchName : onlineRepository에 branch를 업로드함