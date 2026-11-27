# Midjourney 제작 가이드 V2.0

## 모델
V7 Omni Reference + Style Reference 조합을 초기 후보로 사용. V8.x Edit Model은 여러 참조를 활용할 대안이며, 동일한 3개 테스트 컷으로 비교 후 하나를 잠근다. V7을 최신 모델이라고 주장하지 않는다. 공식 가이드:
- https://docs.midjourney.com/hc/en-us/articles/36285124473997-Omni-Reference
- https://docs.midjourney.com/hc/en-us/articles/32180011136653-Style-Reference
- https://docs.midjourney.com/hc/en-us/articles/48495453462797-Edit-Model
- https://docs.midjourney.com/hc/en-us/articles/37460773864589-Video
- https://docs.midjourney.com/hc/en-us/articles/32859204029709-Parameter-List

## 스타일 테스트
동일 사진과 구도로 A/B/C를 비교. 공통: realistic human proportions, understated expressions, clean modern composition, period-accurate Korean clothing and architecture, no text. A 스타일 프롬프트:
```
Contemporary cinematic semi-realistic 3D animated short film, tactile matte materials, nuanced human expression, believable anatomy, soft natural daylight, clear sky blue and fresh muted greens, warm ivory highlights, refined cinematic composition, gentle depth of field, historically accurate mid-century rural Korea, sincere and hopeful, sophisticated adult audience, no vintage filter, no sepia, no distressed paper
--v 7 --ar 16:9 --raw --s 100 --chaos 0
```
CHAR-03: 실제 승인 사진을 참조하고 동일한 얼굴 형태와 나이, 헤어스타일을 유지. V7은 한 개 Omni Reference만 가능. CHAR_URL, STYLE_URL은 실제 승인 URL로 교체 후 실행. 숫자는 테스트 초기값이며 고정 보장은 없다.
```
A respectful semi-realistic 3D character portrait based on the supplied historical photograph, Korean Christian evangelist in his forties in the 1950s, preserve facial structure, hairstyle and realistic proportions, period-appropriate modest dark suit, neutral warm expression, plain ivory background, soft daylight
--v 7 --ar 2:3 --oref CHAR_URL --ow 200 --sref STYLE_URL --sw 150 --raw --s 100 --chaos 0
```

## 장면별 프롬프트 본문
공통 STYLE-01 문구와 선택된 모델 설정을 결합한다. V7 인물 컷에만 --oref CHAR_URL --ow 200 적용. --sref STYLE_URL --sw 150은 승인된 스타일 생성 후에만 적용. 모든 컷 --ar 16:9. 실제 사진을 표시할 컷은 생성하지 않는다.

| 컷 | prompt body |
|---|---|
| S01A | Early twentieth century Korean coastal village inspired by Tongyeong, calm sea, green wooded hills, modest period houses, clear dawn light, expansive establishing shot. |
| S02A | Young Korean man studying scripture in a simple traditional room, late 1930s, side silhouette, subtle daylight, contemplative rather than posed. |
| S03A | A closed wooden door and simple barred window in a quiet dim interior, slate blue shadows, restrained solemn mood, symbolic not a specific prison. |
| S03B | A narrow shaft of natural daylight across a dark floor, quiet dignity, restrained contrast, no person, no prison identification. |
| S04A | Open rural Korean dirt road after liberation, expansive brightening sky, soft morning light, quiet hopeful landscape. |
| S04B | Korean evangelist walking away along a period rural dirt road, relaxed posture, sunlit hills, medium wide rear view. |
| S05B | Small rural Christian gathering in a modest late 1940s Korean meeting room, evangelist sharing scripture, natural expressions, historical space only if confirmed. |
| S06A | Middle aged Korean seminary student opening a book at a simple 1950s wooden desk, soft daylight, focused expression. |
| S08B | Korean evangelist at eye level with ordinary adult community residents, dignified conversation, late 1950s rural Korea, bright natural light, no exaggerated illness. |
| S09A | Middle aged Korean evangelist riding a period black roadster bicycle beside rice fields, side profile, fresh green landscape and blue sky, realistic hands and bicycle geometry. |
| S09B | Same man and bicycle, standing beside the road looking toward a modest rural village, natural posture and sunlit hills. |
| S12A | Open sky over a gentle green meadow and luminous horizon, warm sunrise, serene Christian hope expressed symbolically, no angels, no golden gates, no person. |

## 영상화
승인된 이미지의 시작 프레임만 사용. 5초 클립 기본 계획, 길이는 실제 생성 결과 검증 후 편집.
```
Subtle natural motion, gentle camera push-in, preserve the exact starting composition, facial features, period details and modern cinematic 3D style, stable anatomy, no morphing, no lip movement, no sudden cuts --motion low --raw --bs 1
```
S09 자전거는 측면 이동으로 테스트하되 바퀴/손/페달이 깨지면 정지 키프레임 팬·줌으로 대체. 영상 생성에는 이미지 전용 --oref/--sref를 넣지 않는다. 실제 사료는 편집기에서만 팬/줌.

## 실행 및 기록
승인된 마스터와 세 대표 테스트 컷부터 제작. job ID, model, prompt, reference ID/URL(공개 승인된 것만), seed(제공 시), 출력 해상도, 리뷰, 버전 기록. 생성 비용 또는 자동 실행은 승인된 범위에서만 진행. 현재 생성 0건.
