# finrate-data

금융 공시 데이터. [`finrate-crawler`](https://github.com/iankim1306/finrate-crawler)가
**매일 07:10 KST**에 자동 갱신한다. 앱은 이 저장소의 raw URL을 직접 fetch한다.

| 파일 | 내용 | 출처 |
|---|---|---|
| `deposits_all.json` | 정기예금 통합(은행+저축은행) | 금융상품통합비교공시시스템(금융감독원) 금융회사 상품정보 |
| `deposits.json` | 정기예금(은행) | 〃 |
| `savings.json` | 적금(은행) | 〃 |
| `sbrate.json` | 저축은행 예금·적금·파킹 | 금감원 + 저축은행중앙회 |
| `brokerfee.json` | 증권사 주식거래 수수료 | 금융투자협회 전자공시 |
| `fxfee.json` | 환전수수료 | 전국은행연합회 소비자포털 |
| `history.json` | 일별 1위 금리 스냅샷 | 누적 기록 |

## 유의사항
공시금리는 금융회사 사정에 따라 수시로 변경될 수 있습니다.
**가입 전 반드시 해당 금융회사에 확인**하시기 바랍니다.
본 데이터는 정보 제공 목적이며 금융상품의 판매·중개를 위한 것이 아닙니다.
