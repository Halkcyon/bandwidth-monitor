bandwidth-monitor
=================
A wrapper for |speedtest|_ to get time-series data on local bandwidth
availability.

As a default, the scheduler will run hourly at the top of the hour and store
output in a local ``sqlite3`` database named ``bandwidth.db``.

Inspired by |@jsphWllng|_'s article `"Monitor your internet with python"
<https://pythonprogramming.org/monitor-your-internet-with-python/>`_.

Usage
=====

.. code-block:: bash

	$ pip install --user git+https://github.com/mburszley/bandwidth-monitoring.git@main#egg=bandwidth-monitor
	$ python -m bandwidth_monitor

..
	a terrible hack: https://docutils.sourceforge.io/FAQ.html#is-nested-inline-markup-possible

.. |speedtest| replace:: ``speedtest.net``
.. _speedtest: https://www.speedtest.net/

.. |@jsphWllng| replace:: ``@jsphWllng``
.. _@jsphWllng: https://pythonprogramming.org/jsphwllng/
