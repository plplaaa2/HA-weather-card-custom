# HA-weather-card-custom
weather-card-custom(feat' naver weather) [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fplplaaa2%2FHA-weather-card-custom&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

이 파일은 https://github.com/bramkragten/weather-card 의 파일을 일부 수정한 것입니다.


# 적용 예

![image](https://github.com/plplaaa2/HA-weather-card-custom/assets/124797654/17ff189d-5a7e-4c97-8838-1cdc1886e2ac)

 평소

![image](https://github.com/plplaaa2/HA-weather-card-custom/assets/124797654/62c5b8c0-efb1-46ce-98d1-e4aba81b76a4)

비가 오려고 할 때

![image](https://github.com/plplaaa2/HA-weather-card-custom/assets/124797654/ba486511-69c9-4576-8465-4f42550ed77b)

비 올때


**Special Thanks**

HACS 네이버 날씨 제작자 miumida님
<br>

**Change Log**

| Version | Date        | 내용              |
| :-----: | :---------: | --------------------------------------------------------------------------------------- |
| v1.0  | 2024.04.25  | First version  |
| v1.1  | 2024.05.02  | 체감온도 현재온도 차이에 따른 색상 변화 안되는 문제 해결  |

# 주의사항

기본 센서 값이 'sensor.naver~' 로 되어 있기 때문에 한글을 영문으로 쓴 센서일 경우

기기 및 서비스 -> 네이버 날씨 -> 구성요소에 들어가 센서 값을 'sensor.naver~' 로 다시 수정하는 걸 권장함.

![image](https://github.com/plplaaa2/HA-weather-card-custom/assets/124797654/bf9cdd58-a41e-439f-b35d-f1776ff557c1)



# 설치방법

**Manual**

1. 네이버 날씨 설치 (https://github.com/miumida/naver_weather)
2. Weather-card 설치 ( HACS -> frontend -> + explorer -> weather-card 설치)
3. /homeassistant/www/community/weather-card/weather-card.js 파일 교체


# 쉬운 적용방법

1. 대쉬보드 -> 편집 -> 리소스 관리
2. 예) /hacsfiles/weather-card/weather-card.js?hacstag=192732636150 선택
3. hacstag=192732636150 <- 숫자 하나 더 추가
<br>※ 브라우저 캐시 삭제 안해도 됩니다.





