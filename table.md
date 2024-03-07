|       FIELD        |  DATA TYPE   |             ATTRIBUTES             |    INDEX    |
| :----------------: | :----------: | :--------------------------------: | :---------: |
|         id         |   SMALLINT   | not null - unique - auto_increment | primary key |
|       brand        | VARCHAR(50)  |              not null              |             |
|       model        | VARCHAR(50)  |              not null              |             |
|      fullName      |     TEXT     |   null - default (brand + model)   |             |
|      carType       | VARCHAR(50)  |   not null - default ('berlina')   |             |
|       doorsN       |   TINYINT    |      not null - default ('3')      |             |
|       price        | DECIMAL(8,2) |              not null              |             |
|  registrationDate  |     DATE     |              not null              |             |
|         km         |  FLOAT(8,2)  |    not null - default (30.000)     |             |
|        fuel        | VARCHAR(20)  |              not null              |             |
|  fuelConsumption   |  FLOAT(3,1)  |                null                |             |
|   urbanFuelCons    |  FLOAT(3,1)  |                null                |             |
| extraUrbanFuelCons |  FLOAT(3,1)  |                null                |             |
| methaneConsumption |  FLOAT(3,1)  |                null                |             |
|    CO2Emissions    |  FLOAT(3,1)  |                null                |             |
| newDriversFriendly |   TINYINT    |                null                |             |
