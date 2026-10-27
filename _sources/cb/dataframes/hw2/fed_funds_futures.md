# Dataframe: `hw2:fed_funds_futures` - 30-Day Fed Funds Futures (ZQ)

Daily bars (dataset GLBX.MDP3, schema ohlcv-1d, parent symbol ZQ.FUT) for all listed ZQ contracts, outrights and calendar spreads. A contract settles at 100 minus the average effective fed funds rate over its month, so 100 minus the close is the market-implied average rate. Filter out spreads before use.


## DataFrame Glimpse

```
Rows: 11751
Columns: 7
$ date   <datetime[ns]> 2026-10-25 00:00:00
$ symbol          <str> 'ZQG7-ZQJ7'
$ open            <f64> 15.5
$ high            <f64> 16.0
$ low             <f64> 15.5
$ close           <f64> 16.0
$ volume          <u64> 333


```

## Dataframe Manifest

| Dataframe Name                 | 30-Day Fed Funds Futures (ZQ)                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/hw2/fed_funds_futures.md)                                       |
| Sources                        | CME Group                                          |
| Providers                      | Databento                                        |
| Provider Links                 | https://databento.com/                                   |
| Tags                           | Futures, Monetary Policy, Fed Funds                                             |
| Access Types                   |                                       |
| How is data pulled?            | Databento historical API via Python                                                   |
| Data available up to (min)     | None                                                             |
| Data available up to (max)     | None                                                             |
| Dataframe Path                 | /Users/apollinaire/Desktop/CAPP/FINM_32800/HW2/hw2-AigleBlanc/_data/fed_funds_futures.parquet                                             |


**Linked Charts:**


- [hw2:fedwatch_latest_forecast](../../charts/hw2.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 2: The Yield Curve and the Policy Path                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [hw2](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     | https://github.com/hw-finm-32800/hw2                  |
| Pipeline Web Page               | <a href="file:///Users/apollinaire/Desktop/CAPP/FINM_32800/HW2/hw2-AigleBlanc/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-10-26 18:58:26           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [hw2:crsp_treasury_consolidated](../../dataframes/hw2/crsp_treasury_consolidated.md)<br>  [hw2:fed_yield_curve](../../dataframes/hw2/fed_yield_curve.md)<br>  [hw2:fed_funds_futures](../../dataframes/hw2/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```

