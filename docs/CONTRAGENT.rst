Контрагент
===========================

::

	"CONTRAGENT":{
		      "ID": "",
		      "NAME": "",
		      "TYPE": "",
		      "INN": "",
		      "ADDRESS": "",
		      "IN_DATE":	     
		      "INSTANCE_CODE": "", 
		      "AGREEMENTS": [ "AGREEMENT_ID":"" ]
		     }

.. table::

  +---------------+--------------------------------+--------+
  | ID            | Id контрагента                 | Number |
  +---------------+--------------------------------+--------+
  | NAME          | Наименование контрагента       | Number |
  +---------------+--------------------------------+--------+
  | TYPE	  | Тип контрагента                | String |
  +---------------+--------------------------------+--------+
  | INN           | ИНН контрагента                | String |
  +---------------+--------------------------------+--------+
  | ADRESS        | Юр.адрес контрагента           | String |
  +---------------+--------------------------------+--------+
  | IN_DATE       | Дата создания контрагента      | String |
  +---------------+--------------------------------+--------+
  | INSTANCE_CODE | Код компоненты                 | String |
  +---------------+--------------------------------+--------+
  | AGREEMENTS    | Массив AGREEMENT_ID (Договоры) | Rows   |
  +---------------+--------------------------------+--------+	

