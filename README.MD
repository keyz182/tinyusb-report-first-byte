Logs from `hidtest.py`

```bash
python .\hidtest.py
Openning HID device with VID = 0x239A
{'path': b'\\\\?\\hid#vid_239a&pid_80cb&mi_02#7&327e8028&0&0000#{4d1e55b2-f16f-11cf-88cb-001111000030}', 
'vendor_id': 9114, 'product_id': 32971, 'serial_number': 'AC25E7CA50533434372E3120FF0D2D28', 'release_number': 
256, 'manufacturer_string': 'Adafruit', 'product_string': 'QT Py M0', 'usage_page': 65280, 'usage': 1, 
'interface_number': 2}
Send text to HID Device : abc
Sending 'b'abc''
Received from HID Device: 
b'bc\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00'
```
