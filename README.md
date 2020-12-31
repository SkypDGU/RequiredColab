# RequiredColab
## 해당 리포지토리의 주피터 노트북들과 SkypDGU에 있는 [darknet](https://github.com/SkypDGU/darknet)과 [OIDv4_ToolKit](https://github.com/SkypDGU/OIDv4_ToolKit) 를 같은 폴더에 놓고 진행

### DataDownload.ipynb 
: [OIDv4_ToolKit]를 사용하여 Human Body 클래스의 이미지를 다운 받고 해당 이미지들을 90도 돌려 전처리해 서있는 사람과 쓰러진 사람 데이터 생성

### train.ipynb 
: [darknet]를 사용하여 DataDownload.ipynb에서 만든 데이터셋을 다운받은 darknet53.conv.74를 사전 모델로 학습을 진행한다. 학습 완료가 되면 학습된 가중치로 쓰러진 객체를 검출해 
