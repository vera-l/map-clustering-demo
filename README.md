# Map server-side clustering demo

I used data [All Cities with a population > 1000](https://data.opendatasoft.com/explore/dataset/geonames-all-cities-with-a-population-1000%40public/table/?disjunctive.country) dataset for a a demonstration.

1. Install requirements

```sh
pip3 install -r requirements.txt
```

2. Download cities dataset and import cities to database

```sh
./import_data_from_csv.py geonames-all-cities-with-a-population-1000.csv
```

3. Run a server

```sh
./server_run.py
```
