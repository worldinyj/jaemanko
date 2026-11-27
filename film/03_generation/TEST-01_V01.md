# TEST-01 V01 — 수난 속의 믿음
2026-11-27 / V2.6 / READY_FOR_MANUAL_RUN

## 목표
S03A (20~25초 예정) 수난을 표현하는 상징적 빈 실내. 1942년경의 옥고는 가족 구술에 근거하며 실제 수감 시설, 구조, 구체적인 체포·고문·재판 장면은 확인되지 않았다. 실제 감옥 복원으로 제시하지 않는다. 사용자 승인 TEST-03_V02의 현대적 시네마틱 3D 스타일 유지. 고통을 미화하지 않되 창살 사이의 작은 자연광으로 희망을 암시한다.

## 미드저니 웹 일반 생성하기
- V7, 16:9, Raw, stylize 100, chaos 0, style weight 150.
- Style Reference에 미드저니에서 승인된 TEST-03_V02 한 장만 배치. Omni Reference, Image Prompt, Starting Frame은 모두 비운다.
- 설정값은 UI 또는 프롬프트 매개변수로 지정. Editor가 아니다.
- 한 번 생성 후 4개 후보 비교, 한 장만 채택.

```text
An austere empty room symbolizing religious persecution in early 1940s colonial Korea, a closed plain wooden door, a small high barred window, a narrow warm beam of natural daylight falling diagonally across a bare worn floor, cool slate blue shadows, subdued natural colors, quiet dignity, solemn and restrained, a subtle suggestion of hope without diminishing the hardship, contemporary cinematic stylized 3D animated film, refined matte materials, believable lighting, wide static eye-level composition, no people, no identifiable prison
--v 7 --ar 16:9 --raw --s 100 --chaos 0 --sw 150 --no text, watermark, sepia, vintage filter, gore, weapons, fantasy glow
```

## QC
- 빈 실내, 작은 창, 닫힌 문, 절제된 한 줄기 자연광.
- 어둡지만 재질/공간 구분 가능; 따뜻한 빛과 청회색 그림자.
- 공포영화, 실사 역사사진, 복고풍 필터, 과한 종교적 후광 배제.
- TEST-03과 조형·재질 통일. 실제 감옥 구조의 사실적 재현으로 오인시키지 않음.
- 자막은 편집 단계에서 '1942년경 · 가족 구술에 근거한 상징적 재현'으로 표시.
- 승인 후 TEST-01_V01.png를 approved/에 저장. 현재 결과 미생성/미수신. 영상화 및 TEST-02는 이 단계의 승인까지 보류.
