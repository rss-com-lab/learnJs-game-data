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
      complexity: "2"
      theme: Приведение типов

    - questionTitle: Какой будет результат?
      questionDescription: [(null + "2") * "3" + 5]
      correctAnswer: "\"NaN\""
      explanation: http://javascript.info/type-conversions
      complexity: "2"
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
      theme: Объекты
      
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
      
    - questionTitle: Что выведет в консоль?
      questionDescription: 
        - "var z = 1, y = z = typeof y;"
        - "console.log(y);"
      correctAnswer: "undefined"
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/Operator_Precedence
      complexity: "2"
      theme: Типы данных
      
    - questionTitle: Каким будет вывод следующего кода?
      questionDescription:
        - "const CAR = {"
        - "color: \"blue\","
        - "price: 500"
        - "}"
        - "CAR.price = 1000;"
        - "console.log(CAR);"
      correctAnswer: 1000
      explanation: https://dev.to/ddhogan/scope-and-hoisting-of-variables-functions-and-this-in-javascript-5176
      complexity: "1"
      theme: Всплытие
      
    - questionTitle: Что выведет в консоль?
      questionDescription:
        - "num = 6;"
        - "console.log(num);"
        - "var num;"
      correctAnswer: 6
      explanation: https://dev.to/ddhogan/scope-and-hoisting-of-variables-functions-and-this-in-javascript-5176
      complexity: "1"
      theme: Всплытие
      
    - questionTitle: Что выведет в консоль?
      questionDescription: 
        - "console.log(num);"
        - "var num = 6;"
      correctAnswer: undefined
      explanation: https://dev.to/ddhogan/scope-and-hoisting-of-variables-functions-and-this-in-javascript-5176
      complexity: "1"
      theme: Всплытие
      
    - questionTitle: Каким будет вывод следующего кода?
      questionDescription: 
        - "new String('Hello') === 'Hello'"
      correctAnswer: false
      explanation: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: "1"
      theme: Типы данных
      
    - questionTitle: Каким будет вывод следующего кода?
      questionDescription: 
        - "\"string\" instanceof String;"
      correctAnswer: false
      explanation: http://qaru.site/questions/2111/why-does-instanceof-return-false-for-some-literals
      complexity: "2"
      theme: Типы данных
      
    - questionTitle: Каким будет вывод следующего кода?
      questionDescription:
        - "var x = [typeof x, typeof y][1];"
        - "typeof typeof x;"
      correctAnswer: "string"
      explanation: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: "2"
      theme: Типы данных
      
    - questionTitle: Каким будет вывод следующего кода?
      questionDescription:
        - "(function f() {"
        - "function f() { return 1; }"
        - "return f();"
        - "function f() { return 2; }"
        - "})();"
      correctAnswer: 2
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Statements/function
      complexity: "2"
      theme: Функции
      
    - questionTitle: Что выведет в консоль?
      questionDescription:
        - "var a = 1;"
        - "var b = function() {"
        - "a = 10;"
        - "return a;"
        - "function a() {"
        - "a = 5;"
        - "}"
        - "};"
        - "console.log(b(), a);"
      correctAnswer: [10, 1]
      explanation: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var
      complexity: "2"
      theme: Всплытие
      
    - questionTitle: Каким будет вывод следующего кода?
      questionDescription:
        - "alert([] + 1 + 2);"
      correctAnswer: "12"
      explanation: https://medium.com/@sergeybulavyk/%D0%BF%D1%80%D0%B5%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D1%82%D0%B8%D0%BF%D0%BE%D0%B2-%D0%B2-javascript-35a15ddfc333
      complexity: "3"
      theme: Типы данных
      
    - questionTitle: Что выведет в консоль?
      questionDescription:
        - "var module = {"
        - "x: 42,"
        - "getX: function() {"
        - "return this.x;"
        - "}"
        - "}"
        - "var y = module.getX;"
        - "console.log(y());"
      correctAnswer: undefined
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Function/bind
      complexity: "2"
      theme: Объекты
      
     
---
