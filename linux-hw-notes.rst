
Linux Hardware Notes
====================

General troubleshooting commands
--------------------------------

.. code::bash

   $ hwinfo --usb
   $ lsusb
   $ lspci
   # lsmod
   # modprobe SOME_MODULE_NAME


Latitude 7490
-------------

Integrated webcam not working:

.. code::bash

    # modprobe uvcvideo

Speakers not working:

.. code::bash

   # modprobe snd_hda_intel

