# data_study
## 개요
- 데이터를 다루고 논문을 작성하는 법에 대한 스터디

## 목표 
- 싸지방에서 논문 하나 써서 연말까지 투고하는 걸 목표로 해보자!
- 국내 학술지 하나를 목표로 쓰면 실적을 꼭 낼 수 있을 것으로 생각함. 

## 공부할 내용
- 파이썬 웹 스크래핑: 유데미 강좌 (scrpay) 및 아마존에서 평점이 좋은 책 1권 같이 공부해보면 좋을 듯! 
- 논문 작성법: 정말 중요한 것인데 기본적인 논문작성의 와꾸라도 익혀두면 말그대로 평생 써먹는 것이기 때문에 처음부터 잘 배우는 것이 좋음
            개인적으로는 책 (예를 들어 http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791197020049&orderClick=LEa&Kc=)
            학교 도서관마다 운영하는 짦은 강좌
            테크니컬 라이팅 세션을 하나 잡아서 쭉 연습해보는 것이 도움이 많이 되었음. 
- 판다스: 판다스 역시 유데미 강의를 하나 구매하거나 책을 하나 정해서 죽어라 파면 도움이 많이 됨. 판다스는 데이터 클리닝 작업에 아주 핵심적인데 판다스와 같이 Python Data Cleaning Cookbook
         이라는 책도 추천함.  
- Latex: 온라인으로 수식을 편집할 수 있는 도구인데 레이텍을 처음부터 잘 쓸 수 있으면 업무 생산성에 엄청난 도움이 됨. 모르는 수식을 stackoverflow 같은 데 물어볼 수도 있고 투고 파일이 레이텍으로 작성되길 요구하기도 하기 때문임. 


## 주제 잡는 법

- 텍스트 마이닝을 문과적으로 해석하는 사회과학 논문들은 주로 인과성을 살펴보는 것을 목표로 함. A가 B에 미치는 영향 (i.e., A → B)을 해석학적으로 살펴본다는 것인데 사실상 논문화될 수 있는 주제는 정해져있음.
- Glaser의 6C 모형을 통해서 논문화될 수 있는 주제를 추려보면 A에 대한 원인을 찾거나, 결과를 파악하거나 원인의 공변인을 살펴보거나 원인이 A에 미치는 영향이 맥락에 따라서 어떻게 달라지는가 등을 살펴보는 것임.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d401b442-8046-4b72-b107-933f53ec8648/Untitled.png)

- 학술적으로 안 좋은 주제들의 예시

코로나로 인한 지역상권 변화를 찾아보자. (코로나 타격 → 지역상권 영향)

안 좋은 이유? 코로나가 끝나면 이 주제는 아무도 안 찾아보는 주제이기 때문임. 오히려 배달의 민족 실무가들이나 찾아볼 만한 주제가 됨. 논문 주제를 뽑는 요령 중에 하나는 남들이 오랫동안 우려먹을 수 있을 만한 떡밥을 잡는지 여부임.

차라리 해당 주제를 좀더 발전시키면, 동네효과처럼 도시공학자들이 관심이 많은 주제를 선택하는 게 유리함 (e.g., 코로나로 인해 범죄자들이 모여사는 동네가 사라지면, 동네의 치안이 높아지는 동네효과가 생기는가?)  

특정한 동네의 아파트 가격이 높아지면 학력수준이 상승하는가? 

사회과학의 특성 중 하나는 인과성을 아무리 지지고 볶고 해도 결국에는 그것을 믿는 사람들이 있는지 여부가 중요하다는 것임. 그런데 경제학자들의 상당수는 학력수준이 높아지면 그것에 대한 반응 (즉 탄력성)으로서 아파트 가격이 상승하고 그것을 통해서 교육재화에 대한 지불가격의사를 측정할 수가 있다고 믿음. 그래서 비슷해보여도 학력수준 상승 → 아파트 가격의 상승이라는 주제를 잡아야지 아파트 가격 상승 → 학력수준 상승이라는 주제를 잡게 되면 학술적인 가치가 거의 없어짐. (동일한 분석을 할 수 있음에도 불구하고) 

- 결국 어느 정도 해당 필드에 대한 지식 (예를 들어 위에처럼 지불가격 의사를 집값으로 뽑는다) 이 있어야, 어떤 주제가 학술적인 가치가 있는지 감이 옴
- 학술적으로 의미가 있으려면.. 그런 인과관계를 믿는 학자들의 대화 속으로 들어가야 함 (비록 그게 좀 현실적으로 말이 안 된다고 느껴지더라고)
- 논문에 대해서 가장 크게 욕할 수 있는 거는 ‘이 논문은 아무도 관심없는 주제다’, ‘노흥미!’라는 반응이지 방법론적인 엄격성은 부차적인 문제임

예를 들어 A라는 교수가 기업체의 화학물질 사용량에 대한 **정보공개**가 사용 **감축**으로 이어진다는 것을 박사논문으로 실었다고 해보자. 앞으로 이 교수는 정보공개 → 오염감축이라는 테마로 주구장창 논문을 쓸 것임…

예를 들어, 어떤 요인으로 인해 기업은 자발적인 환경정보공개를 하게 되는가? (원인), 정보공개의 어떤 유형이 실제 감축으로 이어지는가? (A의 차원을 쪼개보기), 정보공개가 감축노력과 실제감축 중에 어디에 영향을 미치는가? (결과를 쪼개보기), 어떤 맥락에서 정보공개의 효과가 사라질 것인가? (맥락), 정보공개가 규제정책과 결합되면 어떤 결과를 가져올 것인가? 등등, 


## 리뷰어는 어떻게 논문을 심사하는가?
논문 작성 초기 단계에서 실제 논문 심사를 하는 리뷰어들이 어떤 checklist를 가지고 방법론을 바라보는지 생각해보면 아주 유리함. 다음의 링크는 텍스트 데이터를 분석하는 데 있어서 발생할 수 있는 여러가지 맹점이나 방법론적인 허술함을 방지하기 위한 레퍼런스로 유용함. 리뷰어가 채점하는(?) 법

[https://www.routledge.com/The-Routledge-Reviewers-Guide-to-Mixed-Methods-Analysis/Onwuegbuzie-Johnson/p/book/9781138305274](https://www.routledge.com/The-Routledge-Reviewers-Guide-to-Mixed-Methods-Analysis/Onwuegbuzie-Johnson/p/book/9781138305274


## 참가자
- [doyoon](https://github.com/cosmos1030)
