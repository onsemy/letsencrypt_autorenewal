# Let's Encrypt Auto Renewal
Let's Encrypt Auto Renewal for Ubuntu

## 사용법 (Ubuntu 16.04.x 기준)
- Clone 받은 스크립트(letsencrypt.service, letsencrypt.timer)를 ```/etc/systemd/system``` 으로 복사한다
- 터미널에 다음과 같이 입력한다.
``` $ sudo systemctl enable letsencrypt.timer ```