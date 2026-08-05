# 알차다(RCHADA) 홈페이지

알차다 공식 홈페이지의 정적 배포본입니다. GitHub Pages로 호스팅됩니다.

| 파일 | 페이지 |
|---|---|
| `index.html` | 회사소개 (홈) |
| `service.html` | 서비스 소개 |
| `contact.html` | 제휴 문의 |

- 빌드 과정·서버 로직·외부 CDN 의존성이 없는 순수 정적 사이트입니다.
- CSS/JS는 각 HTML에 인라인되어 있으며, 자산 참조는 모두 상대 경로입니다.
- 자산: `service_images/`, `partner_logos/`, 루트의 `hero_*`·`app_screen_*_web.png`

## 수정 방법

이 저장소는 **배포 산출물**입니다. 직접 편집하지 말고
작업본에서 수정한 뒤 배포 스크립트(`homepage/deploy.sh`)로 갱신하세요.

## 문의

1899-1549
