# Seaborn_Study
Matplotlib을 기반으로 하는 Python 데이터 시각화 라이브러리

1. 기본 기능
- 산점도 그래프 - relplot
  1) hue - 그려진 그래프 내에서 서로 다른 색으로 마커 표현
  2) style - 그려진 그래프 내에서 서로 다른 기호로 마커 표현 (hue 함께 사용 가능)
  3) palette - 마커 색상 변경
  4) size - 마커 크기 변경 (size와 hue 함께 사용 불가)
  5) relplot( ).set(xlabel = ' ' , ylabel = ' ' ) - X축/Y축 이름 변경
- 선 그래프 - sns.relplot(kind = 'line')
  1) ci = None - 범위값 제거 (defult값 : 표준편차)
  2) ci = 'sd' - 분산값 범위 표현
  
Searborn 홈페이지
- https://seaborn.pydata.org/