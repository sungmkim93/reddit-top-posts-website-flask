# reddit-top-posts-website-flask For Study MongoDB
## No SQL 이란?
RDBMS는 보통 "관계형 데이터베이스" 라고 한다. NoSQL은? "비관계형 데이터베이스"이다.<br>
NoSQL 데이터베이스는 전통적인 관계형 데이터베이스 보다 덜 제한적인 일관성 모델을 이용하는 데이터의 저장 및 검색을 위한 매커니즘을 제공한다.<br>
이러한 접근에 대한 동기에는 디자인의 단순화, 수평적 확장성, 세세한 통제를 포함한다.<br>
NoSQL 데이터베이스는 단순 검색 및 추가 작업을 위한 매우 최적화된 키 값 저장 공간으로, Latency(Latency is the time required to perform some action or to produce some result.)와 
Throughput(Throughput is the number of such actions executed or results produced per unit of time.)과 관련하여 상당한 성능 이익을 내는 것이 목적이다.<br>
NoSQL 데이터베이스는 BigData와 Realtime(Dynamic) Web application의 상업적 이용에 널리 쓰인다. <br>
또, NoSQL 시스템은 SQL 계열 쿼리 언어를 사용할 수 있다는 사실을 강조한다는 면에서 "Not Only SQL"로 불리기도 한다.<br>

### 특징
- NoSQL 제품군이 RDBMS와의 다른 점으로는 Scheme가 없다. 즉, Data 관계와 정해진 규격(table - column의 정의)이 없다.<br>
- 관계정의가 없으니 Join이 불가능하다. (하지만 reference와 같은 기능으로 비슷하게 구현은 가능함)<br>
- Transaction을 지원하지 않는다. (MongoDB는 지원하려는 추세?..) <br>
- 분산처리 (수평적 확장)를 쉽게 제공한다.(대부분의 NoSQL DB는 분산처리기능을 목적으로 나왔기 때문에 Framework에 포함)<br>#

### 사용하는 이유?
- 아주 많은 Data의 효율적인 처리가 필요할 때
- Data의 분산처리, 빠른 쓰기 및 Data의 안정성이 필요할 때 (특정 서버에 장애가 발생했을 때에도 Data유실이나 서비스 중지가 없는 형태의 구조이기 때문에, NoSQL을 사용한다.)<br>
- Transaction을 지원하지 않고 (may not provide full ACID = Atomicity Consistency Isolation Durability)있는데도 
분산형이고 Data안정성(Fault tolerant) 구조라는 점은 아주 흥미로움(?)<br>

### 보통 NoSQL은 Key-value, column, document 형식등의 데이터모델을 이용한다.<br>
#### 1. Key-value storage type: Redis, Memcached, Oracle Coherence, 
#### 2. Column oriented Store: Cassandra, HBASE, Cloud Datastore
#### 3. Document type: MongoDB, Couchbase
#### 4. Graph type: Neo4j

## Source of information
https://hero0926.tistory.com/29 <br>
https://ko.wikipedia.org/wiki/NoSQL <br>
