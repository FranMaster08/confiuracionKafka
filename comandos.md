 ### Creación de Topics
 ```
 kafka-topics --bootstrap-server kafka-broker-1:9092 --create --topic fran
 ```

### Envio de datos al topic

```
kafka-console-producer --bootstrap-server kafka-broker-1:9092 --topic fran
```


### Recepción de datos al topic

```
kafka-console-producer --bootstrap-server kafka-broker-1:9092 --topic fran
```
