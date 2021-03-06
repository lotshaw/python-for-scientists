

.. _sphx_glr__examples_plot_sns_heatmap.py:


Heatmap
=========

Example heatmap




.. image:: /_examples/images/sphx_glr_plot_sns_heatmap_001.png
    :align: center





.. code-block:: python

    import matplotlib.pyplot as plt
    import numpy as np
    import seaborn as sns

    np.random.seed(0)
    sns.set()

    # Data for plot
    uniform_data = np.random.rand(10, 12)

    # Plot heatmap
    ax = sns.heatmap(uniform_data)

**Total running time of the script:** ( 0 minutes  0.833 seconds)



.. only :: html

 .. container:: sphx-glr-footer


  .. container:: sphx-glr-download

     :download:`Download Python source code: plot_sns_heatmap.py <plot_sns_heatmap.py>`



  .. container:: sphx-glr-download

     :download:`Download Jupyter notebook: plot_sns_heatmap.ipynb <plot_sns_heatmap.ipynb>`


.. only:: html

 .. rst-class:: sphx-glr-signature

    `Gallery generated by Sphinx-Gallery <https://sphinx-gallery.readthedocs.io>`_
