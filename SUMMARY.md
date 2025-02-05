# Оглавление

* [Вступление](docs/getting-started.md)
  * [Почему TypeScript](docs/why-typescript.md)
* [JavaScript](docs/javascript/recap.md)
  * [Сравнение типов данных](docs/javascript/equality.md)
  * [Ссылочные типы данных](docs/javascript/references.md)
  * [Null vs. Undefined](docs/javascript/null-undefined.md)
  * [this](docs/javascript/this.md)
  * [Замыкания](docs/javascript/closure.md)
  * [Числа](docs/javascript/number.md)
  * [Truthy](docs/javascript/truthy.md)
* [Будущее JavaScript](docs/future-javascript.md)
  * [Классы](docs/classes.md)
    * [Объявление классов](docs/classes-emit.md)
  * [Стрелочные функции](docs/arrow-functions.md)
  * [Rest параметры](docs/rest-parameters.md)
  * [Директива let](docs/let.md)
  * [Директива const](docs/const.md)
  * [Деструктурирование](docs/destructuring.md)
  * [Spread Оператор](docs/spread-operator.md)
  * [for...of](docs/for...of.md)
  * [Итераторы](docs/iterators.md)
  * [Шаблонизаторы строк](docs/template-strings.md)
  * [Promise](docs/promise.md)
  * [Генераторы](docs/generators.md)
  * [Async Await](docs/async-await.md)
* [Проекты](docs/project/project.md)
  * [Контекст компиляции](docs/project/compilation-context.md)
    * [tsconfig.json](docs/project/tsconfig.md)
    * [Какие файлы?](docs/project/files.md)
  * [Область описания](docs/project/declarationspaces.md)
  * [Модули](docs/project/modules.md)
    * [Анотация модулей](docs/project/external-modules.md)
    * [globals.d.ts](docs/project/globals.md)
  * [Пространство имен](docs/project/namespaces.md)
  * [Динамический import](docs/project/dynamic-import-expressions.md)
* [Node.js Быстрый старт](docs/quick/nodejs.md)
* [Browser Быстрый старт](docs/quick/browser.md)
* [Система типов в TypeScript](docs/types/type-system.md)
  * [Руководство по миграции с JS](docs/types/migrating.md)
  * [@types](docs/types/@types.md)
  * [Декларирование среды](docs/types/ambient/intro.md)
    * [Декларирование файлов](docs/types/ambient/d.ts.md)
    * [Переменные](docs/types/ambient/variables.md)
  * [Интерфейсы](docs/types/interfaces.md)
  * [Перечисляемые типы](docs/enums.md)
  * [`lib.d.ts`](docs/types/lib.d.ts.md)
  * [Функции](docs/types/functions.md)
  * [Callable](docs/types/callable.md)
  * [Объявление типов](docs/types/type-assertion.md)
  * [Freshness](docs/types/freshness.md)
  * [Type Guard](docs/types/typeGuard.md)
  * [Литералы](docs/types/literal-types.md)
  * [Readonly](docs/types/readonly.md)
  * [Generics](docs/types/generics.md)
  * [Тип Inference](docs/types/type-inference.md)
  * [Тип Compatibility](docs/types/type-compatibility.md)
  * [Тип Never](docs/types/never.md)
  * [Discriminated Unions](docs/types/discriminated-unions.md)
  * [Index Signatures](docs/types/index-signatures.md)
  * [Перемещаемые типы](docs/types/moving-types.md)
  * [Обработка исключений](docs/types/exceptions.md)
  * [Примиси](docs/types/mixins.md)
* [JSX](docs/jsx/tsx.md)
  * [React](docs/jsx/react.md)
  * [Non React JSX](docs/jsx/others.md)
* [Options](docs/options/intro.md)
  * [noImplicitAny](docs/options/noImplicitAny.md)
  * [strictNullChecks](docs/options/strictNullChecks.md)
* [Ошибки в TypeScript](docs/errors/main.md)
  * [Interpreting Errors](docs/errors/interpreting-errors.md)
  * [Common Errors](docs/errors/common-errors.md)
* [NPM](docs/npm/index.md)
* [Тестирование](docs/testing/intro.md)
  * [Jest](docs/testing/jest.md)
  * [Cypress](docs/testing/cypress.md)
* [Инструменты](docs/tools/intro.md)
  * [Prettier](docs/tools/prettier.md)
  * [Husky](docs/tools/husky.md)
  * [Changelog](docs/tools/changelog.md)
* [Советы](docs/tips/main.md)
  * [Строковые перечисляемые типы](docs/tips/stringEnums.md)
  * [Nominal Typing](docs/tips/nominalTyping.md)
  * [Stateful Functions](docs/tips/statefulFunctions.md)
  * [Связывание это плохо](docs/tips/bind.md)
  * [Каррирование](docs/tips/currying.md)
  * [Type Instantiation](docs/tips/typeInstantiation.md)
  * [Ленивая инициализация объекта](docs/tips/lazyObjectLiteralInitialization.md)
  * [Полезные классы](docs/tips/classesAreUseful.md)
  * [Избегайте использования Export Default](docs/tips/defaultIsBad.md)
  * [Limit Property Setters](docs/tips/propertySetters.md)
  * [`outFile` caution](docs/tips/outFile.md)
  * [Советы по JQuery](docs/tips/jquery.md)
  * [Статический конструктор](docs/tips/staticConstructor.md)
  * [Паттерн синглтон](docs/tips/singleton.md)
  * [Аргументы функции](docs/tips/functionParameters.md)
  * [Build Toggles](docs/tips/build-toggles.md)
  * [Barrel](docs/tips/barrel.md)
  * [Create Arrays](docs/tips/create-arrays.md)
  * [Typesafe Event Emitter](docs/tips/typed-event.md)
* [StyleGuide](docs/styleguide/styleguide.md)
* [TypeScript Compiler Internals](docs/compiler/overview.md)
  * [Program](docs/compiler/program.md)
  * [AST](docs/compiler/ast.md)
    * [TIP: Visit Children](docs/compiler/ast-tip-children.md)
    * [TIP: SyntaxKind enum](docs/compiler/ast-tip-syntaxkind.md)
    * [Trivia](docs/compiler/ast-trivia.md)
  * [Scanner](docs/compiler/scanner.md)
  * [Parser](docs/compiler/parser.md)
    * [Parser Functions](docs/compiler/parser-functions.md)
  * [Binder](docs/compiler/binder.md)
    * [Binder Functions](docs/compiler/binder-functions.md)
    * [Binder Declarations](docs/compiler/binder-declarations.md)
    * [Binder Container](docs/compiler/binder-container.md)
    * [Binder SymbolTable](docs/compiler/binder-symboltable.md)
    * [Binder Error Reporting](docs/compiler/binder-diagnostics.md)
  * [Checker](docs/compiler/checker.md)
    * [Checker Diagnostics](docs/compiler/checker-global.md)
    * [Checker Error Reporting](docs/compiler/checker-diagnostics.md)
  * [Emitter](docs/compiler/emitter.md)
    * [Emitter Functions](docs/compiler/emitter-functions.md)
    * [Emitter SourceMaps](docs/compiler/emitter-sourcemaps.md)
  * [Помощь](docs/compiler/contributing.md)
