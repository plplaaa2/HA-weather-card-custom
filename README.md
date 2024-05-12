# HA-weather-card-custom
weather-card-custom(feat' kr-weather) [![Hits]

이 파일은 https://github.com/bramkragten/weather-card 의 파일을 일부 수정한 것입니다.
이 파일은 @dugurs의 HACS용 weather news를 기반으로 제작 되었습니다.
이 파일은 kr-weathernews.com 의 데이터를 사용합니다. 날씨 저작권은 weathernews에 있습니다.


# 적용 예

![image](https://github.com/plplaaa2/HA-weather-card-custom/assets/124797654/17ff189d-5a7e-4c97-8838-1cdc1886e2ac)

 평소

![image](https://github.com/plplaaa2/HA-weather-card-custom/assets/124797654/62c5b8c0-efb1-46ce-98d1-e4aba81b76a4)

비가 오려고 할 때

![image](https://github.com/plplaaa2/HA-weather-card-custom/assets/124797654/ba486511-69c9-4576-8465-4f42550ed77b)

비 올때


**Special Thanks**

@dugurs님

<br>

**Change Log**

| Version | Date        | 내용              |
| :-----: | :---------: | --------------------------------------------------------------------------------------- |
| v1.0  | 2024.04.25  | First version  |

# 주의사항

기본 센서 값이 'home' 로 되어 있기 때문에 weathernews 기기를 추가할 때 home으로 추가 해야 
![Uploading image.png…]()


# 설치방법

**Manual**

1. 네이버 날씨 설치 (https://github.com/dugurs/ha-weathernews)
2. Weather-card 설치 ( HACS -> frontend -> + explorer -> weather-card 설치)
3. /homeassistant/www/community/weather-card/weather-card.js 파일 교체


# 쉬운 적용방법

1. 대쉬보드 -> 편집 -> 리소스 관리
2. 예) /hacsfiles/weather-card/weather-card.js?hacstag=192732636150 선택
3. hacstag=192732636150 <- 숫자 하나 더 추가
<br>※ 브라우저 캐시 삭제 안해도 됩니다.





