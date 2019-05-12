# HowToUseGit
Git 사용법 정리

Git initial settings

# git config
설정 내용 확인 및 변경 
- /etc/gitconfig : 시스템의 모든 사용자와 모든 저장소에 적용되는 
- ~/.gitconfig : 특정 사용자에게만 적용되는 설정
- .git/config : Git directory에 있고 특정 저장소에만 적용 된다.

# 사용자 정보
사용자 이름과 email 주소 설정
$> git config --global user.name "knightkjt"
$> git config --global user.email knightkjt@gmail.com

# 편집기
$> git config --global core.editor gvim

# Diff 도구
$> git config --global merge.tool gvimdiff

# 설정 확인
$> git config --list
