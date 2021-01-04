# moraltopology
> A library to model moral topology and the data pipeline around it


This file will become your README and also the index of your documentation.

## Install

`pip install moraltopology`

## How to use

Start by creating a `MoralTopology` object with your name and data.

```
mt = MoralTopology(name="Vishal Bakshi", data={})
```

You can access the data with `.data`:

```
mt.data
```




    {}



You can access your name with `.name`

```
mt.name
```




    'Vishal Bakshi'



You can print your name (read-only) with `.username()`

```
mt.username()
```




    'Vishal Bakshi'


