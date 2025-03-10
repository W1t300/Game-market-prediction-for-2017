Основные шаги исследования Загрузка и ознакомление с данными

Импортируйте таблицу и изучите её структуру: какие столбцы присутствуют, какие типы данных, сколько строк, есть ли пропуски. Оцените качество данных: наличие дубликатов, неточностей, аномальных значений. Определите период данных. Исходя из условий проекта, данные даны до 2016 года, причём наша задача – на основе данных до конца 2016 года понять закономерности для 2017 года. Предобработка данных

Приведение столбцов к нужным типам: год выпуска – целое число, оценки пользователей – числовой формат (учесть, что иногда пользователи ставят оценки в виде строк, например, "tbd"), а столбец с рейтингом ESRB может быть категориальным признаком. Обработка пропусков: возможны пропуски в оценках, жанрах, годах выхода. Надо решить, как их заполнить или удалить. Выделение актуального периода для анализа трендов: индустрия игр очень быстро развивается. Анализ данных за слишком давние года (например, до 2000-х) может быть нерелевантен при прогнозах на 2017 год. Определите «актуальный период» – например, последние 4-5 лет (2012-2016), чтобы сосредоточиться на современных платформах и вкусах потребителей. Исследовательский анализ данных (EDA)

Распределение продаж по годам: Посмотрите, как меняются глобальные продажи по годам. Есть ли спад или рост в последние годы? Какие годы наиболее релевантны для прогноза?

Продажи по платформам: Определите самые популярные платформы по продажам и их динамику. Выявите «живые» платформы (те, где выпускались игры в последние годы и были высокие продажи) и «угасающие» (давно не имеющие релизов).

Продажи по жанрам: Посмотрите, какие жанры наиболее популярны. Есть ли смена лидеров по популярности с течением времени?

Анализ региональных продаж: Сравните, какие платформы и жанры популярны в разных регионах (NA, EU, JP, Other). Например, в Японии могут быть популярны одни жанры (JRPG, Fighting), в Северной Америке – другие (Sports, Shooter), а в Европе ещё какие-то. Это поможет целенаправленно выбирать игры для конкретных региональных кампаний.

Оценки пользователей и критиков: Исследуйте взаимосвязь между оценками критиков/пользователей и объемами продаж. Есть ли сильная корреляция между высоким рейтингом и продажами? Часто критики и пользователи оценивают игры по-разному – проанализируйте эти различия.

Рейтинг ESRB: Исследуйте влияние возрастного рейтинга на продажи. Например, игры с рейтингом «М» (Mature) могут быть популярны в одних регионах, а семейные игры с рейтингом «E» (Everyone) – в других.

Определение “успешной” игры: Можно выбрать некий порог глобальных продаж (например, более 1 млн копий) и сравнить особенности игр, превысивших этот порог, с теми, что не дотягивают.

На этом этапе будут сформированы первичные гипотезы:

«Живые» платформы и жанры, на которые стоит ориентироваться. Возможное влияние оценки критиков и пользователей. Влияние возрастного рейтинга на продажи. Статистический анализ и проверка гипотез

Проверьте статистически значимые различия в продажах между разными жанрами, рейтингами ESRB или платформами за последние годы. Оцените корреляцию между числовыми показателями (оценки пользователей и критиков, количество оценок) и продажами. Портрет потенциально успешной игры На основе проведенного анализа выделите «признаки успеха». Например:

Для глобального успеха часто подходят игры определённого жанра (к примеру, Action или Shooter) на популярных текущих платформах (PS4, Xbox One в контексте 2016 года). Возможно, игры с высокими оценками критиков продаются лучше – в таком случае стоит обратить внимание на качество продукта и репутацию разработчиков. ESRB-рейтинг может влиять на целевую аудиторию: если вы ориентированы на массовый рынок, лучше выбирать «E» или «T», если ваш продукт ориентирован на зрелую аудиторию – «M». Рекомендации для 2017 года (или будущего периода) Сформулируйте конкретные рекомендации:

На какие платформы делать основной упор при выпуске новых игр? На какие жанры стоит обратить внимание для максимальных продаж? В каких регионах запускать активную рекламную кампанию для того или иного продукта? Как возрастной рейтинг может повлиять на стратегию продвижения? Стоит ли рассчитывать на успех без высоких оценок критиков и пользователей или важно работать над качеством продукта? Использование моделей прогнозирования (опционально) Если задача подразумевает, можно использовать машинное обучение или регрессионный анализ для предсказания продаж новой игры на основе её атрибутов (жанр, платформа, предполагаемый рейтинг, оценки).
