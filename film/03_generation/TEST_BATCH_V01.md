# TEST-BATCH-01 | 대표 장면 3종 | V2.1
2026-11-27 · READY_FOR_MANUAL_MIDJOURNEY / 생성 미실행

사용자 피드백: 현대적이고 밝은 시네마틱 이미지 방향과 세 대표 장면에 긍정적 반응. 최종 스타일/인물 외형 승인은 아직 아님.
V2.0 비주얼 가이드 준수. 시대는 과거, 표현은 현대. 수난은 절제된 무게, 일상은 따뜻한 자연광, 마지막은 기독교적 영원한 소망. 16:9, 텍스트는 편집에서 추가. Midjourney를 제작 도구로 유지. 현재 연결 도구에서 Midjourney 직접 실행 불가(플러그인 검색 결과 없음). 아래 프롬프트는 실제 생성 준비용이며 이미지 결과가 아님.

## 0. 스타일·인물 참조 준비
CHAR-00-R01: 제공된 고려신학교 학적부에서 사진만 추출. 304×376 PNG, 비공개 로컬 자산, SHA256 8b9b71eae06fabbad2f379448ec64f91014c834051b68f8c116fc2ce436bb845. 색복원/AI 얼굴 보정 없음. 해상도는 렌더 결과이며 원래 사진의 세부 정보가 증가하지 않음. 촬영일 미확인. 원본 사료 전체/가족사진은 공개 업로드하지 않음. 가족 승인 및 Midjourney 공개 설정 확인 후 업로드.
순서: TEST-01/03은 인물 없이 생성 가능. TEST-02는 CHAR-03 후보 및 STYLE-01 승인 전까지 실제 제작 보류. 최초 STYLE-01 후보는 TEST-03 결과를 이용해 선정 가능하되 수난 컷과 조형/광원 일관성 검토. 모든 후보는 잠금 전 수정 가능.

### STYLE-01 후보 생성 (TEST-03과 겸용)
```
A luminous contemporary cinematic 3D animated short film landscape, quiet coastal Korean hills and a gently winding path toward a wide open blue sky, fresh natural greens, warm ivory sunlight, subtle atmospheric perspective, refined matte materials, sophisticated composition, natural proportions, emotionally restrained but deeply hopeful, beautiful clean modern color grading, clear foreground midground background, no vintage aesthetic, no artificial fantasy glow --ar 16:9 --v 7 --raw --s 100 --chaos 0 --no text, watermark, sepia, film scratches, angels, golden gates
```
실제 승인 결과 이미지 URL을 STYLE_URL로 입력. 아래 모든 참조 파라미터의 값은 초기 테스트이며 최종 잠금 아님.

### CHAR-03 후보 (1950년대)
```
A respectful contemporary semi-realistic cinematic 3D character portrait of the Korean man in the supplied archival portrait, middle aged in his forties, preserve the distinctive face shape, hair parting, hairline, eyes, nose and mouth as closely as the available photograph permits, natural human proportions, modest mid-century suit and tie, neutral gentle expression, matte skin and cloth, soft daylight, plain warm ivory background, no caricature, no beauty retouching --v 7 --ar 2:3 --oref PHOTO_URL --ow 200 --sref STYLE_URL --sw 150 --raw --s 100 --chaos 0 --no text, watermark
```
PHOTO_URL은 승인된 CHAR-00-R01 또는 더 선명한 가족사진 URL로 교체. 얼굴·복장을 가족이 확인한 후 CHAR-03 후보 URL을 CHAR_URL로 기록. 증명사진만으로 체격·전신·의상 색을 확정하지 않는다.

## TEST-01 | S03A | 수난 속의 믿음
구도: 눈높이보다 약간 낮은 카메라, 오른쪽 상단 좁은 창, 왼쪽 닫힌 문, 바닥에 절제된 자연광. 빈 공간. 특정 통영 감옥을 재현하지 않는다.
```
A quiet empty interior symbolizing religious persecution in colonial-era Korea, an understated closed wooden door and a small barred window high on the right, a narrow shaft of daylight crossing the plain floor, cool slate blue shadows and subtle ivory highlights, contemporary cinematic semi-realistic 3D animated short film, matte period-appropriate materials, realistic lighting, deeply solemn but not despairing, clean refined composition, no person, no identifiable prison --v 7 --ar 16:9 --sref STYLE_URL --sw 150 --raw --s 100 --chaos 0 --no text, watermark, gore, weapons, sepia, film scratches
```
모션: 카메라 아주 느린 전진, 미세한 자연광. 5초. 그림자 과장/창살 변형 없음. 자막(편집): 1942년경 · 가족 구술에 근거한 상징적 재현.
합격: 실제 시설이나 폭력 상황으로 오인되지 않음, 어둠에서도 공간이 식별 가능, 소망의 빛이 절제됨, 다음 장면과 재질 통일.

## TEST-02 | S09A | 자전거를 타는 전도사
구도: 측면 3/4 미디엄 와이드, 인물이 프레임 중앙보다 약간 왼쪽, 오른쪽에 진행 방향 여백. 밝은 들길, 자연스러운 몸 자세. 가족 구술 기반 재현. 구체 도로/의상/자전거 모델은 미확인.
```
A middle-aged Korean Christian evangelist riding a modest period black roadster bicycle along a rural dirt road beside rice fields in late 1950s coastal Korea, character based on the approved archival-photo reference, natural human proportions, quiet focused expression, understated period-appropriate dark jacket and trousers, gentle side three-quarter view, both wheels and hands clearly visible, sunlit green fields, blue sky, contemporary cinematic semi-realistic 3D animated short film, refined matte materials, soft realistic daylight, warm dignified everyday life, clean modern color grading --v 7 --ar 16:9 --oref CHAR_URL --ow 200 --sref STYLE_URL --sw 150 --raw --s 100 --chaos 0 --no text, watermark, modern vehicles, paved highway, sepia, caricature
```
모션: 완만한 측면 트래킹, 안정적인 자전거 이동. 5초. 손·페달·바퀴 왜곡 발생 시 정지 이미지 팬/줌 대체. 얼굴과 헤어라인 변화 없음.
합격: 가족이 인물 닮음을 승인, 동일인으로 인식 가능한 외형, 자전거 바퀴 2개/손·페달 정합, 시대적 오류 없음, 자연광과 색감 일관성. 사진이 없을 경우 추정 외형임을 표시.

## TEST-03 | S12A | 영원한 소망
위 STYLE-01 후보와 같은 프롬프트를 사용. 이 장면을 직접 스타일 후보로 선정할 수 있음. 마지막 하늘과 열린 길은 천국의 소망을 표현하는 상징이지 실제 사후 세계의 기록이 아니다.
모션: 아주 느린 전진, 구름의 미세한 움직임, 카메라가 열린 수평선에 머묾. 5초. 과도한 플레어/빛 폭발 없음.
합격: 자연스럽게 밝고 현대적, 정서적으로 평안함, 종교 장식 과잉 없음, S03의 절제된 빛과 연결 가능, 엔딩 자막 여백.

## 공통 영상 프롬프트
```
Subtle natural movement, slow stable cinematic camera motion, preserve the starting composition and all period details, preserve the modern cinematic semi-realistic 3D style, natural light, no morphing, no sudden cuts --motion low --raw --bs 1
```
승인 이미지에서만 영상화; 실제 역사사진 및 문서는 편집기로만 확대/이동.

## 검수 게이트
각 장면 1개 후보 선택, 실 생성 job ID·모델·참조·결과 파일·검수 기록을 TEST_RESULTS.csv에 기록한다. 먼저 이미지 3컷을 나란히 비교한 뒤 영상화. 현재 생성/비용 지출/최종 잠금/배포 모두 미실행. STYLE_URL, PHOTO_URL, CHAR_URL은 실제 승인 URL로 치환해야 한다.
