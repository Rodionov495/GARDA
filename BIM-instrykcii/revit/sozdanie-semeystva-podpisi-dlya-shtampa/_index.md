---
title: Семейство подписи
order: 4.7
aliases:
  - path: >-
      Proektirovanie/sozdanie-semeystva-podpisi-dlya-shtampa/sozdanie-semeystva-podpisi-dlya-shtampa
    moved: "2026-08-18T15:14:05Z"
  - path: BIM-instrykcii/sozdanie-semeystva-podpisi-dlya-shtampa
    moved: "2026-09-08T16:08:11Z"
properties:
  - id: CDhLD
    value:
      - Луцко Д.
---

Данная инструкция описывает процесс формирования семейств подписей, предназначенных для заполнения штампов на листах



## Создание семейства

1\. Для создания новой подписи для штампа необходимо заранее создать скан подписи (формат PNG, PDF)



2\. Откройте файл шаблона подписи, расположенный по пути:

`C:\Nextcloud\Гарда - ТИМ – отдел\02_Семейства\Общие\Аннотации\Подписи\Подпись_Шаблон.rfa`



3\. Импортируйте файл-изображение подписи в файл шаблона

<note type="lab">

Вкладка «Вставить» -> «Импорт изображения» («Импорт PDF»)

</note>

<image src="./_index.jpeg" crop="0,0,100,100" scale="137px" width="135px" height="76px" float="center"/>



4\. Отмасштабируйте изображение и разместите в области для расположения подписи:

<image src="./_index-2.jpeg" crop="0,0,100,100" scale="611px" width="895px" height="233px" float="center"/>



5\. Обведите подпись инструментом «Сплайн»

<note type="lab">

Вкладка «Создание» -> «Линейная» -> «Сплайн».

</note>

Для сплайна выберите подкатегорию «Подпись»

<image src="./_index-3.jpeg" crop="0,0,100,100" scale="636px" width="1270px" height="698px" float="center"/>



6\. После обведения контуров подписи, удалите файл изображения с вида с последующей очисткой от неиспользуемых элементов:



<image src="./_index-4.jpeg" crop="0,0,100,100" scale="456px" width="734px" height="729px" float="center"/>



7\. В свойствах сплайна параметру «Видимые» назначьте параметр  «G_Штамп_Подпись»:



<image src="./sozdanie-semeystva-podpisi-dlya-shtampa.jpeg" crop="0,0,100,100" scale="650px" width="870px" height="430px" float="center"/>



8\. В свойствах типоразмера в параметре «Фамилия» записываем нужную фамилию:



<image src="./sozdanie-semeystva-podpisi-dlya-shtampa-2.jpeg" crop="0,0,100,100" scale="697px" width="1264px" height="483px" float="center"/>



9\. Сохраняем семейство к себе в личную папку, название формируется по принципу:

`Подпись_<Фамилия>`



10\. Перед использованием семейства необходимо направить его на согласование на почту Александру Родионову ([a.rodionov@gardapro.ru](mailto:a.rodionov@gardapro.ru))

### 