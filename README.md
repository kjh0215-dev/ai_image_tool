#  AI_image_Tool
AI 이미지 생성 원리 탐구 프로젝트

## 소개
Stable Diffusion 기반 AI 이미지 생성이 어떻게 동작하는지 
이해하기 위해 직접 실험해본 레포입니다.
코드는 학습 목적으로 AI의 도움을 받아 구성했으며, 
직접 실행하고 결과를 관찰하면서 원리를 파악하는 데 집중했습니다.

## 사용 기술
- Python
- Diffusers (Stable Diffusion)
- Gradio
- Google Colab (GPU)

## 사용 모델
- Lykon/AnyLoRA — 애니 스타일에 특화된 SD 기반 모델

## 사용 방법
1. Google Colab에서 노트북 실행
2. 런타임 → GPU로 변경
3. 셀 순서대로 실행
4. Gradio 링크 클릭 후 프롬프트 입력

## 실험하면서 배운 것
- 프롬프트 키워드 하나로 결과가 완전히 달라진다는 것
- full body, 손발 같은 부분은 AI가 아직 어렵다는 한계
- negative prompt로 원하지 않는 요소를 제거할 수 있다는 것
- float16 정밀도 문제로 스텝 수를 높이면 검은 화면이 뜨는 현상

## 앞으로 (장기 프로젝트)
- 직접 그린 그림 50장으로 나만의 LoRA 학습시키기
- 내 그림체를 학습한 개인 모델 완성
- 기능 하나씩 추가하면서 AI 이미지 생성 원리 깊게 이해
- ComfyUI 노드 기반 워크플로우로 발전
