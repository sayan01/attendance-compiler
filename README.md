# attendance compiler

compile attendance files created using [sports-sec-attendance-app](https://github.com/sayan01/sports-sec-attendance-app)
into a singular xlsx file with separate sheets for each section.

## installation:
- clone repo - `git clone https://github.com/sayan01/attendance-compiler`
- run pip install - `pip install -r requirements.txt`
- run script - `python3 main.py` or `./main.py` with arguments

## usage:

```
./main.py file1.csv file2.csv file3.csv file4.csv
```

normal shell globbing works, so if folder only contains csv which are of today, do

```
./main.py *.csv
```

or any other globbing that makes sense

```
./main csv-sports-sec-2023-03-23*csv
```

or 

```
./main csv-*-2023-03-23*csv
```
