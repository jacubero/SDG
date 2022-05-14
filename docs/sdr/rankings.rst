.. _rankings:

Rankings
========

Overall performance
-------------------

All 193 UN Member States are ranked by their overall score. The overall score measures a country's total progress towards achieving all 17 SDGs. The score can be interpreted as a percentage of SDG achievement. A score of 100 indicates that all SDGs have been achieved.

.. altair-plot::

   import altair as alt
   import pandas as pd

   df_data2021 = pd.read_csv('datasets/data2021.csv')
   df_data2021.rename(columns={'2021 SDG Index Score':'Score'}, inplace=True)

   df_data2021[['Country','Score']]