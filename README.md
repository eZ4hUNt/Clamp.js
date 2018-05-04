![alt text](https://github.com/eZ4hUNt/Clamp.js/blob/master/preview.jpg)
# Как использовать
```
var myParagraph = $('.clampjs').get(0);

// Одна строка
  $clamp(myParagraph, {clamp: 1});
  
// Несколько строк (Три строки)
  $clamp(myParagraph, {clamp: 3});
  
// Автоматическая высота
  $clamp(myParagraph, {clamp: 'auto'});
  
// Высота строк задается в px
  $clamp(myParagraph, {clamp: '35px'});
```

# Опции
*clamp (Number | String | 'auto')* - Каким образом будет обрезаться строка (количество строк, высота строк или автоматически)

*useNativeClamp (Boolean)* - Включает или отключает встроеный -webkit-line-clamp. По умолчанию - true, если браузер поддерживает. 

*truncationChar (String)* - Символ, который нужно вставить в конце элемента HTML после усечения. По умолчанию это многоточие (...).

*truncationHTML (String)* - Строка HTML для вставки перед символом усечения. Это полезно, если вы хотите добавить ссылку «Читать дальше» или что-то в этом роде.

*splitOnChars (Array)* - Определяет, какие символы использовать для фрагментации элемента на более мелкие фрагменты. 

*animate (Boolean)* - Анимирует удаления символов в строке.
