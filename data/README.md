# Ames Housing data

Place the input file here as **`AmesHousing.csv`**. Input data is not included in this repository.

The report uses the Ames Housing dataset attributed to **De Cock (2011)**, with 2,930 housing records and 82 attributes. Use the full Ames dataset rather than the smaller competition training split.

The analysis calls `read.csv()` with its default name conversion and requires these resulting R column names:

```text
SalePrice
Overall.Qual
Gr.Liv.Area
Garage.Cars
Garage.Area
Total.Bsmt.SF
X1st.Flr.SF
Year.Built
```

Additional numeric columns are used during exploratory correlation analysis. Keep the full dataset for that section. The model data uses complete cases for the eight fields above.

Column names differ across Ames distributions. For example, a source header `1st Flr SF` becomes `X1st.Flr.SF` under R's default syntactic name conversion. Check the imported names before rendering; the notebook does not automatically reconcile alternative schemas.
