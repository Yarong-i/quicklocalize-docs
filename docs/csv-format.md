---
layout: default
title: CSV 형식 가이드
---
# CSV 형식 가이드

기본 열
- `key` (고유키)
- 언어코드 열: `ko`, `en`, `ja` …

예시
-key,ko,en
-HELLO,안녕하세요,Hello
-QUIT,종료,Quit

주의
- 첫 컬럼은 반드시 `key`
- 중복 key는 Import 시 경고
- UTF-8(가능하면 BOM 없음) 권장