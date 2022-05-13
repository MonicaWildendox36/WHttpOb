# WHttpOb
Global $o_WHttpObj = ObjCreate("MSXML2.ServerXMLHTTP.6.0") Local $oEventObject = ObjEvent($o_WHttpObj, "__Event")  With $o_WHttpObj   .Open("GET", $o_BUrl, True)   .Send()   ...... EndWith
