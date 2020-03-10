# spring-cloud-gateway-hystrix

# standard-json

[![npm][npm-image]][npm-url]
[![travis][travis-image]][travis-url]

API-GateWay
-----------
URL : http://localhost:8080/ms1/orders
HTTP Method : POST

Json Request :
```json
{
	"order":{
		"id":103,
		"name":"Mobile",
		"qty":1,
		"price":8000
		
	},
	"payment":{},
	"userName":"Basant",
	"email":"bh@gmail.com"
}
```
Json Response :
```json
{
    "order": {
        "id": 103,
        "name": "Mobile",
        "qty": 1,
        "price": 8000
    },
    "transactionId": "d86cfeca-0b26-455e-a1a2-ac3e53707829",
    "userName": "Basant"
}

```
