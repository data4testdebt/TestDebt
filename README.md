# TestDebt

Identifying and Quantifying Test Technical Debt in the Co-Evolving Production & Test Code


### data

The data of 13 projects as our study subjects.

- all_issues.json: issues from the bug-tracing system JIRA
- commits_all.json / commits_clean.json: commits in the entire project history / in the sampled history
- rankings.json: the ranked TestDebts


### results

The results of four research questions in our evaluation.

- RQ1: Can our approach identify TestDebts that account for significantly more test maintenance costs than simply considering all test files?
- RQ2: Can our approach identify TestDebts that incur more maintenance costs than would be expected given their sizes?
- RQ3: Can our approach identify TestDebts that continue to incur significant test maintenance costs in the future?
- RQ4: Can our approach build DebtModels to accurately predict the future costs of TestDebts?
