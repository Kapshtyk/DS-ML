# Steel temperature prediction

In order to optimise production costs, a steel mill needs to reduce energy consumption during the steel processing stage, and to do this it is necessary to build a model that predicts the temperature of the steel.

We had several datasets at our disposal:

- `data_arc.csv` - electrode data;
- `data_bulk.csv` - bulk feed data (volume);
- `data_gas.csv` - data on gas purging of the alloy;
- `data_temp.csv` - temperature measurement results;
- `data_wire.csv` - data on wire materials (volume).

As part of the solution of the task, in addition to working with the data and training the model, it was necessary to prepare a report for the business, the text of which is given at the end of the notebook.

## Libraries
- pandas
- numpy
- matplotlib, seaborn
- sklearn
