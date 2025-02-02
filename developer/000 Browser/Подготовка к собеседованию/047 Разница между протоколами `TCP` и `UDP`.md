![Разница между протоколами `TCP` и `UDP`?](https://youtu.be/trriSYNrHw4?t=234)

#### Ответ

![[Pasted image 20230703191224.png|600]]

*TCP* (Transmission Control Protocol) и *UDP* (User Datagram Protocol) - это два основных протокола передачи данных в сетях TCP/IP. Они отличаются друг от друга по нескольким параметрам.

1. *Надежность доставки данных:* TCP обеспечивает надежную доставку данных, проверяя, что каждый пакет данных был успешно доставлен и при необходимости повторно отправляя потерянные пакеты. UDP, с другой стороны, не предоставляет такую надежность - он просто отправляет пакеты данных и не проверяет, были ли они успешно доставлены.
2. *Установка соединения:* TCP использует трехстороннее рукопожатие для установки соединения между двумя устройствами. UDP не устанавливает соединение, а просто отправляет пакеты данных без предварительной настройки.
3. *Скорость передачи данных:* UDP быстрее, чем TCP, так как он не тратит время на установку соединения и проверку надежности доставки. Однако, так как TCP обеспечивает надежность, он может быть медленнее, особенно при передаче больших объемов данных.
4. *Размер пакета данных:* TCP разбивает данные на пакеты фиксированного размера, в то время как UDP может отправлять пакеты любого размера до максимально допустимого размера в сети.
5. *Применение:* TCP чаще используется для передачи данных, которые требуют надежной доставки, таких как веб-страницы, файлы и электронная почта. UDP чаще используется для приложений, где скорость передачи данных более важна, чем надежность доставки, таких как потоковое видео и онлайн-игры.

Важно отметить, что выбор между TCP и UDP должен основываться на требованиях конкретного приложения и учитывать особенности сети, через которую передаются данные.

[TCP против UDP или будущее сетевых протоколов](https://habr.com/ru/companies/oleg-bunin/articles/461829/)

___
#TCP #UPD #TCP/IP 

___

#### [[000 Browser|Назад]]