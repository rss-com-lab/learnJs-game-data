---
chooseOptions:
  data: 
    - questionTitle: "Кто является основным создателем языка Java Script?"
      questionDescription: []
      answers: 
        - "Бил Гейтс"
        - "Линус Торвальдс"
        - "Джеймс Гослинг" 
        - "Брендан Эйх"
      correctAnswer: "Брендан Эйх"
      explanation: "https://ru.wikipedia.org/wiki/JavaScript"
      complexity: 1
      theme: "Общие сведения"
   
    - questionTitle: "Какую строку выведет console.log?"
      questionDescription: 
        - "var a='1';"
        - "var b = 1;"
        - "res = (a == b) + ',' + (a === b);"
        - "console.log(res);)"
      answers: 
        - "false, false"
        - "true, true"
        - "false, true" 
        - "true, false"
      correctAnswer: "true, false"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Equality_comparisons_and_sameness"
      complexity: 1
      theme: "Приведение типов"

    - questionTitle: "Какое значение будет выведено в консоли?"
      questionDescription: 
        - "result = 0;"
        - "function addValue(x) {"
        - "result = result + x;"
        - "return result;"
        - "}"
        - "console.log(addValue(addValue(10)));)"
      answers: 
        - 30
        - 10
        - 20 
        - 0
      correctAnswer: 20
      explanation: "https://medium.com/@stasonmars/%D1%80%D0%B0%D0%B7%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%D1%81%D1%8F-%D1%81-%D0%BF%D0%BE%D0%B4%D0%BD%D1%8F%D1%82%D0%B8%D0%B5%D0%BC-hoisting-%D0%B2-javascript-7d2d27bc51f1"
      complexity: 1
      theme: Всплытие переменных

    - questionTitle: "Какое значение будет выведено в консоли?"
      questionDescription: 
        - "var output = (function(x) {"
        - "  delete x;"
        - "  return x;"
        - "})(0);"
        - "console.log(output);"
      answers: 
        - "undefined"
        - "0"
        - "{}" 
        - "ошибка"
      correctAnswer: "0"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/delete"
      complexity: 1
      theme: "Объекты"

    - questionTitle: "Какое значение будет выведено в консоли?"
      questionDescription: 
        - "var x = 1;"
        - "var output = (function(x) {"
        - "  delete x;"
        - "  return x;"
        - "})();"
        - "console.log(output);"
      answers: 
        - "undefined"
        - "0"
        - "1" 
        - "ошибка"
      correctAnswer: "1"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/delete"
      complexity: 1
      theme: "Объекты"

    - questionTitle: "Какое значение будет выведено в консоли?"
      questionDescription: 
        - "var x = { foo : 1}"
        - "var output = (function(x) {"
        - "  delete x.foo;"
        - "  return x.foo;"
        - "})();"
        - "console.log(output);"
      answers: 
        - "undefined"
        - "0"
        - "{}" 
        - "ошибка"
      correctAnswer: "undefined"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/delete"
      complexity: 1
      theme: "Объекты"

    - questionTitle: "Какое значение будет выведено в консоли?"
      questionDescription: 
        - "var Employee = {"
        - "  company: 'xyz'"
        - "}"
        - "var emp1 = Object.create(Employee);"
        - "delete emp1.company"
        - "console.log(emp1.company);"
      answers: 
        - "undefined"
        - "xyz"
        - "null" 
        - "ошибка"
      correctAnswer: "xyz"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/delete"
      complexity: "2"
      theme: "Объекты"

    - questionTitle: "Какое значение будет выведено в консоли?"
      questionDescription: 
        - "var trees = ['xyz', 'xxxx', 'test', 'ryan', 'apple'];"
        - "delete trees[3];"
        - "console.log(trees.length);"
      answers: 
        - "5"
        - "4"
        - "undefined" 
        - "6"
      correctAnswer: "5"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/delete"
      complexity: 2
      theme: "Массивы"

    - questionTitle: "Какое значение будет выведено в консоли?"
      questionDescription: 
        - "var bar = true;"
        - "console.log(bar + 0);"
        - "console.log(bar + 'xyz');"
        - "console.log(bar + true); "
        - "console.log(bar + false);"
      answers: 
        - "'10', 'truexyz', 'truetrue', 'truefalse'"
        - "1, 2, 2, 1"
        - "'1', 'truexyz', '11', 1" 
        - "1, 'truexyz', 2, 1"
      correctAnswer: "1, 'truexyz', 2, 1"
      explanation: "http://javascript.info/type-conversions"
      complexity: 1
      theme: "Приведение типов"

    - questionTitle: "Какое значение будет выведено в консоли?"
      questionDescription: 
        - "var z = 1, y = z = typeof y;"
        - "console.log(y);"
      answers: 
        - "'undefined'"
        - "1"
        - "undefined" 
        - "NaN"
      correctAnswer: "'undefined'"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/Operator_Precedence"
      complexity: "3"
      theme: "Операторы"
      
    - questionTitle: "Что вернет метод fill?"
      questionDescription:
        - "[1,2.3,4,5,6].fil(0,2,3)" 
      answers: 
        - "[0,2,3,4,5,6]"
        - "[1,2,0,4,5,6]"
        - "[1,2,3,0,5,6]" 
        - "[1,2,0,0,0,0]"
      correctAnswer: "[1,2,0,4,5,6]"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array/fill"
      complexity: "1"
      theme: "Массивы"
      
    - questionTitle: "Какой из методов массива удалит и вернет первый элемент массива?"
      questionDescription: []
      answers: 
        - "pop()"
        - "shift()"
        - "unshift()" 
        - "push()"
      correctAnswer: "shift()"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array"
      complexity: "1"
      theme: "Массивы"
      
    - questionTitle: "Number в JS по умолчанию хранятся в:"
      questionDescription: []
      answers:
      - 64 бита
      - 32 бита
      - 16 бит
      - 8 бит
      correctAnswer: 
      - 64 бита
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Data_structures
      complexity: "1"
      theme: Типы данных
      
    - questionTitle: "Что выведет в консоль?"
      questionDescription:
        - "const x = null || 0 || {name: false};"
        - "console.log(x);"
      answers:
        - "0"
        - "undefined"
        - "null"
        - "{name: false}"
      correctAnswer:
        - "{name: false}"
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/%D0%9B%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5_%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%8B
      complexity: "1"
      theme: Типы данных
      
    - questionTitle: "Что выведет  в консоль?"
      questionDescription:
        - "var scope = \"global\";"
        - "function outer() {"
        - "function scope() {"
        - "console.log(scope);"
        - "}"
        - "scope();"
        - "}"
        - "outer();"
      answers:
        - "global"
        - "object window"
        - "ReferenceError"
        - "тело функции scope"
      correctAnswer:
        - "тело функции scope"
      explanation: http://speakingjs.com/es5/ch16.html
      complexity: "2"
      theme: Scope
      
    - questionTitle: "Что выведет  в консоль?"
      questionDescription:
        - "var b = 1;"
        - "function outer() {"
        - "var b = 2"
        - "function inner() {"
        - "b++;"
        - "var b = 3;"
        - "console.log(b);"
        - "}"
        - "inner();"
        - "}"
        - "outer();"
      answers:
        - "undefined"
        - "NaN"
        - "2"
        - "3"
        - "4"
      correctAnswer:
        - "3"
      explanation: http://speakingjs.com/es5/ch16.html
      complexity: "2"
      theme: Scope
      
    - questionTitle: "Что выведет в консоль?"
      questionDescription:
        - "function () {"
        - "try {"
        - "throw new Error();"
        - "} catch (x) {"
        - "var x = 1, y = 2;"
        - "console.log(x);"
        - "}"
        - "console.log(x);"
        - "console.log(y);"
        - "})();"
      answers:
        - "1, undefined, 2"
        - "1, 1, 2"
        - "1, undefined, undefined"
      correctAnswer:
        - "1, undefined, 2"
      explanation: https://dev.opera.com/articles/efficient-javascript/?page=2#trycatch
      complexity: "3"
      theme: Scope
      
    - questionTitle: "Что выведет  в консоль?"
      questionDescription:
        - "(function(x) {"
        - "return (function(y) {"
        - "console.log(x);"
        - "})(2)"
        - "})(1);"
      answers:
        - "undefined"
        - "2"
        - "1"
        - "ReferenceError"
      correctAnswer:
        - "1"
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Closures
      complexity: "1"
      theme: Замыкание
      
    - questionTitle: "Какой будет результат выполнения?"
      questionDescription:
        - "(function() {"
        - "return typeof arguments;"
        - "})();"
      answers:
        - "undefined"
        - "object"
        - "array"
        - "arguments"
      correctAnswer:
        - "object"
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Functions/arguments
      complexity: "2"
      theme: Функции
      
    - questionTitle: "Какой будет результат выполнения?"
      questionDescription:
        - "var f = function g() {"
        - "return 23;"
        - "};"
        - "typeof g();"
      answers:
        - "undefined"
        - "function"
        - "number"
        - "ReferenceError"
      correctAnswer:
        - "ReferenceError"
      explanation: http://qaru.site/questions/39198/why-use-named-function-expressions
      complexity: "2"
      theme: Функции
      
    - questionTitle: "Какой будет результат выполнения?"
      questionDescription:
        - "var f = function g() {"
        - "return 23;"
        - "};"
        - "concole.log(typeof g);"
      answers:
        - "undefined"
        - "function"
        - "number"
        - "ReferenceError"
      correctAnswer:
        - "undefined"
      explanation: http://qaru.site/questions/39198/why-use-named-function-expressions
      complexity: "2"
      theme: Функции
      
    - questionTitle: "Какой будет результат выполнения?"
      questionDescription:
        - "(function(a) {"
        - "arguments[0] = 10;"
        - "return a;"
        - "})(5);"
      answers:
        - 5
        - 10
        - "undefined"
        - "ReferenceError"
      correctAnswer:
        - 10
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Functions/arguments
      complexity: "3"
      theme: Функции
      
    - questionTitle: "Что выведет в консоль?"
      questionDescription:
        - "var obj = {"
        - "a: 1"
        - "};"
        - "(function(obj) {"
        - "obj = {"
        - "a: 2"
        - "};"
        - "})(obj);"
      answers:
        - 1
        - 2
        - "undefined"
        - "ReferenceError"
      correctAnswer:
        - 1
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Functions
      complexity: "3"
      theme: Функции
      
    - questionTitle: "С помощью какого метода объекта события можно отменить стандартное поведение браузера?"
      questionDescription: []
      answers:
        - "cancelEvents()"
        - "preventEvent()"
        - "preventDefault()"
        - "stopPropagation()"
      correctAnswer:
        - preventDefault()
      explanation: https://learn.javascript.ru/default-browser-action
      complexity: "1"
      theme: События
      
    - questionTitle: "Какой будет результат выполнения?"
      questionDescription:
        - "function Car(color) {"
        - "this.color = color;"
        - "}"
        - "var lada = new Car(\"Black\");"
        - "Car.prototype.currentGear = 1;"
        - "console.log(++lada.currentGear);"
        - "console.log(Car.prototype.currentGear);" 
      answers:
        - "1, 2"
        - "2, 1"
        - "1, 1"
        - "2, 2"
      correctAnswer:
        - "2, 1"
      explanation: https://hackernoon.com/prototypes-in-javascript-5bba2990e04b
      complexity: "2"
      theme: Объекты
      
    - questionTitle: "В каком порядке выводятся значения в консоль?"
      questionDescription:
        - "(function() {"
        - "console.log(1);"
        - "setTimeout(function(){console.log(2)}, 1000);"
        - "setTimeout(function(){console.log(3)}, 0);"
        - "console.log(4);"
        - "})();"
      answers:
        - "1, 2, 3, 4"
        - "1, 3, 2, 4"
        - "1, 4, 2, 3"
        - "1, 4, 3, 2"
      correctAnswer:
        - "1, 4, 3, 2"
      explanation: https://medium.com/front-end-weekly/javascript-event-loop-explained-4cd26af121d4
      complexity: "3"
      theme: События
      
    - questionTitle: "В чем особенность событий focus/blur?"
      questionDescription: []
      answers:
        - "у них нет объекта события"
        - "они не всплывают"
        - "можно назначить только один обработчик событий"
        - "нельзя отменить действия браузера по умолчанию"
      correctAnswer:
        - "они не всплывают"
      explanation: https://learn.javascript.ru/focus-blur
      complexity: "2"
      theme: События
      
    - questionTitle: "В какой момент времени определяется значение this для метода?"
      questionDescription: []
      answers:
        - "при создании объекта"
        - "при каждом вызове метода"
        - "в момент первого вызова метода"
        - "при создании метода"
      correctAnswer:
        - "при каждом вызове метода"
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/this
      complexity: "2"
      theme: Объекты
      
    - questionTitle: "В каком порядке выведутся значения в консоль?"
      questionDescription:
        - "(function() {"
        - "console.log(1);"
        - "setTimeout(() => console.log(2), 1000);"
        - "setTimeout(() => console.log(3), 0);"
        - "Promise.resolve(true).then(() => console.log(4));"
        - "console.log(5);"
        - "})();"
      answers:
        - "1, 2, 3, 4, 5"
        - "1, 5, 3, 2, 4"
        - "1, 3, 5, 2, 4"
        - "1, 5, 4, 3, 2"
      correctAnswer:
        - "1, 5, 4, 3, 2"
      explanation: https://blog.bitsrc.io/understanding-asynchronous-javascript-the-event-loop-74cd408419ff
      complexity: "3"
      theme: События
      
    - questionTitle: "В каком порядке выведутся значения в консоль?"
      questionDescription: 
       - "let promise = new Promise((resolve, reject) => {"
       - "console.log(1);"
       - "resolve(2);"
       - "});"
       - "promise.then(res => console.log(res));"
       - "console.log(3);"
      answers:
        - "1, 2, 3"
        - "3, 1, 2"
        - "1, 3, 2"
        - "3, 2, 1"
      correctAnswer:
        - "1, 3, 2"
      explanation: https://levelup.gitconnected.com/javascript-and-asynchronous-magic-bee537edc2da
      complexity: "3"
      theme: События
      
    - questionTitle: "Какой будет результат выполнения?"
      questionDescription: 
       - "function test() {"
       - "console.log(a);"
       - "console.log(foo());"
       - "var a = 1;"
       - "function foo() {"
       - "return 2;"
       - "}"
       - "}"
       - "test();"
      answers:
        - "undefined, undefined"
        - "undefined, 2"
        - "1, 2"
        - "undefined, function foo()"
      correctAnswer:
        - "undefined, function foo()"
      explanation: https://dev.to/ddhogan/scope-and-hoisting-of-variables-functions-and-this-in-javascript-5176
      complexity: "2"
      theme: Всплытие
      
    - questionTitle: "Какой будет результат выполнения?"
      questionDescription:
        - "function doSomething() {"
        - "console.log(bar);"
        - "console.log(foo);"
        - "var bar = 1;"
        - "let foo = 2;"
        - "}"
      answers:
        - "undefined, undefined"
        - "undefined,  ReferenceError"
        - "1, undefined"
        - "1, 2"
      correctAnswer:
        - "undefined,  ReferenceError"
      explanation: https://dev.to/ddhogan/scope-and-hoisting-of-variables-functions-and-this-in-javascript-5176
      complexity: "2"
      theme: Всплытие
      
    - questionTitle: "Какой будет результат фызова функции?"
      questionDescription:
        - "function varTest() {"
        - "var x = 1;"
        - "if (true) {"
        - "var x = 2;"
        - "console.log(x);"
        - "}"
        - "console.log(x);"
        - "}"
      answers:
        - "2, undefined"
        - "2, 1"
        - "2, 2"
        - "SyntaxError"
      correctAnswer:
        - "2, 2"
      explanation: https://dev.to/ddhogan/scope-and-hoisting-of-variables-functions-and-this-in-javascript-5176
      complexity: "2"
      theme: Всплытие
      
    - questionTitle: "Какой будет результат фызова функции?"
      questionDescription:
        - "function letTest() {"
        - "let x = 1;"
        - "if (true) {"
        - "let x = 2;"
        - "console.log(x);"
        - "}"
        - "console.log(x);"
        - "}"
      answers:
        - "2, undefined"
        - "2, 1"
        - "2, 2"
        - "SyntaxError"
      correctAnswer:
        - "2, 1"
      explanation: https://dev.to/ddhogan/scope-and-hoisting-of-variables-functions-and-this-in-javascript-5176
      complexity: "2"
      theme: Всплытие
      
    - questionTitle: "Какой будет результат фызова функции?"
      questionDescription:
        - "function test() {"
        - "let x = 1;"
        - "if (true) {"
        - "var x = 2;"
        - "console.log(x);"
        - "}"
        - "console.log(x);"
        - "}"
      answers:
        - "2, undefined"
        - "2, 1"
        - "2, 2"
        - "SyntaxError"
      correctAnswer:
        - "SyntaxError"
      explanation: https://dev.to/ddhogan/scope-and-hoisting-of-variables-functions-and-this-in-javascript-5176
      complexity: "2"
      theme: Всплытие
   
      
---
