# Arduino-RCCar [![works badge](https://cdn.rawgit.com/nikku/works-on-my-machine/v0.2.0/badge.svg)](https://github.com/nikku/works-on-my-machine)
> 아두이노로 만든 무선 조정 자동차입니다.

## 사용 부품
- Arduino Nano
- HC-06
- L298N

## 사용 전원
### 아두이노 전원
- 1.5V * 4

### L298N 모터 드라이버 전원
- 18650 배터리(3.7V) * 2

## 회로도
이미지에서 모터 드라이버는 L298N 텍스트로 대체되었습니다.

- D2 <-> L298N IN1
- D3 <-> L298N IN2
- D4 <-> L298N IN3
- D5 <-> L298N IN4
- D7 <-> HC-06 RXD
- D8 <-> HC-06 TXD

![sketch](https://raw.githubusercontent.com/SkyLightQP/Arduino-RCCar/master/sketch.png)