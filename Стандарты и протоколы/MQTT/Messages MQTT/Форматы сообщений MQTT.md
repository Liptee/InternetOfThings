## CONNECT
![[Pasted image 20220521173146.png]]
С помощью сообщения **CONNECT** клиент запрашивает подключение к серверу. Первое сообщение, отправленное от клиента серверу должно быть сообщение **CONNECT**.

Сообщение **CONNECT** содержит [[Fixed Header]], [[Variable Header]], [[Payload]].

Поле [[Remaining Length]] содержит значение оставшейся длины сообщения (длина заголовка пременной длины (10 байт) + длина поля [[Payload]]). 

[[Variable Header]] сообщения CONNECT состоит из четырех полей: **[[Protocol Name]]**, **[[Protocol Level]]**, **[[Connect Flags]]**, **Keep Alive**.