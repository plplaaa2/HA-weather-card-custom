# HA-weather-card-custom
weather-card-custom(feat' naver weather)

**설치방법**

HA/www/weather-card/weather-card.js 파일 교체

**적용방법**

대쉬보드 -> 편집 -> 리소스 관리 -> /hacsfiles/weather-card/weather-card.js?hacstag=192732636150 <- 숫자 하나 더 추가

**주의사항**

기본 센서 값은 'sensor.naver-' 로 되어 있기 때문에 한글을 영문으로 쓴 센서일 경우

기기 및 서비스 -> 네이버 날씨 -> 구성요소에 들어가 센서 값을 'sensor.naver~' 로 다시 수정하는 걸 권장함.
