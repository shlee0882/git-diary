### git-diary git 오토커밋 스케줄링


- 매일매일 일기장형식의 md파일이 git-diary 원격저장소에 오토커밋 푸시됩니다.
- 크론탭을 사용해 스케줄링을 걸어놓아 github에 매일 잔디밭을 만들 수 있습니다.
- md파일의 타이틀은 커밋한 해당 날짜를 갖고 있습니다.

- 제가 설정한 환경은 gcp compute engine의 ubuntu linux 18.04에서 git과 ssh을 연동하였고 크론탭에서 오전 7시에 스케줄링되어 구동됩니다.

- 설정 방법 : [https://shlee0882.tistory.com/270?category=703461](https://shlee0882.tistory.com/270?category=703461)
