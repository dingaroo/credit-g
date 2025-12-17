# German Credit Classification Dataset


## Data Dictionary

| Column Name              | Non-Null Count | Dtype   | Description              |
|--------------------------|----------------|---------|--------------------------|
| checking_status          | 1000 non-null  |  object | Status of existing checking account, in Deutsche Mark. |
| duration                 | 1000 non-null  |  float64| Duration in months |
| credit_history           | 1000 non-null  |  object | Credit history (credits taken, paid back duly, delays, critical accounts) |
| purpose                  | 1000 non-null  |  object | Purpose of the credit (car, television,...). |
| credit_amount            | 1000 non-null  |  float64| Credit amount |
| savings_status           | 1000 non-null  |  object | Status of savings account/bonds, in Deutsche Mark. |
| employment               | 1000 non-null  |  object | Present employment, in number of years. |
| installment_commitment   | 1000 non-null  |  float64| Installment rate in percentage of disposable income |
| personal_status          | 1000 non-null  |  object | Personal status (married, single,...) and sex |
| other_parties            | 1000 non-null  |  object | Other debtors / guarantors |
| residence_since          | 1000 non-null  |  float64| Present residence since X years |
| property_magnitude       | 1000 non-null  |  object | Property (e.g. real estate) |
| age                      | 1000 non-null  |  float64| Age in years |
| other_payment_plans      | 1000 non-null  |  object | Other installment plans (banks, stores) |
| housing                  | 1000 non-null  |  object | Housing (rent, own, ...)
| existing_credits         | 1000 non-null  |  float64| Number of existing credits at this bank  |
| job                      | 1000 non-null  |  object | Job |
| num_dependents           | 1000 non-null  |  float64| Number of people being liable to provide maintenance for. |
| own_telephone            | 1000 non-null  |  object | Telephone (yes,no)  |
| foreign_worker           | 1000 non-null  |  object | Foreign worker (yes,no)  | 
| class                    | 1000 non-null  |  object | Whether applicant is a good or bad credit risk. 'good' indicates low risk, 'bad' indicates high risk. **Target Variable**       |


