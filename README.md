# VTAH_QA_Demo_API_Test
Demo project of API test for VISEO Tech An Hour (VTAH) around the QA Job


## API Test

We use bruno for api testing: <https://docs.usebruno.com>

API tests are divided in three folders in the same collection:

1. Product (covers routes used to manage product)
2. SearchProduct (covers routes used to search product)
3. UserAccount (covers routes used for user creation and account management)

```bash
cd Automation-Exercise
npm i

# run all tests
bru run --env vtah
# run all tests and collect the results in json format
bru run --env vtah --output results/results.json
```