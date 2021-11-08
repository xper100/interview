# Interview


## 통계 및 수학

- 고유값(eigen value)와 고유벡터(eigen vector)에 대해 설명해주세요. 그리고 왜 중요할까요?

>

- 샘플링(Sampling)과 리샘플링(Resampling)에 대해 설명해주세요. 리샘플링은 무슨 장점이 있을까요?

> 샘플링은 모집단에서 부분집합을 추출하는 행위를 말하며, 리샘플링은 부분집합으로 모집단을 추론하는 행위이다. 완전조사없이 모집단의 일부만을 사용하여 모수를 추론할 수 있는 경제성이 강점이다.

- 확률 모형과 확률 변수는 무엇일까요?

> 

- 누적 분포 함수와 확률 밀도 함수는 무엇일까요? 수식과 함께 표현해주세요

- 베르누이 분포 / 이항 분포 / 카테고리 분포 / 다항 분포 / 가우시안 정규 분포 / t 분포 / 카이제곱 분포 / F 분포 / 베타 분포 / 감마 분포 / 디리클레 분포에 대해 설명해주세요. 혹시 연관된 분포가 있다면 연관 관계를 설명해주세요

- 조건부 확률은 무엇일까요?

- 공분산과 상관계수는 무엇일까요? 수식과 함께 표현해주세요

- 신뢰 구간의 정의는 무엇인가요?

- p-value를 고객에게는 뭐라고 설명하는게 이해하기 편할까요?

- p-value는 요즘 시대에도 여전히 유효할까요? 언제 p-value가 실제를 호도하는 경향이 있을까요?

- A/B Test 등 현상 분석 및 실험 설계 상 통계적으로 유의미함의 여부를 결정하기 위한 방법에는 어떤 것이 있을까요?

- R square의 의미는 무엇인가요?

- 평균(mean)과 중앙값(median)중에 어떤 케이스에서 뭐를 써야할까요?

- 중심극한정리는 왜 유용한걸까요?

- 엔트로피(entropy)에 대해 설명해주세요. 가능하면 Information Gain도요.

- 요즘같은 빅데이터(?)시대에는 정규성 테스트가 의미 없다는 주장이 있습니다. 맞을까요?

- 어떨 때 모수적 방법론을 쓸 수 있고, 어떨 때 비모수적 방법론을 쓸 수 있나요?

- “likelihood”와 “probability”의 차이는 무엇일까요?

- 통계에서 사용되는 bootstrap의 의미는 무엇인가요.

- 모수가 매우 적은 (수십개 이하) 케이스의 경우 어떤 방식으로 예측 모델을 수립할 수 있을까요?

- 베이지안과 프리퀀티스트간의 입장차이를 설명해주실 수 있나요?

- 검정력(statistical power)은 무엇일까요?

- missing value가 있을 경우 채워야 할까요? 그 이유는 무엇인가요?

- 아웃라이어의 판단하는 기준은 무엇인가요?

- 콜센터 통화 지속 시간에 대한 데이터가 존재합니다. 이 데이터를 코드화하고 분석하는 방법에 대한 계획을 세워주세요. 이 기간의 분포가 어떻게 보일지에 대한 시나리오를 설명해주세요

- 출장을 위해 비행기를 타려고 합니다. 당신은 우산을 가져가야 하는지 알고 싶어 출장지에 사는 친구 3명에게 무작위로 전화를 하고 비가 오는 경우를 독립적으로 질문해주세요. 각 친구는 2/3로 진실을 말하고 1/3으로 거짓을 말합니다. 3명의 친구가 모두 “그렇습니다. 비가 내리고 있습니다”라고 말했습니다. 실제로 비가 내릴 확률은 얼마입니까?

- 필요한 표본의 크기를 어떻게 계산합니까?

- Bias를 통제하는 방법은 무엇입니까?

- 로그 함수는 어떤 경우 유용합니까? 사례를 들어 설명해주세요



## 분석일반

- 좋은 feature란 무엇인가요. 이 feature의 성능을 판단하기 위한 방법에는 어떤 것이 있나요?

> 데이터셋에 여러번 등장하며 분명하고 명확한 의미를 담고있는 feature ex) 나이: 27 vs 나이: 2571

참고: *https://developers.google.com/machine-learning/crash-course/representation/qualities-of-good-features?hl=ko*

- "상관관계는 인과관계를 의미하지 않는다"라는 말이 있습니다. 설명해주실 수 있나요?

> 인과관계는 "A이기 때문에 B이다."와 원인과 결과의 관계이지만 상관관계는 A <-> B사이의 변화가 서로 공존하는것을 뜻함 즉, 두 변수 간에 일정한 관계가 있는 것을 뜻함



- A/B 테스트의 장점과 단점, 그리고 단점의 경우 이를 해결하기 위한 방안에는 어떤 것이 있나요?

> 장점: 어떤 현상을 통계적으로 효과를 판단할 수 있는 근거를 제공

> 단점: 결과와 요인사이의 인과관계를 정확히 알 수 없음 (특정 디자인의 변화가 사용자의 반응을 일으켰다고 단정할 수 없음. 그저 그런 현상을 확인)


- 각 고객의 웹 행동에 대하여 실시간으로 상호작용이 가능하다고 할 때에, 이에 적용 가능한 고객 행동 및 모델에 관한 이론을 알아봅시다.

> 

- 고객이 원하는 예측모형을 두가지 종류로 만들었다. 하나는 예측력이 뛰어나지만 왜 그렇게 예측했는지를 설명하기 어려운 random forest 모형이고, 또다른 하나는 예측력은 다소 떨어지나 명확하게 왜 그런지를 설명할 수 있는 sequential bayesian 모형입니다.고객에게 어떤 모형을 추천하겠습니까?

> 고객의 성향에 따라 다르다. 예측이 중요한 고객에게는 랜덤포레스트, 신용등급 및 결과가 미치는 영향이 큰 산업에는 설명력이 강한 모델을 추천


- 고객이 내일 어떤 상품을 구매할지 예측하는 모형을 만들어야 한다면 어떤 기법(예: SVM, Random Forest, logistic regression 등)을 사용할 것인지 정하고 이를 통계와 기계학습 지식이 전무한 실무자에게 설명해봅시다.

>

- 나만의 feature selection 방식을 설명해봅시다.

>


- 데이터 간의 유사도를 계산할 때, feature의 수가 많다면(예: 100개 이상), 이러한 high-dimensional clustering을 어떻게 풀어야할까요?

> 대표적으로 PCA를 이용하여 차원을 축소시켜 진행할 것입니다. 









