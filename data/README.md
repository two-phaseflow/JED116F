Data files used by the notebooks. Read them in Colab with

    !wget -q https://raw.githubusercontent.com/two-phaseflow/JED116F/main/data/<filename>

or with pandas directly from the raw URL.

## Files

| file | content | source |
|---|---|---|
| K37_steptest_2008-01-18_raw.csv | K-37 (Krafla) injection step test, pressure at 1420 m every 5 s, injection rate | ISOR measurement database, https://uos.is/boreholes/58037 |
| K38_steptest_2008-07-20_raw.csv | K-38 (Krafla) injection step test, pressure at 1780 m every 10 s, injection rate | ISOR measurement database, https://uos.is/boreholes/58038 |
| NJ15_steptest_1985-10-21_record.csv | NJ-15 (Nesjavellir) injection step test, 21.10.1985 (the report says 1995), pressure at 1590 m | Ntihabose (2014) UNU-GTP report, digitized from Figure 4 |
| BR23_interference_1980.csv | Ohaaki BR19 to BR23 interference test, water level drop in BR23 (magnitude) | Grant and Bixley, Fig. A1.1, digitized |
| BR20_output_test.csv | Ohaaki BR20 discharge test, lip pressure and weir readings | Grant and Bixley, digitized |
