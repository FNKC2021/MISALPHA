Стандарт
=========================================

стандарт отделения - указывается в DEPARTMENTS
стандарт личный - заполняется DOCTOR
стандарт общий - DEPARTMENTS и DOCTOR не заполняется

::

	"STANDART":{
	            "ID": "",
	            "CODE": "",
	            "TYPE": "",
	            "NAME": "",
	            "DESCRIPTION": ""
	            "DEPARTMENTS":["DEPARTMENT_ID":""],
	            "DOCTORS":["DOCTOR_ID":""],
	            "MKB10S":["MKB10_ID":""],
	            "SERVICES":[{"SERVICE_ID":"", "COUNT":"1"}],
	           }

.. table::

  +-------------+-----------------------------------+-----------------+
  | ID          | Id стандарта                      | Number          |
  +-------------+-----------------------------------+-----------------+
  | CODE        | Код стандарта                     | String          |
  +-------------+-----------------------------------+-----------------+
  | TYPE        | Тип стандарта                     | String          |
  +-------------+-----------------------------------+-----------------+
  | NAME        | Наименование стандартра           | String          |
  +-------------+-----------------------------------+-----------------+
  | DESCRIPTION | Описание стандартра               | String          |
  +-------------+-----------------------------------+-----------------+
  | DEPARTMENTS | Отделения, использующие стандарт  | Rows of Objects |
  +-------------+-----------------------------------+-----------------+
  | DOCTORS     | Врачи, использующие стандарт      | Rows of Objects |
  +-------------+-----------------------------------+-----------------+
  | MKB10S      | Диагнозы, относящиеся к стандарту | Rows of Objects |
  +-------------+-----------------------------------+-----------------+
  | SERVICES    | Услуги, входящие в стандарт       | Rows of Objects |
  +-------------+-----------------------------------+-----------------+
  | COUNT       | Кол-во вхождений услуги в стандарт| Rows of Objects |
  +-------------+-----------------------------------+-----------------+

стандарт отделения - указывается в DEPARTMENTS
стандарт личный - заполняется DOCTOR
стандарт общий - DEPARTMENTS и DOCTOR не заполняется