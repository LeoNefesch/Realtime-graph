This is fork from https://github.com/mhhabib/Realtime-graph

Библиотека channels устанавливается вместе с daphne, по [документации](https://channels.readthedocs.io/en/latest/installation.html):
```commandline
python -m pip install -U 'channels[daphne]'
```
Все необходимые библиотеки ( attrs-23.1.0 autobahn-23.6.2 automat-22.10.0 cffi-1.16.0 channels-4.0.0 constantly-23.10.4 cryptography-41.0.7 daphne-4.0.0 hyperlink-21.0.0
idna-3.6 incremental-22.10.0 pyasn1-0.5.1 pyasn1-modules-0.3.0 pycparser-2.21 pyopenssl-23.3.0 service-identity-23.1.0 six-1.16.0 twisted-23.10.0 twisted-iocpsupport-1.0.4 txaio-23.1.1 typing-extensions-4.9.0 zope-interface-6.1)
устанавливаются подтягиваются при выполнении этой команды. Их в requirements.txt прописывать не нужно! Версии обновятся, и будут конфликты зависимостей.

В проекте используется:
- msgpack - библиотека для двоичной сериализации. Он позволяет обмениваться данными на нескольких языках, например JSON.
- async-timeout - asyncio-совместимый контекстный менеджер для таймаута.