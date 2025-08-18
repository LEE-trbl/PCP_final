# Type 1(건물별 모델)

## base_1

1. `temperature` : 건물별 온도
2. `humidity` : 건물별 습도
3. `windspeed` : 건물별 풍속"
4. `day_of_week` - 요일 (day of week)
5. `month` - 월
6. `week` - 주차
7. `is_holiday` - 휴일 여부
8. `sin_hour` - 시간의 사인값 (24시간 주기)
9. `cos_hour` - 시간의 코사인값 (24시간 주기)
10. `day_hour_mean` - 요일별 시간 평균 온도
11. `day_hour_std` - 요일별 시간 온도 표준편차
12. `holiday_hour_mean` - 휴일 시간 평균 온도
13. `holiday_std` - 휴일 시간 온도 표준편차
14. `THI` - 온도-습도 지수 (Temperature-Humidity Index)
15. `WCT` - 체감 온도 (Wind Chill Temperature)
16. `CDH` - 냉방도시 (Cooling Degrees Hours)
17. `is_peak_season` - 성수기 여부

## + detail_1

1. `summer_sin` - 여름 계절의 사인 값
2. `summer_cos` - 여름 계절의 코사인 값
3. `day_max_temperature` - 일최고온도
4. `day_min_temperature` - 일최저온도
5. `day_mean_temperature` - 일평균온도
6. `day_diff_temperature` - 일교차

---

## Type 2(전체 건물 모델)

## base_2

1. `temperature` : 건물별 온도
2. `humidity` : 건물별 습도
3. `windspeed` : 건물별 풍속"
4. `day_of_week` - 요일 (day of week)
5. `month` - 월
6. `week` - 주차
7. `is_holiday` - 휴일 여부
8. `sin_hour` - 시간의 사인값 (24시간 주기)
9. `cos_hour` - 시간의 코사인값 (24시간 주기)
10. `day_hour_mean` - 요일별 시간 평균 온도
11. `day_hour_std` - 요일별 시간 온도 표준편차
12. `holiday_hour_mean` - 휴일 시간 평균 온도
13. `holiday_std` - 휴일 시간 온도 표준편차
14. `THI` - 온도-습도 지수 (Temperature-Humidity Index)
15. `WCT` - 체감 온도 (Wind Chill Temperature)
16. `CDH` - 냉방도시 (Cooling Degrees Hours)
17. `is_peak_season` - 성수기 여부
18. `total_area` - 건물 총 면적
19. `cooling_area` - 냉방 면적
20. `building_number` - 건물 번호
21. `building_type` - 건물 유형

## + detail_2

1. `summer_sin` - 여름 계절의 사인 값
2. `summer_cos` - 여름 계절의 코사인 값
3. `day_max_temperature` - 일최고온도
4. `day_min_temperature` - 일최저온도
5. `day_mean_temperature` - 일평균온도
6. `day_diff_temperature` - 일교차
7. `pv-temp` - 태양광 발전 온도
8. `ess_pcs_std` - ESS 표준편차


