# Temperature Sensors

An nRF52840-based Zigbee temperature sensor for use with ESPHome, designed for efficiency

![](/assets/image.png)

## Bill of Materials

|Name                        |Quantity needed|MOQ|Price |Quantity to order|Link                                                                                           |Total    |
|----------------------------|---------------|---|------|-----------------|-----------------------------------------------------------------------------------------------|---------|
|2450AT43F0100001E           |1              |1  |1.1034|1                |https://www.lcsc.com/product-detail/C17192881.html                                             |1.1034   |
|32.768k crystal             |1              |5  |0.2553|5                |https://www.lcsc.com/product-detail/C46257428.html                                             |1.2765   |
|32M crystal                 |1              |10 |0.0564|10               |https://www.lcsc.com/product-detail/C42464320.html                                             |0.564    |
|1pF cap                     |1              |100|0.0085|100              |https://www.lcsc.com/product-detail/C5137611.html                                              |0.85     |
|1.2pF cap                   |1              |100|0.0038|100              |https://www.lcsc.com/product-detail/C1638.html                                                 |0.38     |
|20pF cap                    |2              |100|0.0089|100              |https://www.lcsc.com/product-detail/C5137583.html                                              |0.89     |
|10uF cap                    |3              |50 |0.083 |50               |https://www.lcsc.com/product-detail/C1691.html                                                 |4.15     |
|1uF cap                     |1              |50 |0.0217|50               |https://www.lcsc.com/product-detail/C29936.html                                                |1.085    |
|100pF cap                   |2              |50 |0.0174|50               |https://www.lcsc.com/product-detail/C576846.html                                               |0.87     |
|47nF cap                    |1              |100|0.0077|100              |https://www.lcsc.com/product-detail/C576852.html                                               |0.77     |
|100nF cap                   |5              |50 |0.0179|50               |https://www.lcsc.com/product-detail/C5137636.html                                              |0.895    |
|100uF cap                   |1              |5  |0.3214|5                |https://www.lcsc.com/product-detail/C521072.html                                               |1.607    |
|1nF cap                     |1              |100|0.0049|100              |https://www.lcsc.com/product-detail/C17702741.html                                             |0.49     |
|10pF can                    |1              |100|0.0059|100              |https://www.lcsc.com/product-detail/C1634.html                                                 |0.59     |
|Green LED                   |1              |1  |0.29  |1                |https://www.digikey.com/en/products/detail/sunled/XZVG53W-8/4745971                            |0.29     |
|Red LED                     |1              |1  |0.27  |1                |https://www.digikey.com/en/products/detail/sunled/XZMDK53W-8/4745952                           |0.27     |
|Diodes                      |4              |50 |0.0112|50               |https://www.lcsc.com/product-detail/C191023.html                                               |0.56     |
|JST S3B-PH-SM4-TB           |2              |1  |0.57  |2                |https://www.digikey.com/en/products/detail/jst-sales-america-inc/S3B-PH-SM4-TB/926656          |1.14     |
|JST S2B-PH-SM4-TB           |1              |5  |0.2055|5                |https://www.lcsc.com/product-detail/C295747.html                                               |1.0275   |
|4.7nH inductor              |1              |5  |0.0863|5                |https://www.lcsc.com/product-detail/C2043858.html                                              |0.4315   |
|2.2nH inductor              |1              |10 |0.0785|10               |https://www.lcsc.com/product-detail/C412264.html                                               |0.785    |
|10uH inductor               |1              |10 |0.0564|10               |https://www.lcsc.com/product-detail/C76798.html                                                |0.564    |
|15nH inductor               |1              |20 |0.0666|20               |https://www.lcsc.com/product-detail/C98055.html                                                |1.332    |
|AO3401A (PMOS)              |3              |20 |0.0371|20               |https://www.lcsc.com/product-detail/C347476.html                                               |0.742    |
|1M resistor                 |3              |100|0.0037|100              |https://www.lcsc.com/product-detail/C2907003.html                                              |0.37     |
|10k resistor                |2              |100|0.0057|100              |https://www.lcsc.com/product-detail/C844918.html                                               |0.57     |
|5.1k resistor               |2              |100|0.0028|100              |https://www.lcsc.com/product-detail/C2907044.html                                              |0.28     |
|100k resistor               |1              |100|0.0025|100              |https://www.lcsc.com/product-detail/C2907088.html                                              |0.25     |
|300 resistor                |2              |100|0.0029|100              |https://www.lcsc.com/product-detail/C2930092.html                                              |0.29     |
|560k resistor               |1              |100|0.0025|100              |https://www.lcsc.com/product-detail/C23203.html                                                |0.25     |
|180k resistor               |1              |100|0.0027|100              |https://www.lcsc.com/product-detail/C2906999.html                                              |0.27     |
|TS-1088-AR02016 (pushbutton)|1              |10 |0.0557|10               |https://www.lcsc.com/product-detail/C720477.html                                               |0.557    |
|CHS-01B1 (slide switch)     |1              |1  |0.7583|1                |https://www.lcsc.com/product-detail/C3312309.html                                              |0.7583   |
|NTC themistor               |1              |10 |0.0597|10               |https://www.lcsc.com/product-detail/C3152998.html                                              |0.597    |
|nRF52840-QFAA-F-R7          |1              |1  |6.54  |1                |https://www.digikey.com/en/products/detail/nordic-semiconductor-asa/NRF52840-QFAA-F-R7/15929801|6.54     |
|TP4057                      |1              |10 |0.0413|10               |https://www.lcsc.com/product-detail/C725791.html                                               |0.413    |
|TPS63051RMWR                |1              |1  |1.022 |1                |https://www.lcsc.com/product-detail/C139412.html                                               |1.022    |
|SN74LVC1G00DCKR (inverter)  |1              |10 |0.0299|10               |https://www.lcsc.com/product-detail/C19829626.html                                             |0.299    |
|                            |               |   |      |                 |                                                                                               |         |
|PCB                         |1              |1  |2     |1                |https://cart.jlcpcb.com/quote                                                                  |2        |
|                            |               |   |      |                 |                                                                                               |         |
|JLCPCB shipping             |               |   |      |                 |                                                                                               |3.12     |
|LCSC shipping               |               |   |      |                 |                                                                                               |10.76    |
|Digikey shipping            |               |   |      |                 |                                                                                               |$4.99    |
|                            |               |   |      |                 |                                                                                               |         |
|Subtotal                    |               |   |      |                 |                                                                                               |55.9992  |
|Total                       |               |   |      |                 |                                                                                               |60.619134|

## Production notes

The layer stackup should be JLC0616H-3313.
