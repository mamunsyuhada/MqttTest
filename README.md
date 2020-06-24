# MQTT Android Client with Auth (Username & Pass)

## Need to modified

Parameter|Example Value|
---------|-------------|
[Host](https://github.com/mamunsyuhada/MqttTest/blob/master/app/src/main/java/com/example/mqtttest/MainActivity.java#L27)|tcp://```yourhost.com```:```port```|
[Username](https://github.com/mamunsyuhada/MqttTest/blob/master/app/src/main/java/com/example/mqtttest/MainActivity.java#L44)|```User:*:*```|
[Password](https://github.com/mamunsyuhada/MqttTest/blob/master/app/src/main/java/com/example/mqtttest/MainActivity.java#L45)|```Admin:*:*```|

## Dependencies Used

[Paho MQTT](https://github.com/eclipse/paho.mqtt.android)

```gradle
implementation 'org.eclipse.paho:org.eclipse.paho.client.mqttv3:1.2.2'
implementation 'org.eclipse.paho:org.eclipse.paho.android.service:1.1.1'
```

## Troubleshooting

- [add local broadcast manager depedency](https://stackoverflow.com/questions/51097099/can-not-resolve-import-localbroadcastmanager-on-statement-android-support-v4-con)

## Demo


