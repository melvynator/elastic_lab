# Download the two datasets

To index the accounts documents please type in a terminal:

```
curl -H "Content-Type: application/json" -XPOST 'localhost:9200/bank/account/_bulk?pretty&refresh' --data-binary "@accounts.json"
```

To index the shakespeare documents please type in a terminal:

```
curl -H "Content-Type: application/json" -XPOST 'localhost:9200/shakespeare/act/_bulk?pretty&refresh' --data-binary "@shakespeare.json"
```
