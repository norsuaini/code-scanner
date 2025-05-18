 # QR-Code-Scanner

This Region Plug-in is used to scan codes. If any string has been detected an APEX Item can be set, Dynamic Action can be fired or JavaScript can be executed.
The following formats are supported: QR_CODE, AZTEC, CODABAR, CODE_39, CODE_93, CODE_128, DATA_MATRIX, MAXICODE, ITF, EAN_13, EAN_8, PDF_417, RSS_14, RSS_EXPANDED, UPC_A, UPC_E, UPC_EAN_EXTENSION

If you don't to know how to install this Plug-in in Apex, please take look at the Documentation of Oracle APEX.

To control the QR Code Scanner you can fire events on th QR Code region. The following events are supportet:

apex.region("region_id").pause(); => stop Scanner Video

apex.region("region_id").start(); => start Scanner video

apex.region("region_id").refresh(); => reset the currentValue and the item

apex.region("region_id").setFacingMode(); => change camera
