---
description: Shading
---

# Shading



#### 샤딩 구성시 고려해야할 상황

* 샤드 확장
* 백엔드 에서의 connection 관리 \( 2017년 deview 영상이라서 legacy이지 않나 싶다.\)
* 데이터 정합성





SQL Routing\(\);

#### 고려해야할 상황

* 샤드 확장
* 백엔드에서 connection 관리\( for문 \)
* 데이터 정합성
  * count 등

```sql
create shard tablee
```





```sql
create global tablee
```

#### sharding caatlog

* group id
* driver가 groupid 계산
* 
