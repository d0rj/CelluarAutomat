# ⬛⬜ Celluar automat

## Описание

Простое приложение для изучения клеточных автоматов, в частности игры "Жизнь". В настоящее время только её и поддерживает.

Поле является развёрткой тора.

## Окружение

* numpy
* tkinter


## Использование

```bash
python main.py
```

### Управление

* Step - просчитать одну итерацию автомата;
* Clear - очистить поле;
* Random - заполнить поле случайным образом;
* Simulate - просчитывать состояние автомата до сигнала остановки;
* Клик на поле - включить/выключить клетку.
* Log - начать/закончить логгирование. Логи сохраняются в папку 'default' (редактирование названия пока не поддерживается) и подписываются своим порядковым номером относительно начала записи.

## Roadmap

* Быстрая смена правил перехода автомата;
* Интерфейс покрасивее xD;
* Добавление множества известных конфигураций;
* Одномерный режим;
* Более удобная работа с логами.
