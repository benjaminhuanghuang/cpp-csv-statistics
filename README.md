## C++ Weather Statistics App

## CSV file operation


## time 


## map
- lower_bound(k)
  returns iterator to first element whose key gose AFTER k

  returns iterator to element whose key matches k

- upper_bound(k)
  returns iterator to first element whose key gose AFTER k

  returns iterator to element whose key matches k


Example
```
  startTimePressure = timeToPressure_.lower_bound(startDateTime);
  endTimePressure = timeToPressure_.lower_bound(endDateTime);
```