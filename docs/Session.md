# Описание класса Session
Класс для работы с сеансами тату-салона.

## Атрибуты

* Cabinet:[Cabinet](https://github.com/To4ilko1/TatooParlor/blob/master/docs/Cabinet.md "объект класса Cabinet")
* ID:Int
* Client:[Client](https://github.com/To4ilko1/TatooParlor/blob/master/docs/Client.md "объект класса Client")
* Date:DateTime
* Services:List<[Service](https://github.com/To4ilko1/TatooParlor/blob/master/docs/Service.md "объект класса Service")>
* Workers:List<[Worker](https://github.com/To4ilko1/TatooParlor/blob/master/docs/Worker.md "объект класса Worker")>

## Описание атрибутов

* Cabinet:[Cabinet](https://github.com/To4ilko1/TatooParlor/blob/master/docs/Cabinet.md "объект класса Cabinet") - кабинет, в котором проходит сеанс.
* ID:Int - идентификатор в БД.
* Client:[Client](https://github.com/To4ilko1/TatooParlor/blob/master/docs/Client.md "объект класса Client") - клиент.
* Date:DateTime - дата сеанса.
* Services:List<[Service](https://github.com/To4ilko1/TatooParlor/blob/master/docs/Service.md "объект класса Service")> - список услуг сеанса.
* Workers:List<[Worker](https://github.com/To4ilko1/TatooParlor/blob/master/docs/Worker.md "объект класса Worker")> - список работников.