# ESP32 Jammer
<p>The device is a multi-functional jammer designed to disrupt wireless communication across a variety of frequencies, including 2.4GHz broadband, Bluetooth, and remote control (RC) signals. It works by emitting a wide-band noise signal that interferes with the targeted frequency ranges, rendering devices operating on these frequencies ineffective. The jammer is capable of blocking common Wi-Fi networks operating in the 2.4GHz band, Bluetooth connections used for short-range communication, as well as controlling devices like RC cars, drones, and other remote-controlled gadgets. With its compact design, this jammer is highly effective in areas where wireless communication needs to be interrupted or prevented, ensuring that devices relying on these frequencies become inoperable within a radius of 30m.</p>

![IMG_0097 (1)](https://github.com/user-attachments/assets/3f2474b4-8632-43ad-9fc6-dd3d6c00ee1b)
![IMG_0080 (1)](https://github.com/user-attachments/assets/7278e68d-2f59-4723-91ac-e92a19350350)
![68747470733a2f2f64776477706c642e70616765732e6465762f45535033322d426c75654a616d6d6572427940656d656e7374612e6a7067](https://github.com/user-attachments/assets/d64c5610-a4a5-4af5-9df6-9373b230e8a4)

# Parts

  [Resistor](https://pl.aliexpress.com/item/1005007987815579.html?aff_fcid=1e343476a15f43959b9e5f1eca4ca941-1741732129651-05363-_oBV1Q1Z&tt=CPS_NORMAL&aff_fsk=_oBV1Q1Z&aff_platform=shareComponent-detail&sk=_oBV1Q1Z&aff_trace_key=1e343476a15f43959b9e5f1eca4ca941-1741732129651-05363-_oBV1Q1Z&terminal_id=5bcfda95327e49539b9b6782303a1b72&afSmartRedirect=y) 4.7k Ohm<br />
  [Status Led: 3 mm LED](https://pl.aliexpress.com/item/1005006898362384.html?spm=a2g0o.order_list.order_list_main.16.42211c24tHlYuV&gatewayAdapt=glo2pol)<br />
  [JST PH 2.0 Cables and Connectors](https://pl.aliexpress.com/item/32665588344.html?spm=a2g0o.order_list.order_list_main.21.42211c24tHlYuV&gatewayAdapt=glo2pol)<br />
  [Switch Handle length 4mm](https://pl.aliexpress.com/item/4001207529493.html?spm=a2g0o.order_list.order_list_main.26.42211c24tHlYuV&gatewayAdapt=glo2pol)<br />
  [Battery](https://pl.aliexpress.com/item/1005008060921977.html?spm=a2g0o.order_list.order_list_main.31.42211c24tHlYuV&gatewayAdapt=glo2pol)<br />
  [TP4056 Charging Module Micro-USB](https://pl.aliexpress.com/item/1005008071836461.html?spm=a2g0o.order_list.order_list_main.37.42211c24tHlYuV&gatewayAdapt=glo2pol)<br />
  [Optional 3rd antenna for better range](https://pl.aliexpress.com/item/1005007039901040.html?spm=a2g0o.order_list.order_list_main.42.42211c24tHlYuV&gatewayAdapt=glo2pol)<br />
  [PCB 7x9cm](https://pl.aliexpress.com/item/32888385898.html?spm=a2g0o.order_list.order_list_main.47.42211c24tHlYuV&gatewayAdapt=glo2pol) You will need to cut it down to 7x5,5cm because of the fitment to the case designed by @emensta<br />
  [10uF Capacitor](https://pl.aliexpress.com/item/1005002524973878.html?spm=a2g0o.order_list.order_list_main.52.42211c24tHlYuV&gatewayAdapt=glo2pol) (2x) (any voltage above 5V)<br />
  [NRF24L01 PA](https://pl.aliexpress.com/item/1005007142575123.html?spm=a2g0o.order_list.order_list_main.57.42211c24tHlYuV&gatewayAdapt=glo2pol) (2x)<br />
  [ESP32 Dev Module](https://pl.aliexpress.com/item/1005006613312645.html?spm=a2g0o.order_list.order_list_main.62.42211c24tHlYuV&gatewayAdapt=glo2pol) Recommended: ESP32-32U CP2102<br />
  [M3 screws&nuts kit for the case](https://pl.aliexpress.com/item/1005002855686647.html?aff_fcid=6a3cf658a8c7443480b183b7236a4a21-1741732689780-09433-_oC24YXH&tt=CPS_NORMAL&aff_fsk=_oC24YXH&aff_platform=shareComponent-detail&sk=_oC24YXH&aff_trace_key=6a3cf658a8c7443480b183b7236a4a21-1741732689780-09433-_oC24YXH&terminal_id=5bcfda95327e49539b9b6782303a1b72&afSmartRedirect=y)

