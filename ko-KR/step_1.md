패키지를 설치하려면 Raspberry Pi가 온라인 상태여야 합니다. 패키지를 설치하기 전에 Raspberry Pi의 운영 체제인 Raspbian을 업데이트 및 업그레이드하세요.

+ 터미널 창을 열고 다음 명령어를 입력하여 이 작업을 수행합니다:

![터미널 열기](images/terminal.png)

```bash
sudo apt-get update
sudo apt-get upgrade
```

+ 이제 터미널 창에 `install` 명령어를 입력하여 필요한 패키지를 설치할 수 있습니다. 예를 들어 Sense HAT 소프트웨어를 설치하는 방법은 다음과 같습니다:

```bash
sudo apt-get install sense-hat
```
