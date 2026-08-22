## Important DAX Measures

### Total Runs

```DAX
Total Runs =
SUM(Data[Runs])

### Batting Average

```DAX
Batting Average =
DIVIDE(
    SUM(Data[Runs]),
    SUM(Data[Outs]),
    0
)

### Strike Rate

```DAX
Strike Rate =
DIVIDE(
    SUM(Data[Runs]) * 100,
    SUM(Data[Balls]),
    0
)

