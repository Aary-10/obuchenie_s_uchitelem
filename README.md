<div style="background-color:#e6f0ff; padding: 15px; border-radius: 5px; border-top: 4px solid #2e8b57; margin-bottom: 10px;">
  <p style="font-size: 1.2em; font-weight: bold; margin-bottom: 5px;"><span style="color: #007791; margin-right: 5px;">🎯</span> Общая цель проекта:</p>
  <p style="margin-bottom: 10px;">Разработать решение для персонализации предложений постоянным клиентам интернет-магазина “В один клик” с целью увеличения их покупательской активности, основываясь на анализе данных и бизнес-моделировании.</p>
    <ul style="margin-left: 20px; padding-left: 20px;">
        <li style="list-style-type: disc; margin-bottom: 5px;"><strong>Промаркировать</strong> уровень финансовой активности клиентов (снизилась/прежний уровень).</li>
        <li style="list-style-type: disc; margin-bottom: 5px;"><strong>Собрать и проанализировать</strong> данные о клиентах по группам: коммуникация, продуктовое поведение, покупательское поведение и поведение на сайте.</li>
        <li style="list-style-type: disc; margin-bottom: 5px;"><strong>Построить модель</strong>, предсказывающую вероятность снижения покупательской активности клиента в следующие три месяца.</li>
        <li style="list-style-type: disc; margin-bottom: 5px;"><strong>Использовать</strong> данные модели и данные о прибыльности клиентов для выделения сегментов покупателей.</li>
        <li style="list-style-type: disc; margin-bottom: 5px;"><strong>Разработать</strong> персонализированные предложения для каждого сегмента.</li>
  </ul>
</div>
<div style="background-color:#f0f0f0; padding: 15px; border-radius: 5px; border-top: 2px solid #2e8b57; margin-bottom: 10px;">
  <p style="font-size: 1.2em; font-weight: bold; margin-bottom: 10px;">⚙️ Конкретные задачи:</p>
  
  <div style="margin-bottom: 10px; margin-left: 20px; padding-left: 20px;">
    <p style="font-weight: bold; margin-bottom: 5px;">Подготовка данных:</p>
      <ul style="margin-left: 0; padding-left: 20px;">
        <li style="list-style-type: disc; margin-bottom: 3px; line-height: 1.3;">Загрузить и проверить корректность предоставленных данных (файлы market_file.csv, market_money.csv, market_time.csv, money.csv).</li>
        <li style="list-style-type: disc; margin-bottom: 3px; line-height: 1.3;">Провести необходимую предобработку данных.</li>
         <li style="list-style-type: disc; margin-bottom: 3px; line-height: 1.3;">Объединить таблицы market_file.csv, market_money.csv, market_time.csv и преобразовать структуру данных по периодам.</li>
        <li style="list-style-type: disc; margin-bottom: 3px; line-height: 1.3;">Провести исследовательский анализ данных, отобрать клиентов с активностью не менее трех месяцев.</li>
    </ul>
  </div>
  
  <div style="margin-bottom: 10px; margin-left: 20px; padding-left: 20px;">
    <p style="font-weight: bold; margin-bottom: 5px;">Моделирование:</p>
     <ul style="margin-left: 0; padding-left: 20px;">
       <li style="list-style-type: disc; margin-bottom: 3px; line-height: 1.3;">Провести корреляционный анализ признаков и устранить мультиколлинеарность.</li>
        <li style="list-style-type: disc; margin-bottom: 3px; line-height: 1.3;">Использовать пайплайны для подготовки данных (ColumnTransformer для раздельной обработки количественных и категориальных признаков с различными кодировщиками и скейлерами).</li>
        <li style="list-style-type: disc; margin-bottom: 3px; line-height: 1.3;">Обучить модели: KNeighborsClassifier(), DecisionTreeClassifier(), LogisticRegression(), и SVC().</li>
        <li style="list-style-type: disc; margin-bottom: 3px; line-height: 1.3;">Подобрать гиперпараметры для каждой модели и выбрать лучшую, используя подходящую метрику.</li>
      </ul>
  </div>

  <div style="margin-bottom: 10px; margin-left: 20px; padding-left: 20px;">
     <p style="font-weight: bold; margin-bottom: 5px;">Анализ и Интерпретация:</p>
      <ul style="margin-left: 0; padding-left: 20px;">
          <li style="list-style-type: disc; margin-bottom: 3px; line-height: 1.3;">Оценить важность признаков для лучшей модели с помощью SHAP.</li>
           <li style="list-style-type: disc; margin-bottom: 3px; line-height: 1.3;">Выявить наиболее и наименее значимые признаки.</li>
        </ul>
   </div>

  <div style="margin-bottom: 10px; margin-left: 20px; padding-left: 20px;">
    <p style="font-weight: bold; margin-bottom: 5px;">Сегментация и Персонализация:</p>
     <ul style="margin-left: 0; padding-left: 20px;">
      <li style="list-style-type: disc; margin-bottom: 3px; line-height: 1.3;">Выполнить сегментацию покупателей, используя результаты моделирования и данные о прибыльности.</li>
      <li style="list-style-type: disc; margin-bottom: 3px; line-height: 1.3;">Выбрать и проанализировать целевой сегмент покупателей.</li>
      <li style="list-style-type: disc; margin-bottom: 3px; line-height: 1.3;">Разработать персонализированные предложения для выбранного сегмента с целью увеличения его покупательской активности.</li>
    </ul>
  </div>

  <div style="margin-left: 20px; padding-left: 20px;">
    <p style="font-weight: bold; margin-bottom: 5px;">Выводы:</p>
    <ul style="margin-left: 0; padding-left: 20px;">
        <li style="list-style-type: disc; margin-bottom: 3px; line-height: 1.3;">Сделать общий вывод по результатам проекта, включая информацию о выбранном сегменте, предложенных мерах и их обоснование.</li>
    </ul>
  </div>
</div>
</div>