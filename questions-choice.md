---
chooseOptions:
  data: 
    - questionTitle: "Выбери правильный ответ"
      questionDescription: 
        - "Кто является основным создателем языка Java Script?"
      answers: 
        - "Бил Гейтс"
        - "Линус Торвальдс"
        - "Джеймс Гослинг" 
        - "Брендан Эйх"
      correctAnswer: "Брендан Эйх"
      explanation: "[wiki](https://ru.wikipedia.org/wiki/JavaScript)"
      complexity: "low"
      theme: 1 
   
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
      explanation: "Оператор равно (==) сначала приводит две переменные к числовому типу, а уже потом сраниваются их значения. Оператор строгого равенства (===) сначала проверяет типы переменных, и если они совпадают, то осуществляет сравнивание их значений, иначе возвращается false"
      complexity: "low"
      theme: 1

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
      explanation: "[Всплытие переменных](https://medium.com/@stasonmars/%D1%80%D0%B0%D0%B7%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%D1%81%D1%8F-%D1%81-%D0%BF%D0%BE%D0%B4%D0%BD%D1%8F%D1%82%D0%B8%D0%B5%D0%BC-hoisting-%D0%B2-javascript-7d2d27bc51f1)"
      complexity: "low"
      theme: 1

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
      explanation: "Оператор delete используется для удаления свойства из объекта. В данном случае x - это локальная переменная. Оператор delete не влияет на локальные переменные"
      complexity: "low"
      theme: 1

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
      explanation: "Оператор delete используется для удаления свойства из объекта. В данном случае x - это глобальная переменная. Оператор delete не влияет на локальные переменные"
      complexity: "low"
      theme: 1

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
      explanation: "Оператор delete используется для удаления свойства из объекта. В данном случае x - это объект, у которого есть свойство foo, и в самовызывающейся функции мы удаляем свойство foo у объекта x. После удаления мы пытаемся сослаться на удалённое свойство foo, что даёт результат undefined"
      complexity: "low"
      theme: 1

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
      explanation: "Объект emp1 наследует company как свойство протоипа. Оператор delet не удаляет свойства прототипа. Удалить такое свойство можно непосредственно из объекта Employee используя delete Employee.company или удалить из объекта emp1 используя свойство __proto__: delete emp1.__proto__.company"
      complexity: "low"
      theme: 1

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
      explanation: "Оператор delete удаляет элемент из массива, но при этом не влияет на его длинну"
      complexity: "low"
      theme: 1

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
      explanation: 
      - "Вот основные правила приведения типов с оператором сложения:"
      - "Number + Number -> Addition"
      - "Boolean + Number -> Addition"
      - "Boolean + Boolean -> Addition"
      - "Number + String -> Concatenation"
      - "String + Boolean -> Concatenation"
      - "String + String -> Concatenation"
      complexity: "low"
      theme: 1

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
      explanation: "Почитать про порядок выполнения операторов и ассоциативность на [MDN](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/Operator_Precedence)"
      complexity: "low"
      theme: 1
  
    - questionTitle: "Какие методы массива вернут строку как результат?"
      questionDescription: 
      answers: 
        - "slice()"
        - "toString()"
        - "join()"
        - "splice()"
        - "concat()"
      correctAnswer: 
        - "toString()"
        - "join()"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array"
      complexity: "2"
      theme: "Массивы"
      
    - questionTitle: "Что вернет метод fill?"
      questionDescription: "[1,2.3,4,5,6].fil(0,2,3)" 
      answers: 
        - "[0,2,3,4,5,6]"
        - "[1,2,0,4,5,6]"
        - "[1,2,3,0,5,6]" 
        - "[1,2,0,0,0,0]"
      correctAnswer: "[1,2,0,4,5,6]"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array/fill"
      complexity: "1"
      theme: "Массивы"
      
    - questionTitle: "Какие методы массива вернут boolean как результат?"
      questionDescription: 
      answers:   
        - "every()"
        - "some()"
        - "indexOf()"
        - "includes()"
        - "toString()"
      correctAnswer: 
        - "every()"
        - "some()"
        - "includes()"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array"
      complexity: "1"
      theme: "Массивы"
      
    - questionTitle: "При помощи какого метода можно создать новый массив?"
      questionDescription: 
      answers:   
       - "of()"
       - "reverse()"
       - "sort()"
       - "from()"
       - "indexOf()"
      correctAnswer: 
        - "of()"
        - "from()"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array"
      complexity: "2"
      theme: "Массивы"

    - questionTitle: "Какие методы массива возвращают новый массив?"
      questionDescription: 
      answers: 
        - "some()"
        - "map()"
        - "filter()" 
        - "forEach()"
      correctAnswer: 
        - "map()"
        - "filter()"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array"
      complexity: "1"
      theme: "Массивы"
      
    - questionTitle: "Какой из методов массива удалит и вернет первый элемент массива?"
      questionDescription: 
      answers: 
        - "pop()"
        - "shift()"
        - "unshift()" 
        - "push()"
      correctAnswer: "shift()"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array"
      complexity: "1"
      theme: "Массивы"
      
    - questionTitle: "Какие из методов или свойств массива вернут длину нового/существующего  массива?"
      questionDescription: 
      answers: 
        - "pop"
        - "shift"
        - "length"
        - "unshift" 
        - "push"
      correctAnswer: 
        - "push"
        - "unshift"
        - "length"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array"
      complexity: "2"
      theme: "Массивы"
      
    - questionTitle: "Что вернет метод slice?"
      questionDescription: "[1, 2, 3, 4, 5, 6].slice(2,3)"
      answers: 
        - "3"
        - ['2']
        - [2, 3]
        - [2]
        - ['2', '3']
        - [3]
      correctAnswer: 
        - [3]
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array/slice"
      complexity: "1"
      theme: "Массивы"
      
    - questionTitle: "Какие методы массива изменяют исходный массив?"
      questionDescription: 
      answers: 
        - "slice()"
        - "splice()"
        - "reverse()"
        - "some()"
        - "pop()"
      correctAnswer: 
        - "splice()"
        - "reverse()"
		- "pop()"
      explanation: "https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array"
      complexity: "2"
      theme: "Массивы"
      
---
