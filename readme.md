# name of the table : cars

table columns:

-ID
    BIGINT -PRIMARY KEY - AUTO INCREMENT - UNIQUE
-vin
    VARCHAR 17 - UNIQUE - NULL
-license_plate 
    CHAR 7  - UNIQUE - NULL
-price
    DECIMAL 10, 2 - NOT NULL - INDEX
-is available
    TINYINT - DEFAULT 0 - INDEX
-model
    VARCHAR 50 - NOT NULL - INDEX
-year
    YEAR - NOT NULL - INDEX
-mileage
    INT - DEFAULT 0 - INDEX
-fuel_type
    TINYINT - NOT NULL - INDEX (see legend to combine number with fuel system)
-transmission
    TINYINT - NOT NULL - INDEX (0 MANUAL - 1 AUTOMATIC)
-status
    TINYINT - NOT NULL - INDEX (RATE STATUS FROM 0 TO 5)
-engine
    SMALLINT - NULL
-horsepower
    SMALLINT - NULL 
-emission_class
    TINYINT - NULL
-avg_consumption
    DECIMAL 6, 2 - NULL
-battery_capacity
    SMALLINT - NULL
-color
    VARCHAR 20 - NULL
-doors
    TINYINT - NULL
-seats
    TINYINT - NULL
-gps
    TINYINT - NULL
-cruise_control
    TINYINT - NULL
-parking_sensors
    TINYINT - NULL
-location
    VARCHAR 50 - NOT NULL
-description
    TEXT - NULL
-other_features
    TEXT - NULL