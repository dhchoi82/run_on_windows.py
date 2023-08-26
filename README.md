# Run_on_Windows.py

- Python이 설치되지 않은 윈도우에 실행 가능한 Python 모듈을 배포하기 위한
프로그랩입니다.
- main 디렉토리에 배포용 Python 모듈을 복사하고, python 디렉토리에
실행을 위한 python을 복사하면 배포를 위한 준비가 완료됩니다.
- 실행파일은 `proto.cmd`이고 `python main`의 CMD 명령어로
실행되는 구조입니다.
- 프로그램 실행 시 PATH 환경변수를 임시로 재설정하므로 배포되는 환경에
설정된 PATH 변수의 영향을 받지 않습니다.
