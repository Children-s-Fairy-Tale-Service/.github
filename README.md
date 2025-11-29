# 🌙 Children's Fairytale Illustration & Quiz Generation

이 프로젝트는 **동화 삽화 자동 생성 모델**과 **GPT API 기반 퀴즈 생성 기능**으로 구성되어 있습니다.  
이미지 생성에는 NVIDIA의 Consistory 기반 모델을 활용했으며,  
특히 **여러 장면에서도 동일한 캐릭터가 유지되는 Character Consistency 구조**를 사용하고 있습니다.

🔗 Consistory 모델:  
[https://github.com/NVlabs/consistory](https://github.com/NVlabs/consistory)

---

## 🎨 Fairytale Illustration Model

- SDXL 기반의 **동화 스타일 LoRA 모델**을 학습  
- Consistory의 캐릭터 일관성 구조 적용  
- 동일한 캐릭터가 여러 장면에서도 자연스럽게 유지됨  
- **현재 이 레포지토리에는 모델 파일은 포함되어 있지 않으며**,  
  **생성된 이미지 예시만 제공**합니다.

🔗 예시 이미지 폴더:  
[Children-s-Fairy-Tale-Service 이미지 모음](https://github.com/Children-s-Fairy-Tale-Service/frontend/tree/main/public/images)

---

🔗 My Fairytale LoRA:  
[https://huggingface.co/kimho9270/sdxl-korean-fairytale-lora](https://huggingface.co/kimho9270/sdxl-korean-fairytale-lora)

## 🧠 GPT API 기반 퀴즈 생성

동화 줄거리를 입력하면 GPT API가 자동으로:

- 줄거리 기반 **맞춤형 퀴즈 생성**
- 빈칸·서술형·선택형 등 다양한 포맷 지원  
- 필요하면 **정답 유사도 기반 평가 로직**도 구현 가능

---

## 🧩 현재 포함된 내용

- Consistory 기반 삽화 생성 **예시 이미지**
- GPT API 기반 퀴즈 생성 **코드 구조**
- 프론트/백엔드 시스템 구성 안내

> ⚠️ 모델(SDXL·Consistory·LoRA 가중치)은 용량 및 라이선스 문제로 포함되어 있지 않습니다.

---

## ✨ Goal

아이들이 읽는 동화를 기반으로  
**“한 이야기, 한 캐릭터, 일관된 그림”**을 만들고  
이를 활용해 **맞춤형 퀴즈를 생성하는 서비스**를 구현하는 것이 목표입니다.
