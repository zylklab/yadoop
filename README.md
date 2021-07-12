## Playbooks list
 * Base (Users and Groups)
 * Zookeeper (Service)
 * HDFS
 * YARN
 * TEZ
 * HIVE


Also, it is important to keep in mind the Processor Scheduling Configuration. Using the parameter **Run Schedule** (for example to *1 sec*), the reading frequency can be set. Note that by default, this value is defined to 0 sec (as fast as possible).

Table of data mapping between plc data and avro

| PLC type | Avro Type |
|----------|-----------|
| PlcBigDecimal | floatType |
| PlcBigInteger | longType |
| PlcBitString | stringType |
| PlcBOOL | booleanType |
| PlcBYTE | stringType |
| PlcCHAR | stringType |
| PlcDATE_AND_TIME | stringType |
| PlcDATE | stringType |
| PlcDINT | stringType |
| PlcDWORD | stringType |
| PlcINT | intType |
| PlcLINT | stringType |
| PlcList | stringType |
| PlcLREAL | stringType |
| PlcLTIME | stringType |
| PlcLWORD | stringType |
| PlcNull | stringType |
| PlcREAL | doubleType |
| PlcSINT | intType |
| PlcSTRING | stringType |
| PlcStruct | stringType |
| PlcTIME_OF_DAY | stringType |
| PlcTIME | stringType |
| PlcUDINT | stringType |
| PlcUINT | stringType |
| PlcULINT | stringType |
| PlcUSINT | stringType |
| PlcWCHAR | stringType |
| PlcWORD | stringType |
| ELSE | stringType |
