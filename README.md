# tripgogo-images

여행가보자고(지큐브) 앱이 보여 주는 관광지 대표 그림입니다.

- `images/places/place-<contentid>.webp`: 768×512 WebP. contentid는 앱 번들의 장소 id입니다.
- `places.json`: 그림이 있는 곳과 교체일(`v`). 앱은 주소에 `?v=`를 붙여 받습니다.
- 🔴 실제 사진이 아니라 새로 그린 그림입니다. 실제 모습과 다를 수 있습니다. 앱에서는 늘 「그림 · 실제 모습과 달라요」를 붙입니다.
- 만드는 곳: 여행가보자고 저장소 `scripts/images/export-place-images.mjs`. 이 저장소의 파일은 손으로 고치지 않습니다.
- © 지큐브. 문의 geecube@geecube.co.kr
