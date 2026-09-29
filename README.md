
뇌과학실험2 보고서 "입력과 판정 방식 변경을 통한 큐레이팅 모델의 개선"에서 만든 두 모델 (sklearn 1.9.0)과 결과입니다.

즉시 실행 가능한 형태로 만드는 것은 추후 시도해보겠습니다.

`/results`는 보고서의 그림과 표에 사용한 값 폴더입니다. `predictions.csv`는 클러스터마다 정답 라벨과 교차검증 판정 파일이고, `hgb|ur+spike` 열이 정밀 모델입니다. `comparisons.csv`는 모델 간 balanced accuracy 차이와 95% 신뢰구간, `weights.csv`는 가중 평균 모델의 세션별 가중치, `metric_correlation.csv`는 IBL 데이터에서 구한 값과 공개된 값의 상관계수, `timing.csv`는 판정 시간입니다.

Steinmetz 데이터의 라이선스(CC BY-NC 4.0)에 따라 이 저장소의 파일도 비상업적 용도로만 사용할 수 있습니다.
