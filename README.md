# 1C-module
КупиПродай_Конфигурация/

├── src/

│   ├── Configuration.xml   Основной файл конфигурации (в формате XML)

│   ├── Configuration.cf                 Альтернативно: бинарный файл конфигурации

│   └── Configuration.mxl                Метаданные конфигурации (если используется)

├── Ext/

│   └── ExternalDataSource/             Внешние источники данных (если есть)

├── Subsystems/

│   ├── Ценообразование/

│   │   ├── Documents/

│   │   │   └── УстановкаЦен/

│   │   │       ├── Object.xml

│   │   │       ├── Form.xml

│   │   │       └── Module.bsl

│   │   ├── Reports/

│   │   │   └── ПрайсЛист/

│   │   │       ├── Report.xml

│   │   │       └── DataCompositionSchema.xml

│   │   └── Metadata.xml

│   ├── Закупки/

│   │   ├── Documents/

│   │   │   └── ПоступлениеТоваров/

│   │   │       ├── Object.xml

│   │   │       ├── Form.xml

│   │   │       └── Module.bsl

│   │   ├── Reports/

│   │   │   └── ОстаткиТоваров/

│   │   │       ├── Report.xml

│   │   │       └── DataCompositionSchema.xml

│   │   └── Metadata.xml

│   └── Продажи/

│       ├── Documents/

│       │   └── РеализацияТоваров/

│       │       ├── Object.xml

│       │       ├── Form.xml

│       │       └── Module.bsl

│       ├── Reports/

│       │   └── ОстаткиТоваров/        Отчет общий для двух подсистем

│       │       ├── Report.xml

│       │       └── DataCompositionSchema.xml

│       └── Metadata.xml

├── Catalogs/

│   ├── Номенклатура/

│   │   ├── Object.xml

│   │   ├── Form.xml

│   │   └── Module.bsl

│   ├── Контрагенты/

│   ├── Организации/

│   ├── Склады/

│   └── ЕдиницыИзмерения/

├── Enums/

│   ├── ВидНоменклатуры.xml

│   └── СтатусДокумента.xml

├── InformationRegisters/

│   ├── ЦеныНоменклатуры/

│   │   ├── Object.xml

│   │   └── Module.bsl

│   └── ВидыЦен/                        Справочник для видов цен (дополнительный)

├── AccumulationRegisters/

│   └── ОстаткиНоменклатуры/

│       ├── Object.xml

│       └── Module.bsl

├── CommonModules/                      Общие модули (если нужны)

├── Roles.xml                           # Роли и права доступа

├── Forms/                              Общие формы (если есть)

├── Templates/                          Шаблоны печатных форм

├── README.md                           Описание проекта

├── .gitignore                          Игнорируемые файлы

└── build.xml                           Скрипты сборки (если используется CI/CD)
