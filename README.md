# 🌪️💧 풍수해/지진 재해 보험 대상 지역 선정 시스템 📊🛡️

## 📌 소개
자연재해에 미리 대비하는 **보험 가입 유도 시스템**!<br>
이 프로젝트는 **재난안전데이터**와 **농식품 공공데이터**를 활용해 풍수해 🌧️와 지진 🌍 등 재해 발생 가능성이 높은 지역을 선정하여, 보험사, 정부, 시민 모두가 미리 대비할 수 있도록 돕습니다. 

```
COPYRIGHT 2024 MAFRA INC. ALL RIGHTS RESERVED.
위 데이터분석 인사이트 및 대시보드 웹사이트는 "MAFRA"의 저작물이므로 상업적 이용을 금합니다.
```

## 🧑‍🦲 팀원(가나다순)

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/RosieOh"><img src="https://github.com/SP0F0/.github/assets/62829894/89996fac-c626-44e8-ba10-3dcc17252079" width="100px;" alt=""/><br /><sub><b>오태훈</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/sendjin5"><img src="https://github.com/SP0F0/.github/assets/62829894/fc0c73b5-3bdc-4edf-8c7f-b7b8eff9bf67" width="100px;" alt=""/><br /><sub><b>이승렬</b></sub></a><br /></td>
             <td align="center"><a href="https://github.com/sendjin5"><img src="https://github.com/SP0F0/.github/assets/62829894/fc0c73b5-3bdc-4edf-8c7f-b7b8eff9bf67" width="100px;" alt=""/><br /><sub><b>김민석</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>

## 🎯 목표
### 시스템 구성
1. **📥 데이터 수집**
   - **기상청 강수 정보** ☔, **지진 통보**, **행정안전부 재해위험지구** 데이터를 통해 풍수해 및 지진 관련 데이터를 수집하고 지도에 시각화합니다.
   - **농식품 팜맵 오픈 API** 🌾를 통해 전국의 논, 밭, 과수원 위치를 지도에 표시합니다.

2. **📊 데이터 분석**
   - **재해위험지구**와 **농경지**가 중첩되는 지역을 분석하여 재해 발생 빈도가 높은 곳을 식별합니다.

3. **🛠️ 시스템 구현**
   - **재난안전데이터 공유 플랫폼**을 통해 시각화된 데이터를 제공하여, 보험사 및 시민들이 대상 지역에 대한 정보를 쉽게 확인할 수 있도록 합니다.

## 🌈 기대효과
- **보험사**: 위험 지역을 미리 파악하여, 더 효율적인 보험 상품 개발과 신속한 보상 지급 가능 💡
- **정부**: 재난 관리와 보상 지원의 효율성 향상으로 국민 안전 보호 강화 🚨
- **시민**: 고위험 지역에 대한 정보를 바탕으로 필요한 보험에 가입하여 재난 피해를 최소화 💼

## 📂 활용 데이터
- **팜맵 오픈 API** 📍: [농식품 팜맵 서비스](https://agis.epis.or.kr/ASD/main/intro.do)
- **기상청 동네 6시간 강수량** ☔: [재난안전데이터공유플랫폼](https://www.safetydata.go.kr/disaster-data/view?dataSn=26)
- **산림청 산사태 예보정보** 🏞️: [재난안전데이터공유플랫폼](https://www.safetydata.go.kr/disaster-data/view?dataSn=695)
- **행정안전부 지역 재해위험지구** 🚧: [재난안전데이터공유플랫폼](https://www.safetydata.go.kr/disaster-data/view?dataSn=52)

## 🗺️ 시스템 구성도 예시
**농경지 위치 조회**와 함께 **강수량** 및 **재해위험지구** 데이터를 조합하여, 농경지별 재해 위험성을 평가하고 고위험 지역을 선별할 수 있습니다.

## 📝 요약
**재난안전데이터와 농식품 공공데이터**를 활용한 이 시스템은 **풍수해 및 지진 재해 보험 대상 지역**을 미리 선정하여, 국민의 안전을 강화하고 재난 발생 시 효과적인 대응을 도모합니다. 🚀

## 🔗 관련 링크
- 🌾 [농식품 팜맵 서비스](https://agis.epis.or.kr/ASD/main/intro.do)
- ☔ [재난안전데이터공유플랫폼 - 기상청 동네 6시간 강수량](https://www.safetydata.go.kr/disaster-data/view?dataSn=26)
- 🏞️ [재난안전데이터공유플랫폼 - 산림청 산사태 예보정보](https://www.safetydata.go.kr/disaster-data/view?dataSn=695)
- 🚧 [재난안전데이터공유플랫폼 - 행정안전부 지역 재해위험지구](https://www.safetydata.go.kr/disaster-data/view?dataSn=52)

---

> 이 README는 자연재해에 대비해 **풍수해 및 지진 고위험 지역**을 시각화하여 국민의 안전과 대비를 강화하는 프로젝트의 개요를 제공합니다. 💪🌍
