---
typeAnswer:
  data: 
    - questionTitle: Какой будет результат?
      questionDescription: [2 + 9 + "1"]
      correctAnswer: "\"111\""
      explanation: http://javascript.info/type-conversions
      complexity: "1"
      theme: Приведение типов

    - questionTitle: Какой будет результат?
      questionDescription: [1 + "2" + 9 ]
      correctAnswer: "\"129\""
      explanation: http://javascript.info/type-conversions
      complexity: "1"
      theme: Приведение типов
      
    - questionTitle: Какой будет результат?
      questionDescription: [null + "8" / "4"]
      correctAnswer: "2"
      explanation: http://javascript.info/type-conversions
      complexity: "1"
      theme: Приведение типов

    - questionTitle: Какой будет результат?
      questionDescription: [(null + "2") * "3" + 5]
      correctAnswer: "\"NaN\""
      explanation: http://javascript.info/type-conversions
      complexity: "1"
      theme: Приведение типов

    - questionTitle: Какой будет результат?
      questionDescription: [Boolean("JavaScript")]
      correctAnswer: "true"
      explanation: http://javascript.info/type-conversions
      complexity: "1"
      theme: Приведение типов

    - questionTitle: Какой будет результат?
      questionDescription: [Boolean(undefined)]
      correctAnswer: "false"
      explanation: http://javascript.info/type-conversions
      complexity: "1"
      theme: Приведение типов

    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof true)]
      correctAnswer: "\"boolean\""
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: "1"
      theme: Типы данных

    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof NaN)]
      correctAnswer: "\"number\""
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: "1"
      theme: Типы данных

    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof typeof(1))]
      correctAnswer: "\"string\""
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: "1"
      theme: Типы данных

    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof 'true')]
      correctAnswer: "\"string\""
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: "1"  
      theme: Типы данных

    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof isNaN)]
      correctAnswer: "\"function\""
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: "1"
      theme: Типы данных

    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof null)]
      correctAnswer: "\"object\""
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: "1"
      theme: Типы данных

    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof undefined)]
      correctAnswer: "\"undefined\""
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: "1"
      theme: Типы данных
      
    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(0.1 + 0.2 == 0.3)]
      correctAnswer: "false"
      explanation: https://www.w3schools.com/js/js_numbers.asp
      complexity: "2"
      theme: Типы данных
      
    - questionTitle: Вопрос
      questionDescription: ['Какой метод Object.? используется для', 'клонирования объектов?']
      correctAnswer: "assign()"
      explanation: https://medium.com/@Farzad_YZ/3-ways-to-clone-objects-in-javascript-f752d148054d
      complexity: "2"
      theme: Объекты в JS
      
    - questionTitle: Что вернёт следующий код?
      questionDescription:
        - "const arr = [10, 12, 15, 21];"
        - "for (var i = 0; i < arr.length; i++) {"
        - "setTimeout(function() {"
        - "console.log('Index: ' + i +'"
        - ", element: ' + arr[i]);"
        - "}, 3000);"
        - "}"
      correctAnswer: "Index: 4, element: undefined"
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Closures
      complexity: "3"
      theme: Closures
     
---
