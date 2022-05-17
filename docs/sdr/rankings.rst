.. _rankings:

Rankings
========

.. currentmodule:: altair

World Index Score
-----------------

.. altair-plot::
   :output: stdout

   import pandas as pd
   import altair as alt

   source = pd.read_csv('rankings/average.csv')

   alt.Chart(source).mark_line(point=True).encode(
      alt.X('Year', scale=alt.Scale(zero=False)),
      alt.Y('Average', scale=alt.Scale(zero=False)),
      order='Year',
      tooltip=['Average']
   )

Index Score versus Spillover Score
----------------------------------

.. tabs::

   .. tab:: 2021

      .. raw:: html
         :file: rankings/indexspill2021.html

   .. tab:: 2020

      .. raw:: html
         :file: rankings/indexspill2020.html


Overall performance
-------------------

All 193 UN Member States are ranked by their overall score. The overall score measures a country's total progress towards achieving all 17 SDGs. The score can be interpreted as a percentage of SDG achievement. A score of 100 indicates that all SDGs have been achieved.

.. tabs::

   .. tab:: 2021

      .. tabs::

         .. tab:: All regions

            .. include:: rankings/index2021all.rst

         .. tab:: East and South Asia

            .. include:: rankings/index2021esa.rst

         .. tab:: Eastern Europe and Central Asia

            .. include:: rankings/index2021eeca.rst

         .. tab:: Latin America and the Caribbean

            .. include:: rankings/index2021lac.rst

         .. tab:: Middle East and North Africa

            .. include:: rankings/index2021mena.rst

         .. tab:: OECD members

            .. include:: rankings/index2021oecd.rst

         .. tab:: Oceania

            .. include:: rankings/index2021oceania.rst

         .. tab:: Sub-Saharan Africa

            .. include:: rankings/index2021afr.rst

   .. tab:: 2020

      .. tabs::

         .. tab:: All regions

            .. include:: rankings/index2020all.rst

         .. tab:: East and South Asia

            .. include:: rankings/index2020esa.rst

         .. tab:: Eastern Europe and Central Asia

            .. include:: rankings/index2020eeca.rst

         .. tab:: Latin America and the Caribbean

            .. include:: rankings/index2020lac.rst

         .. tab:: Middle East and North Africa

            .. include:: rankings/index2020mena.rst

         .. tab:: OECD members

            .. include:: rankings/index2020oecd.rst

         .. tab:: Oceania

            .. include:: rankings/index2020oceania.rst

         .. tab:: Sub-Saharan Africa

            .. include:: rankings/index2020afr.rst

   .. tab:: 2019

      .. tabs::

         .. tab:: All regions

            .. include:: rankings/index2019all.rst

         .. tab:: East and South Asia

            .. include:: rankings/index2019esa.rst

         .. tab:: Eastern Europe and Central Asia

            .. include:: rankings/index2019eeca.rst

         .. tab:: Latin America and the Caribbean

            .. include:: rankings/index2019lac.rst

         .. tab:: Middle East and North Africa

            .. include:: rankings/index2019mena.rst

         .. tab:: OECD members

            .. include:: rankings/index2019oecd.rst

         .. tab:: Oceania

            .. include:: rankings/index2019oceania.rst

         .. tab:: Sub-Saharan Africa

            .. include:: rankings/index2019afr.rst

   .. tab:: 2018

      .. tabs::

         .. tab:: All regions

            .. include:: rankings/index2018all.rst

         .. tab:: East and South Asia

            .. include:: rankings/index2018esa.rst

         .. tab:: Eastern Europe and Central Asia

            .. include:: rankings/index2018eeca.rst

         .. tab:: Latin America and the Caribbean

            .. include:: rankings/index2018lac.rst

         .. tab:: Middle East and North Africa

            .. include:: rankings/index2018mena.rst

         .. tab:: OECD members

            .. include:: rankings/index2018oecd.rst

         .. tab:: Oceania

            .. include:: rankings/index2018oceania.rst

         .. tab:: Sub-Saharan Africa

            .. include:: rankings/index2018afr.rst

   .. tab:: 2017

      .. tabs::

         .. tab:: All regions

            .. include:: rankings/index2017all.rst

         .. tab:: East and South Asia

            .. include:: rankings/index2017esa.rst

         .. tab:: Eastern Europe and Central Asia

            .. include:: rankings/index2017eeca.rst

         .. tab:: Latin America and the Caribbean

            .. include:: rankings/index2017lac.rst

         .. tab:: Middle East and North Africa

            .. include:: rankings/index2017mena.rst

         .. tab:: OECD members

            .. include:: rankings/index2017oecd.rst

         .. tab:: Oceania

            .. include:: rankings/index2017oceania.rst

         .. tab:: Sub-Saharan Africa

            .. include:: rankings/index2017afr.rst

   .. tab:: 2016

      .. tabs::

         .. tab:: All regions

            .. include:: rankings/index2016all.rst

         .. tab:: East and South Asia

            .. include:: rankings/index2016esa.rst

         .. tab:: Eastern Europe and Central Asia

            .. include:: rankings/index2016eeca.rst

         .. tab:: Latin America and the Caribbean

            .. include:: rankings/index2016lac.rst

         .. tab:: Middle East and North Africa

            .. include:: rankings/index2016mena.rst

         .. tab:: OECD members

            .. include:: rankings/index2016oecd.rst

         .. tab:: Oceania

            .. include:: rankings/index2016oceania.rst

         .. tab:: Sub-Saharan Africa

            .. include:: rankings/index2016afr.rst

Spillover performance
---------------------

Countries are ranked by their spillover score. Each country's actions can have positive or negative effects on other countries' abilities to achieve the SDGs. The Spillover Index assesses such spillovers along three dimensions: environmental & social impacts embodied into trade, economy & finance, and security. A higher score means that a country causes more positive and fewer negative spillover effects.

.. tabs::

   .. tab:: 2021

      .. tabs::

         .. tab:: All regions

            .. include:: rankings/spill2021all.rst

         .. tab:: East and South Asia

            .. include:: rankings/spill2021esa.rst

         .. tab:: Eastern Europe and Central Asia

            .. include:: rankings/spill2021eeca.rst

         .. tab:: Latin America and the Caribbean

            .. include:: rankings/spill2021lac.rst

         .. tab:: Middle East and North Africa

            .. include:: rankings/spill2021mena.rst

         .. tab:: OECD members

            .. include:: rankings/spill2021oecd.rst

         .. tab:: Oceania

            .. include:: rankings/spill2021oceania.rst

         .. tab:: Sub-Saharan Africa

            .. include:: rankings/spill2021afr.rst

   .. tab:: 2020

      .. tabs::

         .. tab:: All regions

            .. include:: rankings/spill2020all.rst

         .. tab:: East and South Asia

            .. include:: rankings/spill2020esa.rst

         .. tab:: Eastern Europe and Central Asia

            .. include:: rankings/spill2020eeca.rst

         .. tab:: Latin America and the Caribbean

            .. include:: rankings/spill2020lac.rst

         .. tab:: Middle East and North Africa

            .. include:: rankings/spill2020mena.rst

         .. tab:: OECD members

            .. include:: rankings/spill2020oecd.rst

         .. tab:: Oceania

            .. include:: rankings/spill2020oceania.rst

         .. tab:: Sub-Saharan Africa

            .. include:: rankings/spill2020afr.rst

   .. tab:: 2019

      .. tabs::

         .. tab:: All regions

            .. include:: rankings/spill2019all.rst

         .. tab:: East and South Asia

            .. include:: rankings/spill2019esa.rst

         .. tab:: Eastern Europe and Central Asia

            .. include:: rankings/spill2019eeca.rst

         .. tab:: Latin America and the Caribbean

            .. include:: rankings/spill2019lac.rst

         .. tab:: Middle East and North Africa

            .. include:: rankings/spill2019mena.rst

         .. tab:: OECD members

            .. include:: rankings/spill2019oecd.rst

         .. tab:: Oceania

            .. include:: rankings/spill2019oceania.rst

         .. tab:: Sub-Saharan Africa

            .. include:: rankings/spill2019afr.rst

   .. tab:: 2018

      .. tabs::

         .. tab:: All regions

            .. include:: rankings/spill2018all.rst

         .. tab:: East and South Asia

            .. include:: rankings/spill2018esa.rst

         .. tab:: Eastern Europe and Central Asia

            .. include:: rankings/spill2018eeca.rst

         .. tab:: Latin America and the Caribbean

            .. include:: rankings/spill2018lac.rst

         .. tab:: Middle East and North Africa

            .. include:: rankings/spill2018mena.rst

         .. tab:: OECD members

            .. include:: rankings/spill2018oecd.rst

         .. tab:: Oceania

            .. include:: rankings/spill2018oceania.rst

         .. tab:: Sub-Saharan Africa

            .. include:: rankings/spill2018afr.rst

   .. tab:: 2017

      .. tabs::

         .. tab:: All regions

            .. include:: rankings/spill2017all.rst

         .. tab:: East and South Asia

            .. include:: rankings/spill2017esa.rst

         .. tab:: Eastern Europe and Central Asia

            .. include:: rankings/spill2017eeca.rst

         .. tab:: Latin America and the Caribbean

            .. include:: rankings/spill2017lac.rst

         .. tab:: Middle East and North Africa

            .. include:: rankings/spill2017mena.rst

         .. tab:: OECD members

            .. include:: rankings/spill2017oecd.rst

         .. tab:: Oceania

            .. include:: rankings/spill2017oceania.rst

         .. tab:: Sub-Saharan Africa

            .. include:: rankings/spill2017afr.rst

