---
layout: default
title: 사용법
---
# 사용법

## 기본 흐름
1. CSV 선택 → **Import**
2. `Assets/QuickLocalize/Generated/LocalizationDB.asset` 생성/갱신
3. 씬에서 **LocalizedTextTMP** 컴포넌트를 텍스트 객체에 붙이고 **Key** 지정

## 런타임 언어 전환
```csharp
// 예시
LocalizationService.SetLanguage("ko"); // or "en"
