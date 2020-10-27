# LOAN APPLICATIONS

| No. |   APP NAME   |  BUGS FOUND |
| :-- |  :--------:  | :----------: |
| 1   | Tala         |              |
| 2   | Branch       |              |
| 3   | Timiza       |              |
| 4   | Stawika      |              |
| 5   | Zenka        |
| 6   | Senti        |
| 7   | Okolea       |
| 8   |              |
| 9   |              |
| 10  |              |
| 11  |              |
| 12  |              |
| 13  |              |
| 14  |              |
| 15  |              |   
## Stawika Loan Application
Bug 1:
One can use the endpoint in the application to query iprs details thus the company can incur exta cost if the endpoint is used inappropriately

#### Request
`curl -X GET --header 'Accept: application/json' 'https://live-api.stawika.com/user-info?idNumber=35949821'`
