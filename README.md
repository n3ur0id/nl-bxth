# BX.in.th api

## Examples

### Get Balance

The following returns a list of all the balances

```javascript
i.balance({apikey: '', apisecret: '', endpoint: 'balance'}, function(cb) {
  console.log(cb);
});
```

### Transaction History

```javascript
i.transactions({apikey: '', apisecret: ''}, function(cb) {
  console.log(cb);
})
```
