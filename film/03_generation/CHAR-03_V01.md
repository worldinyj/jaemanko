# CHAR-03 V01 — 1950년대 인물 마스터
2026-11-27 / READY_FOR_MANUAL_MIDJOURNEY / V2.4

사용자 승인 STYLE-01(TEST-03_V02)의 현대적 시네마틱 반사실 3D를 유지한다. 이번 단계는 인물 마스터 후보 한 장 선정만 수행. 수난·자전거·영상 생성은 보류.

## 사진 검토 및 참조 선택
- 주 참조: CHAR-00-R01, 고려신학교 학적부 사진 영역(304×376). 모자 없는 정면에 가까운 구도, 옆으로 정리된 머리와 정장·넥타이를 확인할 수 있다. 사진 자체의 인물 귀속은 제공된 학적부에 근거한다.
- 보조 검수: CHAR-00-R02(ARC-01-02), ZIP의 '01 학업 및 졸업 기록/02 학사모 사진.jpg'(516×730). 얼굴의 윤곽과 세부 표현을 확인하는 데 유용하나 학사모가 헤어스타일을 가리므로 일반 복장의 Omni Reference로는 사용하지 않는다. 인물 귀속은 가족 아카이브 설명 및 가족 확인에 따른다.
- 단체·전신 사진은 해당 인물 위치가 지정되지 않아 이번 참조에서 제외한다.
- 사진의 색상은 추정하지 않는다. 중립적인 회색 정장, 흰 셔츠, 어두운 넥타이는 제작용 선택이다. 실제 원본 사진은 공개 저장소에 게시하지 않는다.

## Midjourney 웹 일반 생성하기 (Editor 아님)
1. V7 선택. R01 사진을 Omni Reference 칸에 넣는다(이미지 1개).
2. 사용자 승인 TEST-03_V02를 Style Reference 칸에 넣는다. 풍경을 인물 구도로 끌어오지 않도록 Image Prompt에는 넣지 않는다.
3. 2:3 세로 비율. 아래 프롬프트 실행. 참조 URL은 사용자가 이미지를 UI에 배치한 경우 텍스트에 별도로 적지 않는다.
4. 결과 중 한 후보를 CHAR-03_V01로 제출해 가족 검수. 생성 결과가 마음에 들지 않으면 닮음/화풍 중 문제 하나만 바꿔 수정한다.

```text
A refined contemporary cinematic semi-realistic 3D animated character portrait of the Korean Christian evangelist shown in the archival reference photograph, a man in his forties in the 1950s, front-facing waist-up portrait, preserve the distinctive facial structure, natural eye shape, nose and mouth, neatly side-parted dark hair, natural human proportions, simple mid-century gray suit, white shirt and dark tie, calm gentle expression with closed lips, clean warm ivory studio background, soft natural daylight, tactile matte skin and fabric, subtle realistic details, dignified and approachable, sophisticated animated film character, no vintage filter, no caricature
--v 7 --ar 2:3 --raw --s 100 --chaos 0 --ow 200 --sw 150 --no graduation cap, academic gown, text, watermark, sepia
```

## QC
- 가족 승인: R01/R02를 기준으로 얼굴 특징과 나이가 자연스럽고 할아버지의 모습과 닮았는지 가족이 직접 판단.
- 화풍: TEST-03의 밝고 세련된 재질/자연광과 조화. 과장된 만화적 비율, 지나친 피부 미화, 실사 역사사진 오인 가능성은 피한다.
- 복장: 1950년대 한국의 정장 차림과 부합; 학사모/가운 없음. 색은 제작 추정.
- 구도: 상반신 중심, 머리와 어깨가 프레임 내에 충분히 들어오고 다음 장면의 Omni Reference로 활용 가능.
- 결과 등록 전 실제 얼굴 검수 완료를 주장하지 않는다. 가족사진의 외부 서비스 사용 권한 및 공개 설정 확인 후 실행.
- 참고: STYLE-01은 승인된 이미지이나 GitHub 업로드본은 첨부 원본과 바이트가 다르므로 가능하면 사용자 Midjourney에서 직접 승인한 V02 또는 정확한 첨부 원본을 스타일 참조로 이용한다.
