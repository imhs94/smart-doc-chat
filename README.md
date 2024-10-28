# 데이콘 재정정보 AI 검색 알고리즘 경진대회

PDF 문서에서 정확한 답변을 추출하는 강력한 질의응답 시스템. LangChain, Meta Llama, 그리고 최신 임베딩 모델을 결합하여 효율적인 문서 검색과 답변 생성을 제공.

## 주요 기능
- PDF 문서 처리 및 마크다운 변환
- Ensemble Retriever (BM25 + FAISS) 기반 정보 검색
- LLaMA 3.1 기반 자연스러운 답변 생성
- 청크 단위 문서 분할 및 벡터 임베딩

## 프로젝트 구조

- PDF 처리 파이프라인

  PDF → Markdown 변환
  헤더 기반 텍스트 분할
  청크 생성


- 검색 시스템

  BM25 검색기
  FAISS 벡터 검색
  Ensemble Retriever


- 질의응답 파이프라인

  프롬프트 템플릿 적용
  LLM 기반 답변 생성
