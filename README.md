# core3566PWM
The PWM tuning for core3566
## 1. sudo luckfox-config
## 2. select interface
<img width="916" alt="image" src="https://github.com/itemhsu/core3566PWM/assets/25599185/8bebba44-9096-42a5-a137-82efee4fa202">

## 3. select 4 PWM
<img width="730" alt="image" src="https://github.com/itemhsu/core3566PWM/assets/25599185/132196ed-61d3-4bb6-b47b-65b6f534c571">

## 4. select port
<img width="804" alt="image" src="https://github.com/itemhsu/core3566PWM/assets/25599185/891fcbce-fc86-471b-89eb-76bc2b50cf12">

* port definition

<img width="922" alt="image" src="https://github.com/itemhsu/core3566PWM/assets/25599185/848f9b89-3499-4baa-951a-c3f19c5b6de0">

* pi 4 definition

  <img width="414" alt="image" src="https://github.com/itemhsu/core3566PWM/assets/25599185/c5ed69a4-fff6-498a-b6fb-3863a304c822">

## 確認 pwm 使用腳位
<img width="869" alt="image" src="https://github.com/itemhsu/core3566PWM/assets/25599185/e85d89ab-dcb7-428c-9a35-69d45dbcdce7">

* dtoverlay=pwm-2chan,pin=12,func=4,pin2=13,func2=4 代表用pin12 pin13
* core3566 相對位置是pwm8 pwm9

