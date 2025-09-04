# QuickLocalize — CSV → ScriptableObject (Unity Editor Tool)

**한 줄 설명**: CSV를 Localization ScriptableObject로 임포트하고, 런타임에서 Tr("key")/LocalizedTextTMP로 텍스트를 교체하는 간단 로컬라이즈 유틸.

## Features
- CSV → ScriptableObject 원클릭 임포트
- TextMeshPro 연동(LocalizedTextTMP)
- 언어 전환 샘플 제공
- Unity 2021.3+ / Built-in/HDRP/URP 호환

## Quick Start
1. `Window > QuickLocalize > CSV Importer`
2. CSV(TextAsset) 지정 → **Import**
3. 샘플 씬 실행(버튼으로 **KR/EN 전환** 확인)

**샘플 경로 예시**
- Scene: `Assets/QuickLocalize/Samples/LocalizationSample.unity`
- CSV:  `Assets/QuickLocalize/Samples/Localization/hello.csv`
- Generated: `Assets/QuickLocalize/Generated/LocalizationDB.asset`

## FAQ
- **한글이 깨져요**: TMP 폰트 SDF 생성(폰트 자가 임베딩) 후, TextMeshPro 폰트를 교체하세요.
- **버전 호환**: Unity 2021.3 이상 권장.

## Support
- Email: youremail@example.com

> 이 레포는 **문서와 스크린샷**만 포함합니다(유료 에셋 파일은 포함하지 않습니다).
