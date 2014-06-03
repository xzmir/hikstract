hikstract
=========

Extracts videos recorded by Hikvision IP camera.


Configuration
-------------

All configuration is done inside `config.cfg`. Edit this file to suit your needs:

    [main]

    # The directory, which the camera writes to
    data_dir = 

    # Output directory for extracted recordings
    output_dir = 

    # Debug logging
    debug = off

    # Additionally, extract a frame this many seconds into the recording
    # Set to negative value to disable
    snapshot_seek = 10


Usage
-----

Simply run `hikstract` from the command line.
