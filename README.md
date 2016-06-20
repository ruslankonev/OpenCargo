# Freights API
#### агрегатор ставок для расчета международных грузоперевозок

## Расчет стоимости перевозки
```
/api/calculate
```
Для осуществления расчета стоимости грузоперевозки необходимо обратиться с POST-запросом по адресу **`/api/calculate`** с указанием `Content-Type: application/json` и содержанием следующих параметров запроса в теле сообщения:
```
{
	"senderPointLat": 0.00,
	"senderPointLng": 0.00,
	"receiverPointLat": 0.00,
	"receiverPointLng": 0.00,
	"pointFrom": "",
	"pointTo": "",
	"volume": 80,
	"weight": 20000,
} 

```
