# cryptopool-simulator
Similator for cryptopools written in C++

# Some run instruction comming here

## simu

compile:

```bash
make all
```

run simulation

```bash
./simu sample_in_2_currencies.json
```

## For the python code

Create and initialize a Python [virtual environment](https://docs.python.org/3/library/venv.html).

```bash
cd cryptopool-simulator
python -m venv .venv
source .venv/bin/activate
```

Then install the dependencies:

```bash
pip install -r requirements.txt
```

## create configuration.json files

scripts/make_inputs_*.py generates configuration.json files which are used as input for the simulation
