# GitTutorial
Command Line

(base) minkim@Minkim Documents % cd GitHub/GitTutorial
(base) minkim@Minkim GitTutorial % git init
/Users/minkim/Documents/GitHub/GitTutorial/.git/ 안의 기존 깃 저장소를 다시 초기화했습니다
(base) minkim@Minkim GitTutorial % git switch -C new-branch
새로 만든 'new-branch' 브랜치로 전환합니다
(base) minkim@Minkim GitTutorial % git add README.md
(base) minkim@Minkim GitTutorial % git commit -m 'AddNewLine'
[new-branch c1568c8] AddNewLine
 1 file changed, 2 insertions(+)
(base) minkim@Minkim GitTutorial % git remote -v
(base) minkim@Minkim GitTutorial % git remote add origine git@github.com:minkim7
704/GitTutorial.git
(base) minkim@Minkim GitTutorial % git push -u origin new-branch
fatal: 'origin' does not appear to be a git repository
fatal: 리모트 저장소에서 읽을 수 없습니다

올바른 접근 권한이 있는지, 그리고 저장소가 있는지
확인하십시오.
(base) minkim@Minkim GitTutorial %
