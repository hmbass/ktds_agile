

# Product Backlog

### 개요

Product Backlog는 제품에 필요하다고 알려진 모든 요구사항에 대한 우선순위화 된 목록이며, 제품에 대한 모든 변경 요구사항을 포함하는 단 하나의 소스이다.

PO가 Product Backlog의 내용 및 우선순위화에 대한 책임을 갖고 있다.



![ProductBacklog](./img/06fig02_modified.png "Product Backlog")



Product Backlog는 요구사항에 대한 완성본이 아니고, 제품으로 진화하고, 그 제품이 사용될 환경과 함께 진화하면서 끊임없이 변화한다.

Product Backlog는 제품의 다음 배포에 추가로 포함될 모든 기능/비기능 요구사항, 개선사항 등을 나열한다.

Product Backlog 항목들은 각각에 대한 설명, 우선순위, 추정값 등이 포함되는데, 그것이 “완료”되었을 때 완료되었음을 증명해 줄 테스트(인수기준)에 대한 설명을 포함하고 있다.

여러 Scrum 팀들이 같은 제품을 만들기 위해 함께 일하고, 그 제품을 만들기 위해 해야 할 작업을 설명하는데 단 하나의 Product Backlog가 사용된다.

어떤 Product Backlog 특성이 항목들을 그룹화하는데 사용될 수 있다.

### Product Backlog Grooming

Product Backlog Grooming은 Product Backlog 항목들에 대한 상세한 내용, 작업의 크기, 그리고 우선순위를 추가하는 활동이다.

이는 PO와 개발팀이 Product Backlog 항목들을 상세화하기 위해 협력하는 지속적인 과정이다.



![ProductBacklogGrooming](./img/06fig06.png)



Product Backlog Grooming 중에, 각 항목을 검토하고 수정한다. Scrum 팀은 언제 어떻게 Product Backlog Grooming 작업을 완료할지 결정한다. 이 작업을 위해서 보통 개발팀 전체 가용 시간의 10% 미만을 사용한다. 하지만, Product Backlog 항목들은 PO의 재량에 따라 언제든지 업데이트 될 수 있다.

높은 순위의 Product Backlog 항목들이 일반적으로 낮은 순위의 항목들 보다 좀 더 명확하게 상세하다. Product Backlog 항목이 더 명확하고 상세할수록 더 정확한 개발 견적을 얻을 수 있고, 낮은 순위의 Product Backlog 일수록 상세화가 덜 되어 있다.

다음 Sprint를 위해 개발팀에 할당될 Product Backlog 항목들은 각 항목이 Sprint 기간 내에 합리적으로 “완료”될 수 있도록 다듬어진다. 한 Sprint 내에 개발팀에 의해 “완료”될 수 있는 Product Backlog 들은 Sprint Planning에서 선택할 수 있는 “준비”된 항목들로 여겨진다. Product Backlog 항목들은 일반적으로 위에 기술된 상세화 단계들을 통해 “준비”된 항목으로서의 투명성을 얻게 된다.

### 진행 상황 모니터링

전체 개발 목표에 도달하기 위해 남은 총 작업량은 언제든지 계산될 수 있다. PO는 적어도 Sprint Review 마다 남아 있는 총 작업량을 추적한다. PO는 목표로 한 날짜까지 작업을 완료하도록 진행 상황을 평가하기 위해 남아 있는 총 작업량을 이전 Sprint Review에서 남아 있던 작업량과 비교한다. 이러한 정보는 제품과 관련된 모든 이해관계자에게 투명하게 공개된다.

Burndown Chart나 Burnup Chart와 같은 다양한 트렌드 분석 예상 도구들이 진행 상황을 예측하기 위해 사용된다. 이러한 도구들이 유용하다고 알려져 있지만 경험주의 이론의 중요성을 대체하지는 못한다. 복잡한 환경에서는 무슨 일이 발생할지 알 수 없다. 단지 지금까지 이미 발생했던 일이 앞으로 의사 결정을 하는데 사용될 수 있다.

### Product Backlog 항목의 종류

Product Backlog에 들어갈 수 있는 항목은 다음과 같은 것들이 될 수 있다.

- Feature(기능): 새로운 기능, 기능 개선
- Defects(결함): 버그 등
- Technical Work(기술적 작업): 고객에게 직접적인 가치를 제공하지는 못하지만 필요한 기술적인 작업 (리팩토링 등)
- Knowledge Acquisition(지식 습득): 새로운 UI 프로토타이핑, 새로운 기술 실험 등

분류가 명확하지 않고 여러 분류에 걸치는 항목들이 존재할 수 있다. 항목들을 분류하여 관리할 필요는 없지만, 이런 분류에 속하는 것이라는 것을 인지할 필요는 있다.

### Product Backlog의 완료기준(DoD : Definition of Done) 정의

Product Backlog에는 완료기준을 정의하여 성공 기준을 명확히 해야 한다.

* 완료의 정의
  * 결과물이 잠재적으로 출시 가능하다고 공표하기 전에 팀이 성공적으로 완수해야 한다고 기대되는 일의 체크리스크
  * 제품 책임자(PO)와 개발팀이 모두 모여서 정의해야 하며, 서로 합의 해야 함
  * 제품 책임자는 인수 관점에서 완료를 중요시하고, 개발팀은 SW의 품질관점에서 완료를 중시하는 성향이 있음
  * 완료 기준 중에 하나라도 충족 시키지 못한다면, 스프린트를 완료한 것이 아니다. 미완성 항목으로 정의되며, 다음 스프린트 작업으로 할당
* Product Backlog에는 아이템 별로 인수 조건(Acceptance Criteria)이 작성되어야 하며, 이는 인수 테스트에서 인증된다.
  [작성 예]
  - Product Backlog 아이템 : "고객이 신용 카드 결제가 가능하다."
  - 인수조건(Acceptance Criteria) : "VISA, Master 카드와 국내 발행 모든 카드사의 신용/체크 카드로 결제가 가능 하다", "오류 발생 시 오류 원인과 어떻게 조치하면 될지 고객에게 알려 줄 수 있는 알림 메시지를 줘야 한다." 등

### PO를 위한 Product Backlog 관리팁

#### **1. Product Backlog가 관리 가능한 수준으로 유지되어야 한다.**

많은 PO가 저지르는 실수 중의 하나는, 철저하고 완벽하게 하려고 너무 많은 수의 Backlog를 도출하여 관리가 되지 않는 상태에 빠지는 것이다. 과다한 Backlog는 유지, 관리가 불가능하고, 투명해지지도 않으며, 아무도 제품의 방향을 알지 못하게 된다. 일반적으로 PO는 100~300개 정도의 Product Backlog를 관리하게 되는데, 그 이상의 Backlog는 하지 말아야 할 것을 결정하여 제거해야 한다. PO는 산출물을 최소화하고 성과를 극대화해야 한다.

#### **2. 단 하나의 Product Backlog만 유지한다.**

지금 당장은 아니지만 언젠가는 필요할 것 같은 이해관계자의 요구, 아이디어 같은 희망사항을 별도의 목록으로 관리하지 않는다. 과감하게 No라고 말하고 제거한다. 정말 가치 있는 것이라면 나중에 다시 나오게 된다.

#### **3. Product Backlog에 관한 모든 것을 직접 다 하려고 하지 않는다.**

PO가 Product Backlog에 대한 최종 책임을 가지는 것은 맞지만, Product Backlog에 관한 모든 것을 혼자 다 하려고 하지 않는다. 개발팀이 함께 참여하여 관리를 지원하도록 유도한다. 대신에 PO는 제품의 비전, 장기 로드맵, 이해관계자와 시장의 비즈니스 가치에 더 중점을 두어야 한다.

#### **4. 모든 Product Backlog 항목이 User Story일 필요는 없다.**

User Story는 Product Backlog 항목을 설명하는데 사용할 수 있는 템플릿의 한 종류이다. Product Backlog 항목의 대다수가 User Story로 작성될 수 있지만, 특정한 종류의 기술 작업, 버그, 기술 부채 같은 것들은 User Story 형식으로 설명할 가치가 거의 없을 수 있다.

#### **5. Product Backlog에 무엇이 있는지 알고 있어야 한다.**

모든 사람이 Product Backlog에 항목을 추가할 수 있도록 하지 않는다. 이럴 경우, 관리하기 어려운 희망사항 목록이 생기고, 투명성과 명확성이 떨어지며, 우선순위가 잘못되어 관리의 효율성이 떨어지게 된다. PO는 Product Backlog에 있는 모든 항목에 대해 알고 있어야 한다.

#### **6. 지속적으로 Product Backlog를 정제한다.**

Product Backlog는 프로젝트 전체 기간 동안 유지되어 살아있는 산출물이다. 시간이 지남에 따라 지속적으로 정제하여 Product Backlog가 최신 상태를 유지하도록 해야 한다. 모든 팀원과 이해관계자에게 최신의 Product Backlog를 투명하게 공개하고, 개발팀은 이를 바탕으로 이번 Sprint의 실행 가능한 계획을 세울 수 있다.

#### **7. Product Backlog는 완성될 수 없다.**

많은 PO가 프로젝트를 처음 시작할 때 빠질 수 있는 함정은, 처음부터 완전한 Product Backlog를 만들려고 한다는 것이다. 제품이 수명을 유지하는 한 요구사항은 시간이 지남에 따라 계속 증가하고 줄어들 것이다. 처음부터 완전한 Product Backlog를 만들려고 하지 말고, 제품에 대한 가장 가치있는 아이디어부터 시작하여 Product Backlog를 작성해 나간다.

#### **8. What과 Why에 중점을 둔다.**

PO가 빠질 수 있는 또 다른 함정은, PO가 제품의 솔루션을 찾고 설명하는데 너무 많이 집중하고 있다는 것이다. 많은 비즈니스 분석, 기술 분석을 수행하고 개발팀을 위한 기능적 설계 및 설명을 작성하는 PO들이 있다. 근본적으로 틀린 것은 아니지만, 한 사람보다는 개발팀 9명의 창의력과 문제 해결 능력이 더 높다. 따라서, PO가 제품의 솔루션에 관심을 가지고 기능을 디자인 하려고 해서는 안된다. PO는 해결하고자 하는 문제와 파악하려는 기회에 관심을 가지고 What과 Why에 중점을 두어야 한다. PO는 How에 대해 너무 걱정하지 말고 개발팀의 창의력과 문제 해결 능력을 이용해 솔루션을 설계한다.

#### **9. Product Backlog를 벽에 붙인다.**

Product Backlog는 팀 및 이해관계자에게 투명하게 공유되어야 한다. 투명성을 높이기 위한 방법은 여러가지가 있지만, 가장 강력한 방법 중 하나는 고개만 돌리면 볼 수 있거나 옆을 지나가다가 볼 수 있도록 벽에 붙여 공유하는 것이다.

#### **10. 고객 또는 비즈니스 가치 이상의 것이 있다.**

물론, 고객, 사용자, 조직에 최대한 많은 가치를 제공해야 하지만, 모든 비용을 투입해서라도 가치를 제공해야 할까? 많은 PO가 더 많은 기능을 제공하는데 전념하고 있지만, 그 보다는 투입되는 비용 대비 고객과 사용자의 가치를 극대화 하여 제품을 성공시키도록 해야 한다. 그러기 위해서는 버그 해결, 기술 부채, 제품 아키텍쳐 개선, 성능, 보안 등도 고려해야 한다. 또한, 테스트 자동화, 빌드 및 배포 프로세스 개선에 시간을 투자하면 더 짧은 시간에 더 높은 품질로 더 많은 가치를 제공할 수 있다.

### Reference

- **[사용자 스토리(User Stroy)](./user-story.md)**
- **[Product Backlog Template](http://moudemo.mousoft.co.kr/confluence/display/AW/Product+Backlog+Template)** ==> 템플릿 링크 필요

