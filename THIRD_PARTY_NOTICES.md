# 서드파티 고지 (Third-Party Notices)

이 프로그램(NINEBIX 오디오 드라마 스튜디오)은 아래 구성요소를 동봉하거나 사용합니다. 각 구성요소는 자체 라이선스를 따릅니다.

| 구성요소 | 용도 | 라이선스 | 출처 |
|---|---|---|---|
| FFmpeg (gyan.dev full build) | 오디오 후처리·영상 렌더 | **GPL v3** — 소스 코드는 아래 링크에서 제공됩니다 | https://www.gyan.dev/ffmpeg/builds/ · https://ffmpeg.org |
| Supertonic 3 (모델 가중치) | 한국어 음성 합성 | **BigScience OpenRAIL-M** — 사용 제한 조항(불법·유해 용도 금지 등)이 있으며 재배포 시 라이선스를 함께 제공합니다 (`resources/runtime/supertonic3/LICENSE`) | https://huggingface.co/Supertone/supertonic-3 |
| supertonic (Python 패키지) | TTS 런타임 | MIT | https://github.com/supertone-inc/supertonic |
| Python 3.11 (embeddable) + numpy, onnxruntime, soundfile, huggingface_hub 등 | TTS 런타임 | PSF / BSD / MIT / Apache-2.0 (각 패키지 `dist-info` 참조) | https://www.python.org |
| Electron | 데스크톱 셸 | MIT | https://www.electronjs.org |
| Node.js (동봉 node.exe) | 서버 런타임 | MIT | https://nodejs.org |
| cloakbrowser + Chromium | 웹 자동화 브라우저 | MIT / BSD-3-Clause | https://github.com/CloakHQ/cloakbrowser · https://www.chromium.org |
| playwright-core, express, better-sqlite3, zod, dotenv | 서버 | Apache-2.0 / MIT | 각 패키지 `package.json` |
| Black Han Sans | 썸네일 제목 서체 | SIL Open Font License 1.1 (`assets/fonts/OFL-BlackHanSans.txt`) | https://github.com/zesstype/Black-Han-Sans |
| Qwen3-TTS (모델 `Qwen/Qwen3-TTS-12Hz-1.7B-VoiceDesign`, `Qwen/Qwen3-TTS-12Hz-0.6B-Base` + `qwen-tts` 패키지) | 선택 음성 엔진 — **동봉되지 않음**, 설정에서 켤 때 Hugging Face/PyPI 에서 다운로드 | Apache-2.0 | https://github.com/QwenLM/Qwen3-TTS |
| PyTorch / torchaudio | Qwen3-TTS 런타임 — 동봉되지 않음, 선택 설치 시 다운로드 | BSD-3-Clause | https://pytorch.org |
| Microsoft Visual C++ 재배포 DLL | Python 확장 로드 | Microsoft 재배포 허용 런타임 | https://learn.microsoft.com/cpp/windows/latest-supported-vc-redist |

## 상표·비제휴 고지

- ChatGPT, OpenAI 는 OpenAI 의 상표이며, Gemini, Google 은 Google LLC 의 상표입니다. 이 프로그램은 두 회사와 **제휴·후원·승인 관계가 없습니다**.
- 이 프로그램은 사용자가 직접 로그인한 본인 계정의 웹 화면을 브라우저 자동화로 조작합니다. 해당 서비스의 이용약관은 자동화된 접근을 제한할 수 있으며, 계정 제한 등 불이익이 발생할 수 있습니다. 사용 여부와 그 결과에 대한 책임은 사용자에게 있습니다. Gemini 는 공식 API 키 방식을 선택할 수 있습니다.
