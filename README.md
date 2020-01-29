# python-path-example

## Bash only cares about where you are when you run the script

To check this, run:

```bash
bash echo.sh
bash scripts/echo.sh
```

## Python cares about where the script is located and will resolve modules relative to that location

To test this, run:

```bash
python src/dostuff.py
python src/scripts/dostuff.py
```

You can also just run this via the bash script with the same results:

```bash
bash run.sh
bash scripts/run.sh
```
