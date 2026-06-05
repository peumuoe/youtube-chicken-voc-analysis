# youtube-chicken-voc-analysis
YouTube 댓글 데이터를 활용한 치킨 프랜차이즈 신메뉴 VOC 분석 프로젝트
# YouTube Chicken VOC Analysis

YouTube 댓글 데이터를 활용해 BHC 스윗칠리킹과 BBQ 뿜치킹 신메뉴에 대한 소비자 반응을 분석한 프로젝트입니다.

## Project Overview

- YouTube Data API를 활용해 신메뉴 관련 댓글 데이터 수집
- Gemini API 기반 감성분석 수행
- 댓글을 긍정, 중립, 부정으로 분류
- 브랜드별 감성분포와 긍정/부정 요인 비교
- 신메뉴 마케팅 및 브랜드 개선 방향 도출

## Tools

- Python
- Google Colab
- YouTube Data API
- Gemini API
- Pandas
- Matplotlib
- Seaborn

## Files

- `BHC_youtube_comment_sentiment_analysis.ipynb`
- `BBQ_youtube_comment_sentiment_analysis.ipynb`

## Key Results

- BHC 댓글 총 3,080건 분석
  - 중립 1,471건
  - 긍정 1,397건
  - 부정 212건

- BBQ 댓글 총 2,872건 분석
  - 중립 1,758건
  - 긍정 759건
  - 부정 355건

## Insight

BHC는 협업과 바이럴 효과가 긍정 반응에 영향을 주었고, BBQ는 식감과 광고 친근감이 긍정 요인으로 나타났습니다. 반면 두 브랜드 모두 가격, 품질, 브랜드 신뢰도 이슈가 부정 반응과 연결되었습니다.
