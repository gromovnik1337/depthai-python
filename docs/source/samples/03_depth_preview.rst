03 - Depth Preview
==================

This example shows how to set the SGBM (semi-global-matching) disparity-depth node, connects
over XLink to transfer the results to the host real-time, and displays the depth map in OpenCV.
Note that disparity is used in this case, as it colorizes in a more intuitive way.

Demo
####

.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/7oDjG-s-88Y" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
    </div>

Setup
#####

.. include::  /includes/install_from_pypi.rst

Source code
###########

Also `available on GitHub <https://github.com/luxonis/depthai-python/blob/main/examples/03_depth_preview.py>`__

.. literalinclude:: ../../../examples/03_depth_preview.py
   :language: python
   :linenos:

.. include::  /includes/footer-short.rst
