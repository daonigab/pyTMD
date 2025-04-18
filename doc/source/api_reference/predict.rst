=======
predict
=======

- Predict tidal values using harmonic constants

  * At a single time (``map``) such as for imagery
  * Multiple times and locations (``drift``) such as for airborne and satellite altimetry
  * Time series at a location (``time_series``) such as to compare with tide gauges

- Predicts tidal values from minor constituents inferred using major constituents
- Predicts long-period equilibrium ocean tides
- Predicts solid earth tides

Calling Sequence
----------------

.. code-block:: python

    import pyTMD.predict
    ht = pyTMD.predict.time_series(time, hc, con)

`Source code`__

.. __: https://github.com/pyTMD/pyTMD/blob/main/pyTMD/predict.py

.. autofunction:: pyTMD.predict.map

.. autofunction:: pyTMD.predict.drift

.. autofunction:: pyTMD.predict.time_series

.. autofunction:: pyTMD.predict.infer_minor

.. autofunction:: pyTMD.predict._infer_short_period

.. autofunction:: pyTMD.predict._infer_semi_diurnal

.. autofunction:: pyTMD.predict._infer_diurnal

.. autofunction:: pyTMD.predict._infer_long_period

.. autofunction:: pyTMD.predict.equilibrium_tide

.. autofunction:: pyTMD.predict.load_pole_tide

.. autofunction:: pyTMD.predict.ocean_pole_tide

.. autofunction:: pyTMD.predict.solid_earth_tide

.. autofunction:: pyTMD.predict._out_of_phase_diurnal

.. autofunction:: pyTMD.predict._out_of_phase_semidiurnal

.. autofunction:: pyTMD.predict._latitude_dependence

.. autofunction:: pyTMD.predict._frequency_dependence_diurnal

.. autofunction:: pyTMD.predict._frequency_dependence_long_period

.. autofunction:: pyTMD.predict._free_to_mean
