# Microsoft 365 Copilot 황금 프롬프트 작성 가이드라인[한국어]

본 Microsoft 365 Copilot 황금 프롬프트 작성 퀵 가이드라인은 Microsoft 365 Copilot을 최대한 활용할 수 있도록 도움을 드리기 위해 마련되었습니다. 
프롬프트를 효과적으로 작성하고 활용하는 방법을 이해하여 생성형 AI의 사용성을 극대화할 수 있습니다. 이 문서를 통해 Copilot을 더 잘 활용할 수 있는 노하우를 익혀 보시기 바랍니다.

---

## 1. 프롬프트 사용 설명서 - 핵심 개념

프롬프트란, 사용자가 AI 모델에 입력하는 **질문이나 명령**을 의미합니다. Copilot과 같은 대형 언어 모델(LLM)은 사용자의 요청에 따라 정보를 제공하거나 작업을 수행합니다. 
**명확하고 구체적인 프롬프트**를 작성하면 더 나은 결과를 얻을 수 있습니다.

### 핵심 팁
- **충분한 시행착오를 거치기**: 최적의 프롬프트를 작성하기 위해서는 여러 번의 시도가 필요합니다. 다양한 환경에서 작동하는 프롬프트를 만들기 위해서는, 시간을 투자하여 나만의 황금 프롬프트를 만들어 보길 바랍니다.
- **동일한 프롬프트라도 매번 결과가 다름을 이해하기**: 생성형 인공지능의 특성상 같은 프롬프트를 입력하더라도 매번 다른 답변이 나올 수 있습니다.
- **진화하는 모델 이해하기**: 스마트폰 운영체제가 업데이트되듯, LLM의 버전도 주기적으로 업데이트됩니다. 이에 따라 성능이 개선되거나 변할 수 있다는 점을 기억하세요. 만약 사용 중인 LLM의 모델이 업데이트된다면, 반드시 예의주시하시기를 바랍니다.
- **명확하고 논리적으로 프롬프트 작성하기**: 직장 상사에게 보고서를 제출하듯, Copilot이 쉽게 이해할 수 있도록 논리적이고 명확하게 프롬프트를 작성해야 합니다. 억지로 프롬프트의 길이를 늘일 필요는 없습니다.
- **LLM의 능력을 이해하기**: Copilot이 잘 수행할 수 있는 작업을 파악하고, 그것에 맞게 프롬프트를 설계하시기 바랍니다. 또한, 기능을 이해할 수 있는 짧은 프롬프트 작성을 시작으로, 프롬프트의 길이를 늘여가며 나만의 프롬프트를 만드시길 바랍니다.
- **유용한 프롬프트는 공유하기**: 실제 업무에서 유용했던 프롬프트는 동료들과 함께 공유해 보세요. 좋은 프롬프트는 각자가 자주 사용하는 프롬프트입니다.

---

## 2. 나만의 황금 프롬프트 만들기

LLM이 사용자의 요구를 정확히 이해하고 올바른 결과를 제공하도록 하려면, 체계적으로 구성된 프롬프트를 작성하는 것이 중요합니다. 
아래의 **골든 프롬프트 구성 요소**를 참고하여 나만의 최적화된 프롬프트를 만들어 보길 바랍니다.

### 황금 프롬프트 구성 요소
프롬프트를 작성할 때 다음의 요소들을 포함하길 추천합니다. :

1. **역할(Role)**: Copilot이 수행할 역할을 명확하게 설정합니다.
2. **목적(Objective)**: 프롬프트의 주요 목표를 명확히 정의합니다.
3. **요청 사항(Request)**: 참고 자료 및 필요한 세부 정보를 명시합니다.
4. **가이드라인(Guidelines)**: Copilot이 따라야 할 작성 지침을 제공합니다.
5. **예외 및 제한(Exceptions & Limitations)**: 처리해야 할 예외 상황 및 제한 조건을 설명합니다.
6. **출력 형식(Output Format)**: 원하는 출력 형식을 예시로 제시합니다.

---

### 프롬프트 작성 예시
아래는 위의 구성 요소를 활용한 프롬프트 예시입니다.

```plaintext
[1. 역할] 저는 차세대 의약품 개발 프로젝트 매니저입니다.  
[2. 목적] 프로젝트 목표는 사내 약품 개발팀을 위한 의약품 개발 동향 보고서 작성입니다.  
[3. 요청 사항] /ABC.pdf 문서를 참조하여 내용 요약 후, 사내 의사들을 위한 인사이트를 제안해 주세요.  
[4. 가이드라인] 작성 시 다음을 포함해 주세요:  
  - 최근 동향  
  - 신규 개발 방법 소개  
  - 특장점  
  - 한계  
  - 우리 회사가 고려할 점  
  - 마무리  
[5. 예외 및 제한] 단, 주어진 자료에서 관련 정보를 찾을 수 없다면 "해당 정보는 제공된 자료에서 찾을 수 없습니다"라고 명시해 주세요.  
[6. 출력 형식] 추가적인 자료가 필요하면 요청하세요. 출력 예시는 다음과 같습니다:  

---
**의약품 개발 동향 보고서**  
- **최근 동향**: 글로벌 의약품 시장에서의 새로운 개발 사례를 요약했습니다.  
- **신규 개발 방법**: 새로운 AI 기반 분석 도구 도입 방법 및 활용 사례.  
- **특장점 및 한계**: 최신 기술의 장점과 단점 분석.  
- **우리 회사의 고려 사항**: 도입 시 예상되는 리스크와 해결 방안 제시.  
---
```

## 3. 프롬프트 작성 시 유의 사항

- **명확성**: Copilot이 질문의 맥락을 쉽게 이해할 수 있도록 구체적이고 명확한 지시어를 사용하시기 바랍니다.
- **컨텍스트 제공**: 배경 정보를 충분히 제공하여 Copilot이 상황을 명확하게 파악하도록 돕습니다.
- **구조화된 출력 요청**: 원하는 출력 형식을 미리 정의하면 더 정확한 답변을 얻을 수 있습니다.
- **테스트 및 조정**: 프롬프트를 여러 번 테스트하여 최적화해야 합니다. 필요에 따라 추가 지침을 더하거나 수정하시길 바랍니다.

---

## 4. 결론

Microsoft 365 Copilot을 효과적으로 활용하기 위해서는 **프롬프트 작성의 기술**을 익히는 것이 중요합니다. 이 가이드라인을 통해 Copilot과 협업하여 더 나은 업무 결과를 도출하는 데 도움이 되길 바랍니다.

프롬프트 작성 능력은 연습을 통해 발전합니다. 꾸준히 시도해 보고, 동료들과 공유하며 개선해 나가세요. **지속적인 학습과 개선**을 통해, Copilot을 업무에서 더 강력한 도구로 활용할 수 있을 것입니다.

---

더 나은 프롬프트 꿀팁이 있다면, 저와 함께 공유해주시길 바랍니다.
E-mail : August.Lee@microsoft.com