# AI_image_Tool

# AI 이미지 생성기

## 소개
텍스트 프롬프트를 입력하면 AI가 애니 스타일 이미지를 생성해주는 툴입니다.
Python 이미지 처리 기초를 공부하면서 만들었습니다.

## 사용 기술
- Python
- Diffusers (Stable Diffusion)
- Gradio
- Google Colab (GPU)

## 사용 모델
- Lykon/AnyLoRA - 애니 스타일에 특화된 SD 기반 모델

## 사용 방법
1. Google Colab에서 노트북 실행
2. 런타임 → GPU로 변경
3. 셀 순서대로 실행
4. Gradio 링크 클릭 후 프롬프트 입력

## 배우면서 느낀 것
- 프롬프트 키워드 하나로 결과가 완전히 달라진다는 것
- full body, 손발 같은 부분은 AI가 아직 어렵다는 한계
- negative prompt로 원하지 않는 요소를 제거할 수 있다는 것

## 한계 및 개선 방향
- float16 정밀도 문제로 단계를 높이면 검은 화면이 뜨는 현상
- 특정 캐릭터를 그리려면 LoRA 적용 필요
- 추후 ComfyUI로 노드 기반 워크플로우로 발전 예정
