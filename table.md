|         FIELD          |  DATA TYPE   |             ATTRIBUTES             |    INDEX    |
| :--------------------: | :----------: | :--------------------------------: | :---------: |
|           id           |   SMALLINT   | not null - unique - auto_increment | primary key |
|         brand          | VARCHAR(50)  |              not null              |             |
|         model          | VARCHAR(50)  |              not null              |             |
|       full name        |     TEXT     |   null - default (brand + model)   |             |
|        car type        | VARCHAR(50)  |   not null - default ('berlina')   |             |
|        doors n         |   TINYINT    |      not null - default ('3')      |             |
|         price          | DECIMAL(8,2) |              not null              |             |
|   registration date    |     DATE     |              not null              |             |
|           km           |  FLOAT(8,2)  |    not null - default (30.000)     |             |
|          fuel          | VARCHAR(20)  |              not null              |             |
|    fuel consumption    |  FLOAT(3,1)  |                null                |             |
|    urban fuel cons.    |  FLOAT(3,1)  |                null                |             |
| extra urban fuel cons. |  FLOAT(3,1)  |                null                |             |
|     CO2 emissions      |  FLOAT(3,1)  |                null                |             |
|  methane consumption   |  FLOAT(3,1)  |                null                |             |
|  new drivers friendly  |   BOOLEAN    |                null                |             |
