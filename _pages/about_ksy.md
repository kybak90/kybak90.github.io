
<style>
  /* 부모 <ul>에 flexbox 적용 */
  ul {
    display: flex;
    list-style-type: none; /* 기본 점 제거 */
    padding: 0; /* 기본 여백 제거 */
    margin: 0;
    gap: 20px; /* 항목 사이 간격 */
  }

  li {
    flex: 1; /* 각 li 요소를 동일 비율로 확장 */
    max-width: 300px; /* li 요소의 최대 너비 고정 */
    word-wrap: break-word; /* 긴 단어 줄바꿈 */
    overflow-wrap: break-word; /* 추가적인 줄바꿈 지원 */
  }

  li:first-child {
    flex: 1; /* Research Interests는 기본 크기 */
    max-width: 200px; /* 최대 너비 제한 */
  }

  li:last-child {
    flex: 2; /* Publications 칸을 더 크게 */
    max-width: 700px; /* 최대 너비 제한 */
  }

  .spn5 {
    display: block; /* 텍스트를 한 줄로 */
    margin-bottom: 10px;
    color: hsl(266, 91%, 37%);
    font-size: 1rem;
  }

  .my-enumerate {
    margin: 0; /* 기본 여백 제거 */
    padding: 5px 0; /* 약간의 패딩 */
    word-wrap: break-word; /* 긴 단어 줄바꿈 */
    overflow-wrap: break-word; /* 추가적인 줄바꿈 지원 */
    white-space: normal; /* 기본 줄바꿈 동작 활성화 */
    font-size: 0.8rem;
  }

  .nested {
    padding-left: 15px; /* 중첩된 목록은 들여쓰기 */
  }
</style>



<span class="spn3">Seoyeon Kim</span>

<ul>
  <li>
    <span class="spn5">Research Interests</span>
    <p class="my-enumerate">
    - Biostatistics
    </p>
    <p class="my-enumerate">
    - Clinical Trials
    </p>
    <p class="my-enumerate">
    - Nonparametric Inference
    </p>
  </li>
  <li>
    <span class="spn5">Publications</span>
    <p class="my-enumerate">
      - Nonparametric logistic regression based on sparse triangulation over a compact domain (published)
    </p>
    <p class="my-enumerate">
    - Dynamics of COVID-19 Risk Perception and Predictors in South Korea: A Two-Year Longitudinal Study from the Pandemic’s Beginning (2020-2021) (accepted)
    </p>
    <p class="my-enumerate">
    - Comparison of cognitive and affective dimensions of multi-risk perception according to sociodemographic characteristics in a South Korean population (under review)
    </p>
    <p class="my-enumerate">
    - Political party preference, accountability, and risk perception: Crowd crush in South Korea (under review)
    </p>
  </li>
</ul>
