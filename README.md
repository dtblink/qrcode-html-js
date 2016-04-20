HTML / Javascript - How to show a QRCode

Edit sample.html, 
you just need to fill the QRCode content in the variable QRCODE_CONTENT

        var show_qrcode = function () {
            var form = document.forms['qrForm'];

            var QRCODE_CONTENT = 'QRCode Content generated on step 1';

            document.getElementById('qr').innerHTML = create_qrcode(QRCODE_CONTENT);
        };
