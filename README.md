# 수학 학습자 유형 분석 Streamlit 앱

## 실행 방법

```bash
pip install -r requirements.txt
streamlit run app.py
```

## 사용 방법

1. Google Forms 응답을 Google Sheets에서 `.xlsx` 또는 `.csv`로 다운로드합니다.
2. 웹앱 왼쪽 사이드바에서 파일을 업로드합니다.
3. 군집화에 사용할 변수를 선택합니다.
4. K 값을 조정하면서 Elbow, Silhouette, PCA 산점도, 군집별 프로파일을 확인합니다.
5. 학생별 군집 결과 CSV를 다운로드합니다.

## 기본 분석 변수

- 수학불안 평균
- 수학 자기효능감 평균
- 수학 흥미 평균
- 학습태도 평균

T6 문항인 “수학을 포기하고 싶다고 느낄 때가 있다.”는 학습태도 계산 시 자동 역채점됩니다.
