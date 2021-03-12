23 - Auto Exposure on ROI
=========================

This example shows how to dynamically set the Auto Exposure (AE) of the RGB camera dynamically, during application runtime,
based on bounding box position

Demo
####

.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/kibc8xHw8HI" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
    </div>

Setup
#####

Please run the following command to install the required dependencies

.. code-block:: python
   :substitutions:

   python3 -m pip install -U depthai opencv-python


For additional information, please follow :ref:`Python API installation guide <Installation - Python>`

This example also requires MobilenetSDD blob (:code:`mobilenet.blob` file) to work - you can download it from
`here <https://artifacts.luxonis.com/artifactory/luxonis-depthai-data-local/network/mobilenet.blob>`__

Source code
###########

Also `available on GitHub <https://github.com/luxonis/depthai-python/blob/main/examples/23_autoexposure_roi.py>`__

.. literalinclude:: ../../../examples/23_autoexposure_roi.py
   :language: python
   :linenos:

.. include::  /includes/footer-short.rst
