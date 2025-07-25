
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
    max-width: 600px; /* 최대 너비 제한 */
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


<span class="spn3">Jinju Kim</span>

<ul>
  <li>
    <span class="spn5">Research Interests</span>
    <p class="my-enumerate">
    <i class="fa-solid fa-hashtag" style="font-size:0.7rem"></i> Survey Sampling
    </p>
    <p class="my-enumerate">
    <i class="fa-solid fa-hashtag" style="font-size:0.7rem"></i> Multivariate Data Analysis
    </p>
    <p class="my-enumerate">
    <i class="fa-solid fa-hashtag" style="font-size:0.7rem"></i> Covariance Modelling
    </p>

<div style="height: 20px;"></div>

    <span class="spn5">First Job</span>
    <p class="my-enumerate">
      <i class="fa-solid fa-briefcase" style="font-size:0.7rem"></i> Research Assistant, Marketing Research Division, Gallup Korea
    </p>

</li>

  <li>
    <span class="spn5">Publications</span>
    <p class="my-enumerate">
      - Analysis of US airport network and KOSPI volatility based on covariance regression modeling method (published)
    </p>
    <p class="my-enumerate">
    - A study on risk perception in South Korea regarding the discharge of treated radioactive water from Fukushima (under review)
    </p>
    <p class="my-enumerate">
      - Establishing a panel dataset for the survey on the effects of minimum wage implementation (published)
    </p>
  </li>
</ul>
