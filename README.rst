Python Libraries
============

Assorted python libraries and tools

.. image:: https://api.travis-ci.org/pkittenis/pythonlibraries.png?branch=master
	:target: https://travis-ci.org/pkittenis/pythonlibraries

************
threadpool
************
Producer/consumer style thread pool implementation

************
Usage Example
************

>>> from threadpool import ThreadPool
>>> tp = ThreadPool()
>>> tp.add_task_to_queue(sum, [1, 2])
>>> tasks = range(0, 1)
>>> results = tp.get_results(tasks)
