## 정확한 답이 필요하다면 float과 double은 피하라.

---

- float, double은 공학용 계산을 위해서 설계되었고, 정밀한 근사치로 계산되도록 설계되었다.
- 성능 저하를 신경 쓰지 않겠다면, 정확한 계산을 위해서는 BigDecimal을 사용하자.
- 성능이 중요하다면, 소수점은 직접 관리하고, int, long을 사용하여 계산하자. 


---
### 요약
`
정확한 답이 필요한 계산에는 float과 double을 피하라. 소수점 추적은 시스템에 맡기고, 코딩 시의 불편함
이나 성능 저하를 신경 쓰지 않겠다면 BigDecimal(반올림에 대한 기능)을 사용하라.

`