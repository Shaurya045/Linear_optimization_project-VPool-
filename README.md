# VPool

VPool is a python implementation for the project titled "Optimization problems in vehicle route network design". The project aims at tackling the problem of inefficient vehicle sharing systems currently present in public transport domain and mobility on demand systems by suggesting changes in the way route planning and ride combining for sharing based systems is done while assuring optimization in several other domains.

## Workflow

The problem is tackled in a 3 phase approach:
* Problem modelling in terms of graph.
* Application of graph algorithms to get desired solution.
* Optimization of different domains on obtained solution.

## Dependencies

The code runs an instance of the python wrapper of the Gurobi mathematical programming solver, we will need to obtain our own license and get access to the python wrapper.

Some basic python libraries required for running the code (add ons and backend requirements to these are listed in requirements.txt):

```
numpy
pandas
gurobipy
datetime
networkx
folium
```
## Running the code

In order to run the code, first obtain either a pickled format or csv format of the dataset you are going to run it on, and then type the command:
```
pip install -r requirements.txt
python driver_script.py option input_filepath output_filepath 
```