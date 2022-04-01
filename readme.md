# Club des Devs: Plotly and Pandas for storing/plotting results

This repo contains a jupyter notebook that shows how I run my experiments:
- use some library to produce results, with some hyperparameters
- store interesting results manually in pandas dataframe (and store it at the end)
- plot what I want with plotly express (+ some aestetics)

This is by no means the best or optimal way to do experiments, but I find this way convenient and very transparent. It enables to store all metadata that I want for each run. It also allows me to get rid of matplotlib :)

### Setup

So that everyone works in the same environment, I suggest to start by setting up a virtual environment

`python3 -m venv cddcohen`
`source cddcohen/bin/activate`

(I used python 3.10.2 but should work with older version (?))

Then install a few dependencies

`pip install -r requirements.txt`

in particular pandas for dataframes (we will use them for storage) and plotly (for figures) + kaleido for rendering.

To install the virtual environment to use with Jupyter run (still in venv)

`python -m ipykernel install --user --name=cddcohen`

where you can inspect the `kernel.json` file to check everything is fine.

