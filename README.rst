
Biotuner
########

Python toolbox that incorporates tools from biological signal processing and musical theory to extract harmonic structures from biosignals.

.. image:: https://user-images.githubusercontent.com/49297774/153693263-90c1e49e-a8c0-4a93-8219-491d1ede32e1.jpg

Installation
##############

Create an environment with Python v3.8

.. code-block:: console

    conda create -n biotuner python=3.8
    conda activate biotuner
    pip install biotuner


Simple use case
################

.. code-block:: python
    
    biotuning = biotuner(sf = 1000) #initialize the object
    biotuning.peaks_extraction(data, peaks_function='FOOOF') #extract spectral peaks
    biotuning.compute_peaks_metrics() #get consonance metrics for spectral peaks


Documentation
##############

.. image:: https://user-images.githubusercontent.com/49297774/156813349-ddcd40d0-57c9-41f2-b62a-7cbb4213e515.jpg
