
질문
``` 
데이터셋에 대한 컬럼별 자세한 설명을 markdown 표로 작성
[데이터셋]
ID

Gender

Ever_Married

Age

Graduated

Profession

Work_Experience

Spending_Score

Family_Size

Var_1
458989
Female
Yes
36
Yes
Engineer
0.0
Low
1.0
Cat_6
458994
Male
Yes
37
Yes
Healthcare
8.0
Average
4.0
Cat_6
458996
Female
Yes
69
No
0.0
Low
1.0
Cat_6
459000
Male
Yes
59
No
Executive
11.0
```

| 컬럼명            | 데이터 타입 | 설명                                   |
|------------------|-------------|----------------------------------------|
| ID               | int64      | 고유 식별자 (각 데이터 포인트의 ID)   |
| Gender           | object     | 성별 (예: Male, Female)               |
| Ever_Married     | object     | 결혼 여부 (예: Yes, No)               |
| Age              | int64      | 나이                                   |
| Graduated        | object     | 졸업 여부 (예: Yes, No)               |
| Profession       | object     | 직업 (예: Engineer, Healthcare, Executive) |
| Work_Experience   | float64    | 근무 연수 (연차)                       |
| Spending_Score   | object     | 지출 점수 (예: Low, Average, High)    |
| Family_Size      | float64    | 가족 수                                |
| Var_1            | object     | 숨김 분류 (예: Cat_6)                  |