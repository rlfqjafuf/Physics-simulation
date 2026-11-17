# ProjectileLab EDU Web

포물선 운동을 학습하는 2D/3D 웹 시뮬레이터입니다. HTML/CSS/JavaScript로 작성되었으며 외부 라이브러리나 빌드 단계가 필요 없습니다.

## 기능
- 2D/3D 궤적 표시, 터치/마우스 카메라 회전
- 초기 속력, 발사각, 높이, 중력, 질량, 재생 속도 조절
- 실시간 물리량과 그래프, CSV 내보내기
- 공기 저항이 없는 이상적인 포물선 운동

## GitHub Pages 배포
1. GitHub에서 `ProjectileLab-EDU`라는 **Public** 저장소를 만듭니다. README 자동 생성은 생략해도 됩니다.
2. 이 폴더의 `index.html`, `README.md`, `.nojekyll`, `.gitignore`를 저장소 최상위(root)에 업로드하고 Commit changes를 누릅니다.
3. 저장소 **Settings → Pages → Build and deployment**에서 **Deploy from a branch**를 선택합니다.
4. Branch를 **main**, Folder를 **/(root)**로 선택하고 Save를 누릅니다.
5. 배포가 완료되면 `https://사용자이름.github.io/ProjectileLab-EDU/`에서 실행합니다. 정확한 주소는 Pages 설정에서 확인하세요.

## 실행 및 검증
- 배포 전: `index.html`을 데스크톱 브라우저에서 열어볼 수 있습니다. iPad 파일 미리보기에서는 스크립트 실행이 제한될 수 있으므로 Pages 주소로 접속하세요.
- 배포 후: 슬라이더 6개가 표시되는지, 시작 버튼과 2D/3D 전환이 동작하는지, 그래프가 그려지는지 확인하세요.
- 페이지가 비어 있으면 브라우저 개발자 콘솔 오류를 확인하세요.

## 모델 가정
공기 저항 없음, 일정한 중력가속도, 평평한 지면(y=0). 질량은 궤적에 영향을 주지 않습니다. 3D는 동일한 평면 궤적의 입체 시각화입니다.
