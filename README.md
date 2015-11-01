# Decoder-ByteRun
This is a decoder for ByteRun free online PHP encoder(http://www.byterun.com/free-php-encoder.php).

You can decode your byterun script into a much more readable format.

If you have seen like this code:
```
<?php  $_F=__FILE__;$_X='Pz48P3BocA0KICAgIDVjaDIgImg1bGwyIHcycmxkIjsNCj8+';eval(base64_decode('JF9YPWJhc2U2NF9kZWNvZGUoJF9YKTskX1g9c3RydHIoJF9YLCcxMjM0NTZhb3VpZScsJ2FvdWllMTIzNDU2Jyk7JF9SPWVyZWdfcmVwbGFjZSgnX19GSUxFX18nLCInIi4kX0YuIiciLCRfWCk7ZXZhbCgkX1IpOyRfUj0wOyRfWD0wOw=='));?>
```

Grab the value of $_X
In this case, it's
```
Pz48P3BocA0KICAgIDVjaDIgImg1bGwyIHcycmxkIjsNCj8+
```

Place this string into the first textbox and click the button to decode it.
You will get back the following string.
```
<?php
    echo "hello world";
?>
```
