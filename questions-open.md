---
chooseOptions:
  data: 
    - questionTitle: Какой будет результат?
      questionDescription: [2 + 9 + "1"]
      correctAnswer: "\"111\""
      explanation: http://javascript.info/type-conversionsf
      complexity: low 

    - questionTitle: Какой будет результат?
      questionDescription: [1 + "2" + 9 ]
      correctAnswer: "\"129\""
      explanation: http://javascript.info/type-conversionsf
      complexity: low

    - questionTitle: Какой будет результат?
      questionDescription: [null + "8" / "4"]
      correctAnswer: "\"2\""
      explanation: http://javascript.info/type-conversionsf
      complexity: low

    - questionTitle: Какой будет результат?
      questionDescription: [(null + "2") * "3" + 5]
      correctAnswer: [nan, NaN, NAN]
      explanation: http://javascript.info/type-conversionsf
      complexity: low

    - questionTitle: Какой будет результат?
      questionDescription: [Boolean("JavaScript")]
      correctAnswer: ["true", "True", "TRUE"]
      explanation: http://javascript.info/type-conversionsf
      complexity: low

    - questionTitle: Какой будет результат?
      questionDescription: [Boolean(undefined)]
      correctAnswer: ["false", "False", "FALSE"]
      explanation: http://javascript.info/type-conversionsf
      complexity: low

    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof true)]
      correctAnswer: ["boolean", "Boolean", "BOOLEAN"]
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: low

    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof NaN)]
      correctAnswer: ["number", "Number", "NUMBER"]
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: low

    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof typeof(1))]
      correctAnswer: ["string", "String", "STRING"]
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: low

    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof 'true')]
      correctAnswer: ["string", "String", "STRING"]
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: low  

    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof isNaN)]
      correctAnswer: ["function", "Function", "FUNCTION"]
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: low

    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof null)]
      correctAnswer: ["object", "Object", "OBJECT"]
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: low

    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof undefined)]
      correctAnswer: ["undefined", "Undefined", "UNDEFINED"]
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: low
      
    - questionTitle: Что вернет следующий код?
      questionDescription: [console.log(typeof "[]")]
      correctAnswer: ["object", "Object", "OBJECT"]
      explanation: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof
      complexity: low  
---
