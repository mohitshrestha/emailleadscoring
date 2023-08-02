# emailleadscoring

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

This file will become your README and also the index of your
documentation.

## Install

``` sh
pip install emailleadscoring
```

## How to use

Fill me in please! Don’t forget code examples:

``` python
import emailleadscoring as els
```

Testing: Cost Table Function

``` python
# els.cost_calc_monthly_cost_table()
```

Testing: Total Cost Function

``` python
# els.cost_total_unsub_cost(els.cost_calc_monthly_cost_table())
```

``` python
# import pandas_flavor as pf
# - Using pandas_flavor package and adding @pf.register_dataframe_method # Using pandas_flavor package: @pf.register_dataframe_method** Turns a function into a data frame method so we can use method chaining

# els.cost_calc_monthly_cost_table() \
#     .cost_total_unsub_cost()
```

Testing: Simulation Function

``` python
# els.cost_simulate_unsub_costs()
```

Testing: Plot Simulation (Heat Map) Function

``` python
# els.cost_simulate_unsub_costs(
#     email_list_monthly_growth_rate = [0, 0.015, 0.025, 0.035]
# ) \
#     .cost_plot_simulated_unsub_costs()
```
