From biosignals to music
=========================

This is a simple example of how to use the biotuner package to derive a set of peaks from biosignals to be used as a tuning.


.. code-block:: python

    import biotuner as bt
    import numpy as np
    import matplotlib.pyplot as plt
    # Generate a signal
    fs = 1000
    t = np.arange(0, 10, 1/fs)
    x = np.sin(2*np.pi*10*t) + np.sin(2*np.pi*20*t)
    # Plot the signal
    plt.figure(figsize=(10, 5))
    plt.plot(t, x)
    plt.xlabel('Time (s)')
    plt.ylabel('Amplitude')
    plt.show()
