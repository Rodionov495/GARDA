---
title: Семейство подписи
order: 1.2
aliases:
  - { path: Proektirovanie/sozdanie-semeystva-podpisi-dlya-shtampa/sozdanie-semeystva-podpisi-dlya-shtampa, moved: "2026-08-18T15:14:05Z" }
  - { path: BIM-instrykcii/sozdanie-semeystva-podpisi-dlya-shtampa, moved: "2026-09-08T16:08:11Z" }
  - { path: BIM-instrykcii/revit/sozdanie-semeystva-podpisi-dlya-shtampa, moved: "2026-10-06T11:16:34Z" }
properties:
  - id: CDhLD
    value:
      - Луцко Д.
---

Данная инструкция описывает процесс формирования семейств подписей, предназначенных для заполнения штампов на листах и место хранения их.



<note type="info">
  Все подписи после проверки хранятся по пути:

  `C:\Nextcloud\Гарда - ТИМ – отдел\02_Семейства\00_Общие\00_Подписи`
</note>

## Создание семейства

1\. Для создания новой подписи для штампа необходимо заранее создать скан подписи (формат PNG, PDF)



2\. Откройте файл шаблона подписи, расположенный по пути:

`C:\Nextcloud\Гарда - ТИМ – отдел\02_Семейства\00_Общие\00_Подписи\Подпись_Шаблон.rfa`



3\. Импортируйте файл-изображение подписи в файл шаблона

<note type="lab">
  Вкладка «Вставить» -> «Импорт изображения» («Импорт PDF»)
</note>

![](./_index.jpeg){width=135px height=76px scale=137px}



4\. Отмасштабируйте изображение и разместите в области для расположения подписи:

![](./_index-2.jpeg){width=895px height=233px scale=611px}



5\. Обведите подпись инструментом «Сплайн»

<note type="lab">
  Вкладка «Создание» -> «Линейная» -> «Сплайн».
</note>

Для сплайна выберите подкатегорию «Подпись»

![](./_index-3.jpeg){width=1270px height=698px scale=636px}



6\. После обведения контуров подписи, удалите файл изображения с вида с последующей очисткой от неиспользуемых элементов:



![](./_index-4.jpeg){width=734px height=729px scale=456px}



7\. В свойствах сплайна параметру «Видимые» назначьте параметр  «G_Штамп_Подпись»:



![](./sozdanie-semeystva-podpisi-dlya-shtampa.jpeg){width=870px height=430px scale=650px}



8\. В свойствах типоразмера в параметрах «Должность» (1) и «Фамилия» (2) записываем нужную должность и фамилию соответственно:

![](./sozdanie-semeystva-podpisi-dlya-shtampa.webp){width=714px height=260px}



9\. Удаляем неиспользуемые должности:

![](./sozdanie-semeystva-podpisi-dlya-shtampa-2.webp){width=711px height=283px}

10\. Сохраняем семейство к себе в личную папку, название формируется по принципу:

`Подпись_<Фамилия>`

11\. Отправьте семейство на на почту руководителю BIM:

- Для Московского офиса это Александр Родионов ([a.rodionov@gardapro.ru](mailto:a.rodionov@gardapro.ru))
- Для Новосибирского офиса это Вадим Сталковский ([v.stalkovskiy@gardapro.ru](mailto:v.stalkovskiy@gardapro.ru))

###
