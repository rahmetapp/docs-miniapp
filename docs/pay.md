## Оплата 
- Создать заказ через метод [здесь](https://rahmetpay.readthedocs.io/en/latest/order/) 
- Полученный url из ответа отправить в метод RahmetApp.pay(url), который определен в нативном приложении.
- И дождаться ответа в методах(которые определены в Mini App):
    - *RahmetWebApp.onPaySuccess()*, при успешной оплате;
    - *RahmetWebApp.onNativePayViewClosed()*, при отмене оплаты;
