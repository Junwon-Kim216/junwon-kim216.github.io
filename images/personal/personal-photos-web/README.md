수평 보정 사진 — 홈페이지용 WebP

새로 올린 JPG 6장을 작은 홈페이지 갤러리에 맞게 변환했습니다.
현재 구도와 가로세로 비율을 유지했으며, 크기 축소와 WebP 압축을 적용했습니다.
세로 사진은 높이 400px, 야구 사진은 높이 300px입니다.
홈페이지 표시 크기는 기존 계획대로 세로 사진 약 180px, 야구 사진 약 140px 높이를 사용하면 됩니다.
사진 6장 합계: 172,906 bytes (약 173 KB). 원본 합계 대비 약 97.2% 감소했습니다.

적용 방법

1. 이 ZIP을 압축 해제합니다.
2. 홈페이지 저장소의 images/personal/ 폴더에 ZIP의 images/personal/ 안에 있는 WebP 6개를 복사합니다.
3. 같은 이름의 이전 WebP가 있으면 이번 파일로 교체합니다.
4. 아래 표에 맞게 홈페이지 img 태그의 width, height 속성도 확인합니다.

| 새 원본 | 교체할 파일명 (images/personal/ 안) | 실제 크기 (px) | 용량 |
| --- | --- | --- | --- |
| badminton_1.jpg | badminton-1.webp | 304 × 400 | 24.9 KB |
| badminton_2.jpg | badminton-2.webp | 274 × 400 | 22.2 KB |
| graduate_1.jpg | graduation-group.webp | 300 × 400 | 15.8 KB |
| graduate_2.jpg | graduation-portrait.webp | 300 × 400 | 31.1 KB |
| baseball_1.jpg | baseball-stadium.webp | 400 × 300 | 23.1 KB |
| baseball_2.jpg | baseball-panorama.webp | 819 × 300 | 55.9 KB |

배드민턴 사진 적용 시

수평 보정 후 배드민턴 두 장의 비율이 달라졌습니다.
기존처럼 두 사진을 똑같은 가로 폭에 맞추면 표시 높이가 달라질 수 있습니다.
VS Code의 Codex에 아래 내용을 전달하면 됩니다.

images/personal/에 수평 보정한 새 WebP 6장을 넣었어.
이미지의 실제 크기를 읽어 기존 Personal 섹션의 img width/height를 갱신해줘.
새 크기는 badminton-1.webp 304x400, badminton-2.webp 274x400,
graduation-group.webp와 graduation-portrait.webp 각각 300x400,
baseball-stadium.webp 400x300, baseball-panorama.webp 819x300이야.
현재 사진 비율과 전체 구도를 유지하고, 배드민턴 두 장은 같은 높이로 표시되도록 가로 폭을 조절해줘.
기존의 작은 사진 배치와 모바일 대응을 유지하고, 자르거나 늘려서 왜곡하지 말아줘.
사진 링크, 클릭 확대, 라이트박스, hover 확대는 추가하지 말아줘.

이 ZIP에는 새 이미지와 적용 안내만 포함되어 있습니다.
홈페이지 소스 또는 실제 배포 상태는 변경하지 않았습니다.
