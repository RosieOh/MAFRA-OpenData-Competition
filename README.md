# 풍수해/지진 재해 보험 대상 지역 선정 시스템

## 소개
이 프로젝트는 재난안전데이터와 농식품 공공데이터를 기반으로 풍수해와 지진 등의 재해 발생 가능성이 높은 지역을 선정하여 보험 가입을 유도하는 시스템을 제안합니다. 이 시스템을 통해 보험사, 정부, 시민 모두가 재해에 대비할 수 있도록 지원합니다.

## 목표
### 시스템 구성
1. **데이터 수집**:
   - 공공데이터 포털의 기상청 강수정보, 지진통보, 행정안전부의 재해위험지구 데이터를 활용하여 풍수해와 지진 관련 데이터를 수집하고 지도 시각화합니다.
   - 농식품 팜맵 오픈 API를 활용하여 전국의 논, 밭, 과수원을 지도 시각화합니다.

2. **데이터 분석**:
   - 재해위험지구와 농경지 공통 분포 지역에 대해서 재해 발생 빈도가 높은 지역을 식별합니다.

3. **시스템 구현**:
   - 재난안전데이터 공유 플랫폼을 활용하여 풍수해/지진 재해 보험 대상 지역을 시각화하고 보험사 및 시민들이 접근할 수 있는 시스템을 구현합니다.

## 기대효과
- **보험사**: 재해 발생 가능성이 높은 지역을 사전에 파악하여 보험 상품을 개발하고 보상을 효율적으로 지급할 수 있습니다.
- **정부**: 재난 관리 및 보상 지원에 효율성을 높일 수 있으며, 국민의 안전을 보다 신속하게 보호할 수 있습니다.
- **시민**: 안전한 지역을 선택하여 보험에 가입함으로써 재난 발생 시 피해를 최소화할 수 있습니다.

## 활용 데이터
- **팜맵 오픈 API**: [농식품 팜맵 서비스](https://agis.epis.or.kr/ASD/main/intro.do)
- **기상청 동네 6시간 강수량**: [재난안전데이터공유플랫폼](https://www.safetydata.go.kr/disaster-data/view?dataSn=26)
- **산림청 산사태 예보정보**: [재난안전데이터공유플랫폼](https://www.safetydata.go.kr/disaster-data/view?dataSn=695)
- **행정안전부 지역 재해위험지구**: [재난안전데이터공유플랫폼](https://www.safetydata.go.kr/disaster-data/view?dataSn=52)

## 시스템 구성도 예시
- 팜맵 오픈 API의 지적표기를 활용해 농경지의 위치를 조회하고, 기상청 강수량 데이터와 행정안전부 지역 재해위험지구 표기를 통해 농경지 별 재해 위험지를 선별할 수 있습니다.

## 요약
이 시스템을 통해 재난안전데이터와 농식품 공공데이터를 활용하여 풍수해/지진 재해 보험 대상 지역을 선정함으로써 국민의 안전을 보호하고 재난 발생 시 효율적인 대처를 도모하는 것이 목표입니다. 

## 관련 링크
- [농식품 팜맵 서비스](https://agis.epis.or.kr/ASD/main/intro.do)
- [재난안전데이터공유플랫폼 - 기상청 동네 6시간 강수량](https://www.safetydata.go.kr/disaster-data/view?dataSn=26)
- [재난안전데이터공유플랫폼 - 산림청 산사태 예보정보](https://www.safetydata.go.kr/disaster-data/view?dataSn=695)
- [재난안전데이터공유플랫폼 - 행정안전부 지역 재해위험지구](https://www.safetydata.go.kr/disaster-data/view?dataSn=52)

---

This README provides a comprehensive overview of the system aimed at identifying high-risk areas for storm and earthquake insurance using public disaster safety data and agricultural data. Through this project, we aim to enhance the safety and preparedness of the population against natural disasters.
