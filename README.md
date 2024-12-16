# 허깅페이스 파이프라인
1. 텍스트생성 
pipeline('text-generation', model='gpt2')
2. 감성분석
pipeline('sentiment-analysis')
3. 질문-답변
pipeline('question-answering')
4. 번역 실행
pipeline('translation_en_to_fr')
5. 요약
pipeline('summarization')

# 허깅페이스 챗봇
1. 허깅페이스모델 불러옴 : meta-llama/Llama-3.2-1B 
2. 챗봇 함수 작성 (입력토큰화, 모델이텍스트생성, 디코딩) 
3. 대화테스트
