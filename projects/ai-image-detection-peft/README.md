# AI 생성 이미지 탐지를 위한 PEFT 비교 연구: LN-tuning vs. LoRA

**분야:** 컴퓨터 비전 · Parameter-Efficient Fine-Tuning (PEFT)
**유형:** 교과 프로젝트 — 컴퓨터비전 (3학년)
**상태:** 완료

> ⬅️ [포트폴리오 홈으로](../../README.md)

---

## 개요
**AI 생성 이미지 탐지** 태스크에서 **파라미터 효율적 미세조정(PEFT)** 방법 — 구체적으로 **LN-tuning vs. LoRA** — 를 비교한 연구입니다.

## 문제 정의
AI 생성 이미지를 탐지하기 위해 대형 비전 모델을 전체 미세조정(full fine-tuning)하는 것은 비용이 큽니다. PEFT는 훨씬 적은 학습 파라미터로 유사한 성능을 기대할 수 있지만, 이 태스크에서 방법 간 트레이드오프는 명확하지 않습니다. *[Add 구체적 문제 정의]*

## 방법
- 사전학습된 비전 백본을 실제/AI 생성 이진 분류로 미세조정
- **LN-tuning**(정규화 계층 파라미터 튜닝)과 **LoRA**(저랭크 어댑터) 비교
- *[Add 백본 아키텍처, PEFT 설정 — rank, 대상 계층, 학습 파라미터 수]*

## 데이터셋
- *[Add 데이터셋 이름 / 출처 — 실제 vs. AI 생성 이미지]*
- *[Add 데이터셋 설명 — 규모, 포함된 생성 모델, 분할]*
- *[Add 전처리 / 증강]*

## 실험
- LN-tuning vs. LoRA 비교 (및 *[Add: full fine-tuning / 기타 베이스라인]*)
- *[Add 평가 지표 — accuracy / F1 / AUC]*
- *[Add 효율성 비교 — 학습 파라미터 수, 학습 시간]*

## 결과
- *[Add result — LN-tuning vs. LoRA 정확도 비교]*
- *[Add result — 효율성 비교]*
- *[Add figure]*

## 나의 기여
- *[Add 본인의 구체적 역할]*
- *[Add 공동 연구자(있는 경우)]*

## 기술 스택
- Python, PyTorch *[확인]*
- Hugging Face `transformers` / `peft` *[확인]*

## 파일
- *[Add 코드 / 노트북 링크]*
- *[Add 보고서 / 슬라이드 링크]*
- *[Add 그림 — ../../assets/figures/ 에 배치]*

## 비고
- *[Add 한계 및 향후 방향]*
