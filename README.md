# design-systems

프로젝트에서 함께 쓰는 디자인 시스템 문서를 모아 두는 저장소입니다.
문서는 여기 한 곳에서만 고치고, 각 프로젝트는 복사본을 두지 않고 이 저장소의 파일을 가리킵니다.

## 문서

| 폴더 | 내용 |
| --- | --- |
| [swiftui-liquid-glass](swiftui-liquid-glass/DESIGN.md) | SwiftUI / iOS Liquid Glass Design System — Apple 의 동적 재질과 시스템 컴포넌트를 우선하는 SwiftUI UI/UX 지침 |

## 프로젝트에서 쓰기

프로젝트의 지침 파일이나 README 에 아래 주소를 적어 둡니다.

```
https://github.com/jheroorehj/design-systems/blob/main/swiftui-liquid-glass/DESIGN.md
```

파일 내용만 받아 오려면:

```bash
curl -fsSL https://raw.githubusercontent.com/jheroorehj/design-systems/main/swiftui-liquid-glass/DESIGN.md
```

## 쓰는 곳

- [QuotaBar](https://github.com/jheroorehj/QuotaBar) — macOS 메뉴바 앱

### Mac 앱에서 쓸 때

이 문서는 아이폰·아이패드 앱을 기준으로 썼습니다. Mac 앱에서는 일부만 따릅니다.

| | 규칙 | Mac 에서 |
| --- | --- | --- |
| 그대로 따름 | 간격 값(4 · 8 · 12 · 16 …), 시스템 색, 유리 위에 유리를 겹치지 않기, 접근성 설정 대응 | 똑같이 적용합니다 |
| 따르지 않음 | 버튼을 최소 44 × 44 pt 로 | 손가락이 아니라 마우스로 누르므로 더 작아도 됩니다 |
| 따르지 않음 | 탭 바, 뒤로 가기, 밀어서 돌아가기, 아래에서 올라오는 시트 | 아이폰식 화면 이동이라 Mac 의 창·메뉴 구조와 맞지 않습니다 |

## 라이선스

[MIT](LICENSE)
