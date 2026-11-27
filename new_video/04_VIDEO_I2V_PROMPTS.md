# 04. 이미지투비디오(I2V) 프롬프트 및 QC 가이드 (15숏)

> **기본 설정 (Midjourney Video 기준)**: Starting Frame만 지정, Ending Frame 비움, Loop OFF, `--motion low --raw --bs 1`, HD 720p 우선(최종 편집 시 1080p/24fps 정합). 타 툴(Runway, Kling, Veo 등) 사용 시 끝의 플래그만 제외하고 영어 본문을 그대로 입력합니다.

| 숏 | I2V 프롬프트 | QC 체크포인트 |
|---|---|---|
| S01 | `Slow gentle camera push-in toward the coastal village, subtle ripples shimmering on the calm sea, soft morning clouds drifting slowly, preserve exact starting composition and cinematic 3D style, no sudden cuts --motion low --raw --bs 1` | 건물·해안선 보존 |
| S02 | `Gentle slow camera pan right past the young man overlooking the sea, soft wind moving grass blades and his collar slightly, calm still posture, preserve exact facial profile and matte 3D style, no head turn, no morphing --motion low --raw --bs 1` | 옆모습·수평선 안정 |
| S03 | `Very slow subtle zoom-in toward the young man reading by the window, gentle dust motes drifting in the warm sunbeam, slight calm breathing only, keep hands and book completely steady, no lip movement, no page flipping --motion low --raw --bs 1` | 입·책장·손 고정 |
| S04 | `Very slow steady camera push-in inside the dim quiet room, subtle dust particles floating near the barred window, heavy wooden door and bars completely rigid and unchanged, solemn still atmosphere --motion low --raw --bs 1` | 문·창살 직선 유지 |
| S05 | `Slow gentle tilt-up along the warm shaft of sunlight streaming onto the wooden floor, golden dust motes drifting softly upward, calm luminous glow expanding gently, no morphing --motion low --raw --bs 1` | 빛줄기 자연스러움 |
| S06 | `Smooth slow forward tracking shot along the sunlit rural dirt road, gentle breeze swaying wild grass and wildflowers, soft clouds drifting in the bright blue sky, preserve road and hill geometry --motion low --raw --bs 1` | 길·산 능선 보존 |
| S07 | `Smooth steady rear tracking shot following the man walking calmly forward along the dirt road, natural subtle stride, soft breeze in the sunlit grass, preserve satchel and jacket shape, stable legs --motion low --raw --bs 1` | 다리·가방 안정성 |
| S08 | `Slow gentle camera push-in down the aisle toward the evangelist at the wooden lectern, subtle natural breathing and calm posture, congregation sitting quietly, soft daylight through windows, no exaggerated hand gestures, no lip movement --motion low --raw --bs 1` | 회중·강단 안정 |
| S09 | `Very slow lateral camera glide beside the sunlit wooden desk, gentle natural breathing as the middle-aged student focuses quietly on his open book, soft window light, keep hands pen and desk steady, no morphing --motion low --raw --bs 1` | 손·펜·책 변형 금지 |
| S10 | `Very slow gentle camera push-in toward the middle-aged man holding his diploma in warm afternoon sunlight, subtle natural blink and serene calm breathing, soft breeze in background foliage, preserve exact facial likeness, no talking --motion low --raw --bs 1` | 얼굴 일관성 유지 |
| S11 | `Gentle slow lateral parallax camera drift across the sunlit village courtyard, dappled leaf shadows swaying softly, calm natural breathing and respectful stillness among the three figures, no lip movement, no hand distortion --motion low --raw --bs 1` | 세 인물 얼굴·손 안정 |
| S12 | `Smooth steady lateral tracking shot following the cyclist gliding gently along the green rice field path, natural subtle forward motion, soft wind rippling rice stalks, keep bicycle frame and wheels clean and stable, wide calm rhythm --motion low --raw --bs 1` | 바퀴·프레임 안정 (불안정 시 팬/줌 대체) |
| S13 | `Slow gentle camera pull-back revealing the evangelist standing peacefully beside his parked bicycle overlooking the sunlit valley village, soft breeze moving tall grass and his jacket hem, serene still posture --motion low --raw --bs 1` | 자전거·인물 비율 고정 |
| S14 | `Very slow poetic camera pull-back from the parked black bicycle resting against the rural stone wall at golden sunset, warm light softly glowing, tall grass swaying gently in evening breeze, serene quiet stillness --motion low --raw --bs 1` | 바퀴·돌담 형태 유지 |
| S15 | `Slow graceful crane-up and forward glide over the sunlit green coastal hill toward the vast luminous sunrise sky and calm horizon, warm golden rays softly shimmering over the sea, peaceful expansive hope --motion low --raw --bs 1` | 수평선·빛 자연 확산 |

## 실패 시 대처 원칙
1. 동일 프롬프트 재생성은 최대 1회, 인물 동작이 과하면 동작 지시를 빼고 카메라 이동만 남깁니다.
2. S03·S10·S12 등에서 모핑이 반복되면 승인 정지 이미지의 103–108% 느린 켄 번즈 팬/줌으로 대체합니다.
