# Direction Setting
Introduction of Agents를 읽는 것을 추천드리며, 실습을 통해 context/prompt engineering을 해보실 수 있습니다.

# 예시
추론형/비추론형 LLM 모델마다 다 prompt를 최적화하여 넣는 방식이 다릅니다. 예를 들어, 비추론형은 규칙을 정하는 프롬프트 부분을 앞단에 설정하는 게 유리하며, 추론형은 뒤에 설정하는 게 대체적으로 유리합니다. 기본 UI를 통해 LLM에게 input을 넣을 때에 비해, API 콜을 통해 LLM을 사용하면 User Message 외에도 System Message를 설정할 수 있어 일률적인 방향을 잡는 데에 유리합니다. Tool calling (Skills)을 통해 LLM 제어가 가능하고요. 또, Meta Prompt를 통해 Prompt를 평가하는 더 고차원의 Prompt를 생성할 수 있으며, 다양한 기법들이 존재합니다.
