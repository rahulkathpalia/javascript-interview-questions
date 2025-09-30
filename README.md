# JavaScript Interview Questions & Answers

> Click :star:if you like the project and follow [@SudheerJonna](https://twitter.com/SudheerJonna) for more updates. Coding questions available [here](#coding-exercise). Check [DataStructures and Algorithms](https://github.com/sudheerj/datastructures-algorithms) for DSA related questions and [ECMAScript](https://github.com/sudheerj/ECMAScript-features) for all ES features.).

---

<div>
<p align="center">
  <a href="https://www.greatfrontend.com/questions/formats/javascript-functions?utm_source=github&utm_medium=referral&utm_campaign=sudheerj-js&fpr=sudheerj&gnrs=sudheerj">
    <img src="./images/collab/greatfrontend-js.gif" alt="GreatFrontEnd JavaScript Interview Questions" width="100%">
  </a>
</p>
</div>

> Practice 280+ JavaScript coding interview questions in-browser. Built by ex-FAANG interviewers. No AI-generated fluff. No fake reviews. [Try GreatFrontEnd →](https://www.greatfrontend.com/questions/formats/javascript-functions?utm_source=github&utm_medium=referral&utm_campaign=sudheerj-js&fpr=sudheerj&gnrs=sudheerj) 💡

---

<div>
<p align="center">
  <a href="https://www.frontendlead.com/coding-questions?utm_source=github&utm_medium=referral&ut%0Dm_campaign=sudheerj-js" rel="dofollow">
    <img src="./images/collab/frontendlead-banner.png" alt="FrontEndLead JavaScript Interview Questions" width="100%">
  </a>
</p>
</div>

> 🚀 Ace Javascript interview questions with solutions from FAANG+ companies! [Try FrontendLead →](https://www.frontendlead.com/coding-questions?utm_source=github&utm_medium=referral&ut%0Dm_campaign=sudheerj-js) 🚀

---

<p align="center">
  <a href=https://zerotomastery.io/?utm_source=github&utm_medium=sponsor&utm_campaign=javascript-interview-questions>
    <img src=https://process.fs.teachablecdn.com/ADNupMnWyR7kCWRvm76Laz/resize=height:70/https://www.filepicker.io/api/file/AKYtjj5SSGyJuyZrkAB2 alt="ZTM Logo" width="100" height="50">
  </a>
  <p align="center">
    <ol>
    <li>Take this <a href=https://links.zerotomastery.io/jsp_sudheer>JavaScript Projects</a> course to go from a JS beginner to confidently building your own projects</li>
    <li>Take this <a href=https://links.zerotomastery.io/mci_sudheer2>coding interview bootcamp</a> if you’re serious about getting hired and don’t have a CS degree</li>
    <li>Take this <a href=https://links.zerotomastery.io/ajs_sudheer>Advanced JavaScript Course</a> to learn advanced JS concepts and become a top JS developer</li>
    </ol>
  </p>
</p>

---

### Table of Contents

<!-- TOC_START -->
| No. | Questions |
| --- | --------- |
| 1 | [What are the possible ways to create objects in JavaScript](#what-are-the-possible-ways-to-create-objects-in-javascript) |
| 2 | [What is a prototype chain](#what-is-a-prototype-chain) |
| 3 | [What is the Difference Between `call`, `apply`, and `bind`](#what-is-the-difference-between-call-apply-and-bind) |
| 4 | [What is JSON and its common operations](#what-is-json-and-its-common-operations) |
| 5 | [What is the purpose of the array slice method](#what-is-the-purpose-of-the-array-slice-method) |
| 6 | [What is the purpose of the array splice method](#what-is-the-purpose-of-the-array-splice-method) |
| 7 | [What is the difference between slice and splice](#what-is-the-difference-between-slice-and-splice) |
| 8 | [How do you compare Object and Map](#how-do-you-compare-object-and-map) |
| 9 | [What is the difference between == and === operators](#what-is-the-difference-between--and--operators) |
| 10 | [What are lambda expressions or arrow functions](#what-are-lambda-expressions-or-arrow-functions) |
| 11 | [What is a first class function](#what-is-a-first-class-function) |
| 12 | [What is a first order function](#what-is-a-first-order-function) |
| 13 | [What is a higher order function](#what-is-a-higher-order-function) |
| 14 | [What is a unary function](#what-is-a-unary-function) |
| 15 | [What is the currying function](#what-is-the-currying-function) |
| 16 | [What is a pure function](#what-is-a-pure-function) |
| 17 | [What are the benefits of pure functions](#what-are-the-benefits-of-pure-functions) |
| 18 | [What is the purpose of the let keyword](#what-is-the-purpose-of-the-let-keyword) |
| 19 | [What is the difference between let and var](#what-is-the-difference-between-let-and-var) |
| 20 | [What is the reason to choose the name let as a keyword](#what-is-the-reason-to-choose-the-name-let-as-a-keyword) |
| 21 | [How do you redeclare variables in a switch block without an error](#how-do-you-redeclare-variables-in-a-switch-block-without-an-error) |
| 22 | [What is the Temporal Dead Zone](#what-is-the-temporal-dead-zone) |
| 23 | [What is an IIFE (Immediately Invoked Function Expression)](#what-is-an-iife-immediately-invoked-function-expression) |
| 25 | [What is memoization](#what-is-memoization) |
| 26 | [What is Hoisting](#what-is-hoisting) |
| 27 | [What are classes in ES6](#what-are-classes-in-es6) |
| 28 | [What are closures](#what-are-closures) |
| 29 | [What are modules](#what-are-modules) |
| 31 | [What is scope in javascript](#what-is-scope-in-javascript) |
| 32 | [What is a service worker](#what-is-a-service-worker) |
| 33 | [How do you manipulate DOM using a service worker](#how-do-you-manipulate-dom-using-a-service-worker) |
| 34 | [How do you reuse information across service worker restarts](#how-do-you-reuse-information-across-service-worker-restarts) |
| 35 | [What is a promise](#what-is-a-promise) |
| 36 | [Why do you need a promise](#why-do-you-need-a-promise) |
| 37 | [Explain the three states of promise](#explain-the-three-states-of-promise) |
| 38 | [What is a callback function](#what-is-a-callback-function) |
| 39 | [Why do we need callbacks](#why-do-we-need-callbacks) |
| 40 | [What is a callback hell](#what-is-a-callback-hell) |
| 41 | [What are the main rules of promise](#what-are-the-main-rules-of-promise) |
| 42 | [What is callback in callback](#what-is-callback-in-callback) |
| 43 | [What is promise chaining](#what-is-promise-chaining) |
| 44 | [What is promise.all](#what-is-promiseall) |
| 45 | [What is the purpose of the race method in promise](#what-is-the-purpose-of-the-race-method-in-promise) |
| 46 | [What is a strict mode in javascript](#what-is-a-strict-mode-in-javascript) |
| 47 | [Why do you need strict mode](#why-do-you-need-strict-mode) |
| 48 | [How do you declare strict mode](#how-do-you-declare-strict-mode) |
| 49 | [What is the purpose of double exclamation](#what-is-the-purpose-of-double-exclamation) |
| 50 | [What is the purpose of the delete operator](#what-is-the-purpose-of-the-delete-operator) |
| 51 | [What is typeof operator](#what-is-typeof-operator) |
| 52 | [What is undefined property](#what-is-undefined-property) |
| 53 | [What is null value](#what-is-null-value) |
| 54 | [What is the difference between null and undefined](#what-is-the-difference-between-null-and-undefined) |
| 55 | [What is eval](#what-is-eval) |
| 56 | [What is isNaN](#what-is-isnan) |
| 57 | [What are the differences between undeclared and undefined variables](#what-are-the-differences-between-undeclared-and-undefined-variables) |
| 58 | [What are global variables](#what-are-global-variables) |
| 59 | [What are the problems with global variables](#what-are-the-problems-with-global-variables) |
| 60 | [What is NaN property](#what-is-nan-property) |
| 61 | [What is the purpose of isFinite function](#what-is-the-purpose-of-isfinite-function) |
| 62 | [What is an event flow](#what-is-an-event-flow) |
| 63 | [What is event capturing](#what-is-event-capturing) |
| 64 | [What is event bubbling](#what-is-event-bubbling) |
| 65 | [What is the difference between native, host and user objects](#what-is-the-difference-between-native-host-and-user-objects) |
| 66 | [What are the pros and cons of promises over callbacks](#what-are-the-pros-and-cons-of-promises-over-callbacks) |
| 67 | [Is JavaScript a case-sensitive language](#is-javascript-a-case-sensitive-language) |
| 68 | [What are events](#what-are-events) |
| 69 | [Who created javascript](#who-created-javascript) |
| 70 | [What is the use of preventDefault method](#what-is-the-use-of-preventdefault-method) |
| 71 | [What is the use of stopPropagation method](#what-is-the-use-of-stoppropagation-method) |
| 72 | [What are the steps involved in return false usage](#what-are-the-steps-involved-in-return-false-usage) |
| 73 | [What is BOM](#what-is-bom) |
| 74 | [What is the use of setTimeout](#what-is-the-use-of-settimeout) |
| 75 | [What is the use of setInterval](#what-is-the-use-of-setinterval) |
| 76 | [Why is JavaScript treated as Single threaded](#why-is-javascript-treated-as-single-threaded) |
| 77 | [What is an event delegation](#what-is-an-event-delegation) |
| 78 | [What is ECMAScript](#what-is-ecmascript) |
| 79 | [What is JSON](#what-is-json) |
| 80 | [What are the syntax rules of JSON](#what-are-the-syntax-rules-of-json) |
| 81 | [What is the purpose JSON stringify](#what-is-the-purpose-json-stringify) |
| 82 | [How do you parse JSON string](#how-do-you-parse-json-string) |
| 83 | [Why do you need JSON](#why-do-you-need-json) |
| 84 | [What are PWAs](#what-are-pwas) |
| 85 | [What is the purpose of clearTimeout method](#what-is-the-purpose-of-cleartimeout-method) |
| 86 | [What is the purpose of clearInterval method](#what-is-the-purpose-of-clearinterval-method) |
| 87 | [How do you check whether a string contains a substring](#how-do-you-check-whether-a-string-contains-a-substring) |
| 88 | [How do you validate an email in javascript](#how-do-you-validate-an-email-in-javascript) |
| 89 | [How do you check if a key exists in an object](#how-do-you-check-if-a-key-exists-in-an-object) |
| 90 | [How do you loop through or enumerate javascript object](#how-do-you-loop-through-or-enumerate-javascript-object) |
| 91 | [How do you test for an empty object](#how-do-you-test-for-an-empty-object) |
| 92 | [What is an arguments object](#what-is-an-arguments-object) |
| 93 | [How do you make first letter of the string in an uppercase](#how-do-you-make-first-letter-of-the-string-in-an-uppercase) |
| 94 | [What are the pros and cons of for loops](#what-are-the-pros-and-cons-of-for-loops) |
| 95 | [How do you check if a string starts with another string](#how-do-you-check-if-a-string-starts-with-another-string) |
| 96 | [How do you trim a string in javascript](#how-do-you-trim-a-string-in-javascript) |
| 97 | [How do you add a key value pair in javascript](#how-do-you-add-a-key-value-pair-in-javascript) |
| 98 | [Is the !-- notation represents a special operator](#is-the----notation-represents-a-special-operator) |
| 99 | [How do you assign default values to variables](#how-do-you-assign-default-values-to-variables) |
| 100 | [How do you define multiline strings](#how-do-you-define-multiline-strings) |
| 101 | [What is an app shell model](#what-is-an-app-shell-model) |
| 102 | [Can we define properties for functions](#can-we-define-properties-for-functions) |
| 103 | [What is the way to find the number of parameters expected by a function](#what-is-the-way-to-find-the-number-of-parameters-expected-by-a-function) |
| 104 | [What is a polyfill](#what-is-a-polyfill) |
| 105 | [What are break and continue statements](#what-are-break-and-continue-statements) |
| 106 | [What are js labels](#what-are-js-labels) |
| 107 | [What are the benefits of keeping declarations at the top](#what-are-the-benefits-of-keeping-declarations-at-the-top) |
| 108 | [What are the benefits of initializing variables](#what-are-the-benefits-of-initializing-variables) |
| 109 | [What are the recommendations to create new object](#what-are-the-recommendations-to-create-new-object) |
| 110 | [How do you define JSON arrays](#how-do-you-define-json-arrays) |
| 111 | [How do you generate random integers](#how-do-you-generate-random-integers) |
| 112 | [Can you write a random integers function to print integers within a range](#can-you-write-a-random-integers-function-to-print-integers-within-a-range) |
| 113 | [What is tree shaking](#what-is-tree-shaking) |
| 114 | [What is the need of tree shaking](#what-is-the-need-of-tree-shaking) |
| 115 | [Is it recommended to use eval](#is-it-recommended-to-use-eval) |
| 116 | [What is a Regular Expression](#what-is-a-regular-expression) |
| 117 | [What are the string methods that accept Regular expression](#what-are-the-string-methods-that-accept-regular-expression) |
| 118 | [What are modifiers in regular expression](#what-are-modifiers-in-regular-expression) |
| 119 | [What are regular expression patterns](#what-are-regular-expression-patterns) |
| 120 | [What is a RegExp object](#what-is-a-regexp-object) |
| 121 | [How do you search a string for a pattern](#how-do-you-search-a-string-for-a-pattern) |
| 122 | [What would be the result of 1+2+'3'](#what-would-be-the-result-of-123) |
| 123 | [What is a debugger statement](#what-is-a-debugger-statement) |
| 124 | [What is the purpose of breakpoints in debugging](#what-is-the-purpose-of-breakpoints-in-debugging) |
| 125 | [Can I use reserved words as identifiers](#can-i-use-reserved-words-as-identifiers) |
| 126 | [How do you make synchronous HTTP request](#how-do-you-make-synchronous-http-request) |
| 127 | [How do you make asynchronous HTTP request](#how-do-you-make-asynchronous-http-request) |
| 128 | [What is a conditional operator in javascript](#what-is-a-conditional-operator-in-javascript) |
| 129 | [Can you apply chaining on conditional operator](#can-you-apply-chaining-on-conditional-operator) |
| 130 | [What is the difference between proto and prototype](#what-is-the-difference-between-proto-and-prototype) |
| 131 | [What is the purpose of the freeze method](#what-is-the-purpose-of-the-freeze-method) |
| 132 | [Why do I need to use the freeze method](#why-do-i-need-to-use-the-freeze-method) |
| 133 | [How to convert a string to title case with javascript](#how-to-convert-a-string-to-title-case-with-javascript) |
| 134 | [What are various operators supported by javascript](#what-are-various-operators-supported-by-javascript) |
| 135 | [What is a rest parameter](#what-is-a-rest-parameter) |
| 136 | [What happens if you do not use rest parameter as a last argument](#what-happens-if-you-do-not-use-rest-parameter-as-a-last-argument) |
| 137 | [What are the bitwise operators available in javascript](#what-are-the-bitwise-operators-available-in-javascript) |
| 138 | [What is a spread operator](#what-is-a-spread-operator) |
| 139 | [How do you determine whether object is frozen or not](#how-do-you-determine-whether-object-is-frozen-or-not) |
| 140 | [How do you determine two values same or not using object](#how-do-you-determine-two-values-same-or-not-using-object) |
| 141 | [What is the purpose of using object is method](#what-is-the-purpose-of-using-object-is-method) |
| 142 | [How do you copy properties from one object to other](#how-do-you-copy-properties-from-one-object-to-other) |
| 143 | [What are the applications of the assign method](#what-are-the-applications-of-the-assign-method) |
| 144 | [What is the purpose of the seal method](#what-is-the-purpose-of-the-seal-method) |
| 145 | [What are the applications of the seal method](#what-are-the-applications-of-the-seal-method) |
| 146 | [What are the differences between the freeze and seal methods](#what-are-the-differences-between-the-freeze-and-seal-methods) |
| 147 | [How do you determine if an object is sealed or not](#how-do-you-determine-if-an-object-is-sealed-or-not) |
| 148 | [How do you get enumerable key and value pairs](#how-do-you-get-enumerable-key-and-value-pairs) |
| 149 | [What is the main difference between Object.values and Object.entries method](#what-is-the-main-difference-between-objectvalues-and-objectentries-method) |
| 150 | [How can you get the list of keys of any object](#how-can-you-get-the-list-of-keys-of-any-object) |
| 151 | [How do you create an object with a prototype](#how-do-you-create-an-object-with-a-prototype) |
| 152 | [What is a WeakSet](#what-is-a-weakset) |
| 153 | [What are the differences between WeakSet and Set](#what-are-the-differences-between-weakset-and-set) |
| 154 | [List down the collection of methods available on WeakSet](#list-down-the-collection-of-methods-available-on-weakset) |
| 155 | [What is a WeakMap](#what-is-a-weakmap) |
| 156 | [What are the differences between WeakMap and Map](#what-are-the-differences-between-weakmap-and-map) |
| 157 | [List down the collection of methods available on WeakMap](#list-down-the-collection-of-methods-available-on-weakmap) |
| 158 | [What is the purpose of uneval](#what-is-the-purpose-of-uneval) |
| 159 | [How do you encode an URL](#how-do-you-encode-an-url) |
| 160 | [How do you decode an URL](#how-do-you-decode-an-url) |
| 161 | [How do you print the contents of web page](#how-do-you-print-the-contents-of-web-page) |
| 162 | [What is the difference between uneval and eval](#what-is-the-difference-between-uneval-and-eval) |
| 163 | [What is an anonymous function](#what-is-an-anonymous-function) |
| 164 | [What is the precedence order between local and global variables](#what-is-the-precedence-order-between-local-and-global-variables) |
| 165 | [What are javascript accessors](#what-are-javascript-accessors) |
| 166 | [How do you define property on Object constructor](#how-do-you-define-property-on-object-constructor) |
| 167 | [What is the difference between get and defineProperty](#what-is-the-difference-between-get-and-defineproperty) |
| 168 | [What are the conventions to be followed for the usage of switch case](#what-are-the-conventions-to-be-followed-for-the-usage-of-switch-case) |
| 169 | [What are primitive data types](#what-are-primitive-data-types) |
| 170 | [What are the different ways to access object properties](#what-are-the-different-ways-to-access-object-properties) |
| 171 | [What are the function parameter rules](#what-are-the-function-parameter-rules) |
| 172 | [What is an error object](#what-is-an-error-object) |
| 173 | [When do you get a syntax error](#when-do-you-get-a-syntax-error) |
| 174 | [What are the different error names from error object](#what-are-the-different-error-names-from-error-object) |
| 175 | [What are the various statements in error handling](#what-are-the-various-statements-in-error-handling) |
| 176 | [What are the two types of loops in javascript](#what-are-the-two-types-of-loops-in-javascript) |
| 177 | [What is nodejs](#what-is-nodejs) |
| 178 | [What is the Intl object](#what-is-the-intl-object) |
| 179 | [How do you perform language specific date and time formatting](#how-do-you-perform-language-specific-date-and-time-formatting) |
| 180 | [What is an Iterator](#what-is-an-iterator) |
| 181 | [How does synchronous iteration works](#how-does-synchronous-iteration-works) |
| 182 | [What is the event loop](#what-is-the-event-loop) |
| 183 | [What is the call stack](#what-is-the-call-stack) |
| 184 | [What is the event queue](#what-is-the-event-queue) |
| 185 | [What is a decorator](#what-is-a-decorator) |
| 186 | [What are the properties of the Intl object](#what-are-the-properties-of-the-intl-object) |
| 187 | [What is an Unary operator](#what-is-an-unary-operator) |
| 188 | [How do you sort elements in an array](#how-do-you-sort-elements-in-an-array) |
| 189 | [What is the purpose of compareFunction while sorting arrays](#what-is-the-purpose-of-comparefunction-while-sorting-arrays) |
| 190 | [How do you reverse an array](#how-do-you-reverse-an-array) |
| 191 | [How do you find the min and max values in an array](#how-do-you-find-the-min-and-max-values-in-an-array) |
| 192 | [How do you find the min and max values without Math functions](#how-do-you-find-the-min-and-max-values-without-math-functions) |
| 193 | [What is an empty statement and purpose of it](#what-is-an-empty-statement-and-purpose-of-it) |
| 194 | [How do you get the metadata of a module](#how-do-you-get-the-metadata-of-a-module) |
| 195 | [What is the comma operator](#what-is-the-comma-operator) |
| 196 | [What is the advantage of the comma operator](#what-is-the-advantage-of-the-comma-operator) |
| 197 | [What is typescript](#what-is-typescript) |
| 198 | [What are the differences between javascript and typescript](#what-are-the-differences-between-javascript-and-typescript) |
| 199 | [What are the advantages of typescript over javascript](#what-are-the-advantages-of-typescript-over-javascript) |
| 200 | [What is an object initializer](#what-is-an-object-initializer) |
| 201 | [What is a constructor method](#what-is-a-constructor-method) |
| 202 | [What happens if you write constructor more than once in a class](#what-happens-if-you-write-constructor-more-than-once-in-a-class) |
| 203 | [How do you call the constructor of a parent class](#how-do-you-call-the-constructor-of-a-parent-class) |
| 204 | [How do you get the prototype of an object](#how-do-you-get-the-prototype-of-an-object) |
| 205 | [What happens If I pass string type for getPrototype method](#what-happens-if-i-pass-string-type-for-getprototype-method) |
| 206 | [How do you set the prototype of one object to another](#how-do-you-set-the-prototype-of-one-object-to-another) |
| 207 | [How do you check whether an object can be extended or not](#how-do-you-check-whether-an-object-can-be-extended-or-not) |
| 208 | [How do you prevent an object from being extend](#how-do-you-prevent-an-object-from-being-extend) |
| 209 | [What are the different ways to make an object non-extensible](#what-are-the-different-ways-to-make-an-object-non-extensible) |
| 210 | [How do you define multiple properties on an object](#how-do-you-define-multiple-properties-on-an-object) |
| 211 | [What is obfuscation in javascript](#what-is-obfuscation-in-javascript) |
| 212 | [Why do you need Obfuscation](#why-do-you-need-obfuscation) |
| 213 | [What is Minification](#what-is-minification) |
| 214 | [What are the advantages of minification](#what-are-the-advantages-of-minification) |
| 215 | [What are the differences between obfuscation and Encryption](#what-are-the-differences-between-obfuscation-and-encryption) |
| 216 | [What are the common tools used for minification](#what-are-the-common-tools-used-for-minification) |
| 217 | [How do you perform form validation using javascript](#how-do-you-perform-form-validation-using-javascript) |
| 218 | [How do you perform form validation without javascript](#how-do-you-perform-form-validation-without-javascript) |
| 219 | [What are the DOM methods available for constraint validation](#what-are-the-dom-methods-available-for-constraint-validation) |
| 220 | [What are the available constraint validation DOM properties](#what-are-the-available-constraint-validation-dom-properties) |
| 221 | [What are the validity properties](#what-are-the-validity-properties) |
| 222 | [Give an example usage of the rangeOverflow property](#give-an-example-usage-of-the-rangeoverflow-property) |
| 223 | [Are enums available in javascript](#are-enums-available-in-javascript) |
| 224 | [What is an enum](#what-is-an-enum) |
| 225 | [How do you list all properties of an object](#how-do-you-list-all-properties-of-an-object) |
| 226 | [How do you get property descriptors of an object](#how-do-you-get-property-descriptors-of-an-object) |
| 227 | [What are the attributes provided by a property descriptor](#what-are-the-attributes-provided-by-a-property-descriptor) |
| 228 | [How do you extend classes](#how-do-you-extend-classes) |
| 229 | [How do I modify the url without reloading the page](#how-do-i-modify-the-url-without-reloading-the-page) |
| 230 | [How do you check whether or not an array includes a particular value](#how-do-you-check-whether-or-not-an-array-includes-a-particular-value) |
| 231 | [How do you compare scalar arrays](#how-do-you-compare-scalar-arrays) |
| 232 | [How to get the value from get parameters](#how-to-get-the-value-from-get-parameters) |
| 233 | [How do you print numbers with commas as thousand separators](#how-do-you-print-numbers-with-commas-as-thousand-separators) |
| 234 | [What is the difference between java and javascript](#what-is-the-difference-between-java-and-javascript) |
| 235 | [Does JavaScript support namespaces](#does-javascript-support-namespaces) |
| 236 | [How do you declare a namespace](#how-do-you-declare-a-namespace) |
| 237 | [What is jQuery](#what-is-jquery) |
| 238 | [What is V8 JavaScript engine](#what-is-v8-javascript-engine) |
| 239 | [Why do we call javascript as dynamic language](#why-do-we-call-javascript-as-dynamic-language) |
| 240 | [What is a void operator](#what-is-a-void-operator) |
| 241 | [What is the output of the following for loops](#what-is-the-output-of-the-following-for-loops) |
| 242 | [List down some of the features of ES6](#list-down-some-of-the-features-of-es6) |
| 243 | [What is ES6](#what-is-es6) |
| 244 | [Can I redeclare let and const variables](#can-i-redeclare-let-and-const-variables) |
| 245 | [Does the `const` variable make the value immutable](#does-the-const-variable-make-the-value-immutable) |
| 246 | [What are default parameters](#what-are-default-parameters) |
| 247 | [What are template literals](#what-are-template-literals) |
| 248 | [How do you write multi-line strings in template literals](#how-do-you-write-multi-line-strings-in-template-literals) |
| 249 | [What are nesting templates](#what-are-nesting-templates) |
| 250 | [What are tagged templates](#what-are-tagged-templates) |
| 251 | [What are raw strings](#what-are-raw-strings) |
| 252 | [What is destructuring assignment](#what-is-destructuring-assignment) |
| 253 | [What are default values in destructuring assignment](#what-are-default-values-in-destructuring-assignment) |
| 254 | [How do you swap variables in destructuring assignment](#how-do-you-swap-variables-in-destructuring-assignment) |
| 255 | [What are enhanced object literals](#what-are-enhanced-object-literals) |
| 256 | [What are dynamic imports](#what-are-dynamic-imports) |
| 257 | [What are the use cases for dynamic imports](#what-are-the-use-cases-for-dynamic-imports) |
| 258 | [What are typed arrays](#what-are-typed-arrays) |
| 259 | [What are the advantages of module loaders](#what-are-the-advantages-of-module-loaders) |
| 260 | [What is collation](#what-is-collation) |
| 261 | [What is for...of statement](#what-is-forof-statement) |
| 262 | [What is the output of below spread operator array](#what-is-the-output-of-below-spread-operator-array) |
| 263 | [Is PostMessage secure](#is-postmessage-secure) |
| 264 | [What are the problems with postmessage target origin as wildcard](#what-are-the-problems-with-postmessage-target-origin-as-wildcard) |
| 265 | [What paradigm is Javascript](#what-paradigm-is-javascript) |
| 266 | [What is the difference between internal and external javascript](#what-is-the-difference-between-internal-and-external-javascript) |
| 267 | [What is the purpose of double tilde operator](#what-is-the-purpose-of-double-tilde-operator) |
| 268 | [How do you convert character to ASCII code](#how-do-you-convert-character-to-ascii-code) |
| 269 | [What is ArrayBuffer](#what-is-arraybuffer) |
| 270 | [What is the output of below string expression](#what-is-the-output-of-below-string-expression) |
| 271 | [What is the purpose of Error object](#what-is-the-purpose-of-error-object) |
| 272 | [What is the purpose of EvalError object](#what-is-the-purpose-of-evalerror-object) |
| 273 | [What are the list of cases error thrown from non-strict mode to strict mode](#what-are-the-list-of-cases-error-thrown-from-non-strict-mode-to-strict-mode) |
| 274 | [Do all objects have prototypes](#do-all-objects-have-prototypes) |
| 275 | [What is the difference between a parameter and an argument](#what-is-the-difference-between-a-parameter-and-an-argument) |
| 276 | [What is the purpose of some method in arrays](#what-is-the-purpose-of-some-method-in-arrays) |
| 277 | [How do you combine two or more arrays](#how-do-you-combine-two-or-more-arrays) |
| 278 | [What is the difference between Shallow and Deep copy](#what-is-the-difference-between-shallow-and-deep-copy) |
| 279 | [How do you create specific number of copies of a string](#how-do-you-create-specific-number-of-copies-of-a-string) |
| 280 | [How do you return all matching strings against a regular expression](#how-do-you-return-all-matching-strings-against-a-regular-expression) |
| 281 | [How do you trim a string at the beginning or ending](#how-do-you-trim-a-string-at-the-beginning-or-ending) |
| 282 | [What is the output of below console statement with unary operator](#what-is-the-output-of-below-console-statement-with-unary-operator) |
| 283 | [Does javascript uses mixins](#does-javascript-uses-mixins) |
| 284 | [Mixin Example using Object composition](#mixin-example-using-object-composition) |
| 285 | [Benefits](#benefits) |
| 286 | [What is a thunk function](#what-is-a-thunk-function) |
| 287 | [What are asynchronous thunks](#what-are-asynchronous-thunks) |
| 288 | [What is the output of below function calls](#what-is-the-output-of-below-function-calls) |
| 289 | [How to remove all line breaks from a string](#how-to-remove-all-line-breaks-from-a-string) |
| 290 | [What happens with negating an array](#what-happens-with-negating-an-array) |
| 291 | [What happens if we add two arrays](#what-happens-if-we-add-two-arrays) |
| 292 | [What is the output of prepend additive operator on falsy values](#what-is-the-output-of-prepend-additive-operator-on-falsy-values) |
| 293 | [How do you create self string using special characters](#how-do-you-create-self-string-using-special-characters) |
| 294 | [How do you remove falsy values from an array](#how-do-you-remove-falsy-values-from-an-array) |
| 295 | [How do you get unique values of an array](#how-do-you-get-unique-values-of-an-array) |
| 296 | [What is destructuring aliases](#what-is-destructuring-aliases) |
| 297 | [How do you map the array values without using map method](#how-do-you-map-the-array-values-without-using-map-method) |
| 298 | [How do you empty an array](#how-do-you-empty-an-array) |
| 299 | [How do you round numbers to certain decimals](#how-do-you-round-numbers-to-certain-decimals) |
| 300 | [What is the easiest way to convert an array to an object](#what-is-the-easiest-way-to-convert-an-array-to-an-object) |
| 301 | [How do you create an array with some data](#how-do-you-create-an-array-with-some-data) |
| 302 | [What is the purpose of dir method of console object](#what-is-the-purpose-of-dir-method-of-console-object) |
| 303 | [How do you display data in a tabular format using console object](#how-do-you-display-data-in-a-tabular-format-using-console-object) |
| 303 | [How do you verify that an argument is a Number or not](#how-do-you-verify-that-an-argument-is-a-number-or-not) |
| 304 | [How do you flattening multi dimensional arrays](#how-do-you-flattening-multi-dimensional-arrays) |
| 305 | [What is the easiest multi condition checking](#what-is-the-easiest-multi-condition-checking) |
| 306 | [What are wrapper objects](#what-are-wrapper-objects) |
| 307 | [What is AJAX](#what-is-ajax) |
| 308 | [What are the different ways to deal with Asynchronous Code](#what-are-the-different-ways-to-deal-with-asynchronous-code) |
| 309 | [How to cancel a fetch request](#how-to-cancel-a-fetch-request) |
| 310 | [What is minimum timeout throttling](#what-is-minimum-timeout-throttling) |
| 311 | [What are tasks in event loop](#what-are-tasks-in-event-loop) |
| 312 | [What is microtask](#what-is-microtask) |
| 313 | [What are different event loops](#what-are-different-event-loops) |
| 314 | [What is the purpose of queueMicrotask](#what-is-the-purpose-of-queuemicrotask) |
| 315 | [How do you use javascript libraries in typescript file](#how-do-you-use-javascript-libraries-in-typescript-file) |
| 316 | [What are the differences between promises and observables](#what-are-the-differences-between-promises-and-observables) |
| 317 | [What is heap](#what-is-heap) |
| 318 | [What is an event table](#what-is-an-event-table) |
| 319 | [What is a microTask queue](#what-is-a-microtask-queue) |
| 320 | [What is the difference between shim and polyfill](#what-is-the-difference-between-shim-and-polyfill) |
| 321 | [How do you detect primitive or non primitive value type](#how-do-you-detect-primitive-or-non-primitive-value-type) |
| 322 | [What is babel](#what-is-babel) |
| 323 | [Is Node.js completely single threaded](#is-nodejs-completely-single-threaded) |
| 324 | [What are the common use cases of observables](#what-are-the-common-use-cases-of-observables) |
| 325 | [What is RxJS](#what-is-rxjs) |
| 326 | [What is the difference between Function constructor and function declaration](#what-is-the-difference-between-function-constructor-and-function-declaration) |
| 327 | [What is a Short circuit condition](#what-is-a-short-circuit-condition) |
| 328 | [What is the easiest way to resize an array](#what-is-the-easiest-way-to-resize-an-array) |
| 329 | [What is an observable](#what-is-an-observable) |
| 330 | [What is the difference between function and class declarations](#what-is-the-difference-between-function-and-class-declarations) |
| 331 | [What is an async function](#what-is-an-async-function) |
| 332 | [How do you prevent promises swallowing errors](#how-do-you-prevent-promises-swallowing-errors) |
| 333 | [What is deno](#what-is-deno) |
| 334 | [How do you make an object iterable in javascript](#how-do-you-make-an-object-iterable-in-javascript) |
| 335 | [What is a Proper Tail Call](#what-is-a-proper-tail-call) |
| 336 | [How do you check an object is a promise or not](#how-do-you-check-an-object-is-a-promise-or-not) |
| 337 | [How to detect if a function is called as constructor](#how-to-detect-if-a-function-is-called-as-constructor) |
| 338 | [What are the differences between arguments object and rest parameter](#what-are-the-differences-between-arguments-object-and-rest-parameter) |
| 339 | [What are the differences between spread operator and rest parameter](#what-are-the-differences-between-spread-operator-and-rest-parameter) |
| 340 | [What are the different kinds of generators](#what-are-the-different-kinds-of-generators) |
| 341 | [What are the built-in iterables](#what-are-the-built-in-iterables) |
| 342 | [What are the differences between for...of and for...in statements](#what-are-the-differences-between-forof-and-forin-statements) |
| 343 | [How do you define instance and non-instance properties](#how-do-you-define-instance-and-non-instance-properties) |
| 345 | [What is the difference between isNaN and Number.isNaN?](#what-is-the-difference-between-isnan-and-numberisnan) |
| 346 | [How to invoke an IIFE without any extra brackets?](#how-to-invoke-an-iife-without-any-extra-brackets) |
| 347 | [Is that possible to use expressions in switch cases?](#is-that-possible-to-use-expressions-in-switch-cases) |
| 348 | [What is the easiest way to ignore promise errors?](#what-is-the-easiest-way-to-ignore-promise-errors) |
| 349 | [What is nullish coalescing operator (??)?](#what-is-nullish-coalescing-operator-) |
| 350 | [What is the difference between dense and sparse arrays?](#what-is-the-difference-between-dense-and-sparse-arrays) |
| 351 | [What are the different ways to create sparse arrays?](#what-are-the-different-ways-to-create-sparse-arrays) |
| 352 | [What is the difference between setTimeout, setImmediate and process.nextTick?](#what-is-the-difference-between-settimeout-setimmediate-and-processnexttick) |
| 353 | [How do you reverse an array without modifying original array?](#how-do-you-reverse-an-array-without-modifying-original-array) |
| 354 | [What is global execution context?](#what-is-global-execution-context) |
| 355 | [What is function execution context?](#what-is-function-execution-context) |
| 356 | [What is debouncing?](#what-is-debouncing) |
| 357 | [What is throttling?](#what-is-throttling) |
| 358 | [What is optional chaining?](#what-is-optional-chaining) |
| 359 | [How to verify if a variable is an array?](#how-to-verify-if-a-variable-is-an-array) |
| 360 | [What is pass by value and pass by reference?](#what-is-pass-by-value-and-pass-by-reference) |
| 361 | [What are the differences between primitives and non-primitives?](#what-are-the-differences-between-primitives-and-non-primitives) |
| 362 | [How do you create your own bind method using either call or apply method?](#how-do-you-create-your-own-bind-method-using-either-call-or-apply-method) |
| 363 | [What are the differences between pure and impure functions?](#what-are-the-differences-between-pure-and-impure-functions) |
| 364 | [What is referential transparency?](#what-is-referential-transparency) |
| 365 | [What are the possible side-effects in javascript?](#what-are-the-possible-side-effects-in-javascript) |
| 366 | [What are compose and pipe functions?](#what-are-compose-and-pipe-functions) |
| 367 | [What is module pattern?](#what-is-module-pattern) |
| 368 | [What is Function Composition?](#what-is-function-composition) |
| 369 | [How to use await outside of async function prior to ES2022?](#how-to-use-await-outside-of-async-function-prior-to-es2022) |
| 370 | [What is the purpose of the this keyword in JavaScript?](#what-is-the-purpose-of-the-this-keyword-in-javascript) |
| 371 | [What are the uses of closures?](#what-are-the-uses-of-closures) |
| 372 | [What are the phases of execution context?](#what-are-the-phases-of-execution-context) |
| 373 | [What are the possible reasons for memory leaks?](#what-are-the-possible-reasons-for-memory-leaks) |
| 374 | [What are the optimization techniques of V8 engine?](#what-are-the-optimization-techniques-of-v8-engine) |
| 375 | [What are the examples of built-in higher order functions?](#what-are-the-examples-of-built-in-higher-order-functions) |
| 376 | [What are the benefits higher order functions?](#what-are-the-benefits-higher-order-functions) |
| 377 | [How do you create polyfills for map, filter and reduce methods?](#how-do-you-create-polyfills-for-map-filter-and-reduce-methods) |
| 378 | [What is the difference between map and forEach functions?](#what-is-the-difference-between-map-and-foreach-functions) |
| 379 | [What are hidden classes?](#what-are-hidden-classes) |
| 380 | [What is inline caching?](#what-is-inline-caching) |
| 381 | [What are the different ways to execute external scripts?](#what-are-the-different-ways-to-execute-external-scripts) |
| 382 | [What is Lexical Scope?](#what-is-lexical-scope) |
| 383 | [What is the purpose of requestAnimationFrame method?](#what-is-the-purpose-of-requestanimationframe-method) |
| 384 | [What is the difference between substring and substr methods?](#what-is-the-difference-between-substring-and-substr-methods) |
| 385 | [How to find the number of parameters expected by a function?](#how-to-find-the-number-of-parameters-expected-by-a-function) |
| 386 | [What is globalThis, and what is the importance of it?](#what-is-globalthis-and-what-is-the-importance-of-it) |
| 387 | [What are the array mutation methods?](#what-are-the-array-mutation-methods) |
| 388 | [What is module scope in JavaScript?](#what-is-module-scope-in-javascript) |
| 389 | [What are shadowing and illegal shadowing?](#what-are-shadowing-and-illegal-shadowing) |
| 390 | [Why is it important to remove event listeners after use?](#why-is-it-important-to-remove-event-listeners-after-use) |
<!-- TOC_END -->

<!-- QUESTIONS_START -->

1. ### What are the possible ways to create objects in JavaScript

    There are many ways to create objects in javascript as mentioned below:

    1. **Object literal syntax:**

       The object literal syntax (or object initializer), is a comma-separated set of name-value pairs wrapped in curly braces.

       ```javascript
       var object = {
         name: "Sudheer",
         age: 34,
       };
       ```

       Object literal property values can be of any data type, including array, function, and nested object.

       **Note:** This is one of the easiest ways to create an object and it's most commonly used for creating simple, ad-hoc objects.

    2. **Object constructor:**

       The simplest way to create an empty object is using the `Object` constructor. Currently this approach is not recommended.

       ```javascript
       var object = new Object();
       ```

       The `Object()` is a built-in constructor function so "new" keyword is not required for creating plain objects. The above code snippet can be re-written as:

       ```javascript
       var object = Object();
       ```
       However, `Object()` can be used to either create a plain object or convert a given value into its corresponding object wrapper, whereas `new Object()` is specifically used to explicitly create a new object instance.
       
    3. **Object's create method:**

       The `create` method of Object is used to create a new object by passing the specified prototype object and properties as arguments, i.e., this pattern is helpful to create new objects based on existing objects. In other words, this is useful for setting up **prototypal inheritance**. The second argument is optional and it is used to create properties on a newly created object.

       The following code creates a new empty object whose prototype is null.

       ```javascript
       var object = Object.create(null);
       ```

       The following example creates an object along with additional new properties.

       ```javascript
       let vehicle = {
         wheels: "4",
         fuelType: "Gasoline",
         color: "Green",
       };
       let carProps = {
         type: {
           value: "Volkswagen",
         },
         model: {
           value: "Golf",
         },
       };

       var car = Object.create(vehicle, carProps);
       console.log(car);
       ```

    4. **Function constructor:**

       In this approach, create any function and apply the new operator to create object instances. This was the main way to do constructor-based OOP before ES6 classes.

       ```javascript
       function Person(name) {
         this.name = name;
         this.age = 21;
       }
       var object = new Person("Sudheer");
       ```
    5. **Function constructor with prototype:**

       This is similar to function constructor but it uses prototype for their properties and methods. Using prototype means you're sharing methods/properties across instances, which saves memory and improve performance.

       ```javascript
       function Person() {}
       Person.prototype.name = "Sudheer";
       var object = new Person();
       ```

       This is equivalent to creating an instance with `Object.create` method with a function prototype and then calling that function with an instance and parameters as arguments.

       ```javascript
       function func(x, y, z) {
        this.x = x;
        this.y = y;
        this.z = z;
       }

       var instance = new func(1, 2, 3);
       ```

       **(OR)**

       ```javascript
       function func(x, y, z) {
          this.x = x;
          this.y = y;
          this.z = z;
       }
       // Create a new instance using function prototype.
       var newInstance = Object.create(func.prototype)

       // Call the function
       var result = func.call(newInstance, 1, 2, 3),

       // If the result is a non-null object then use it otherwise just use the new instance.
       console.log(result && typeof result === 'object' ? result : newInstance);
       ```

    6. **Object's assign method:**

       The `Object.assign` method is used to copy all the properties from one or more source objects and stores them into a target object. This is mainly used for cloning and merging

       The following code creates a new staff object by copying properties of his working company and the car he owns.

       ```javascript
       const orgObject = { company: "XYZ Corp" };
       const carObject = { name: "Toyota" };
       const staff = Object.assign({}, orgObject, carObject);
       ```

    7. **ES6 Class syntax:**

       ES6 introduces class feature to create objects. This is syntactic sugar over the prototype-based system.

       ```javascript
       class Person {
         constructor(name) {
           this.name = name;
         }
       }

       var object = new Person("Sudheer");
       ```

    8. **Singleton pattern:**

       A Singleton is an object which can only be instantiated one time. Repeated calls to its constructor return the same instance. This way one can ensure that they don't accidentally create multiple instances.

        ##### Singleton with Closure (Classic JS Pattern)
        ```javascript
        const Singleton = (function () {
        let instance;

        function createInstance() {
          return { name: "Sudheer" };
        }

        return {
          getInstance: function () {
            if (!instance) {
              instance = createInstance();
            }
            return instance;
          }
        };
        })();

        // Usage
        const obj1 = Singleton.getInstance();
        const obj2 = Singleton.getInstance();

        console.log(obj1 === obj2); // true
        ```
         In modern JavaScript applications, singletons are commonly implemented using ES6 modules for their built-in caching behavior, or closures for encapsulated state management.

      **[⬆ Back to Top](#table-of-contents)**

2. ### What is a prototype chain

    The prototype chain is a core concept in JavaScript’s inheritance model. It allows objects to inherit properties and methods from other objects. When you try to access a property or method on an object, JavaScript first looks for it on that object itself. If it’s not found, the engine looks up the object's internal `[[Prototype]]` reference (accessible via `Object.getPrototypeOf(obj)` or the deprecated `__proto__` property) and continues searching up the chain until it finds the property or reaches the end (usually `null`).

    For objects created via constructor functions, the prototype chain starts with the instance, then refers to the constructor’s `.prototype` object, and continues from there. For example:

    ```javascript
    function Person() {}
    const person1 = new Person();

    console.log(Object.getPrototypeOf(person1) === Person.prototype); // true
    ```

    This mechanism allows for property and method sharing among objects, enabling code reuse and a form of inheritance.

    **Summary:**

    *   The prototype chain enables inheritance in JavaScript.
    *   If a property isn’t found on an object, JavaScript looks up its prototype chain.
    *   The prototype of an object instance can be accessed with `Object.getPrototypeOf(obj)` or `__proto__`.
    *   The prototype of a constructor function is available via `Constructor.prototype`.
    *   The chain ends when the prototype is `null`.

    The prototype chain among objects appears as below, 
    
    ![Screenshot](images/prototype_chain.png)

    **[⬆ Back to Top](#table-of-contents)**

3. ### What is JSON and its common operations

    **JSON (JavaScript Object Notation)** is a lightweight, text-based data format that uses JavaScript object syntax for structuring data. It was popularized by Douglas Crockford and is widely used for transmitting data between a server and a client in web applications. JSON files typically have a `.json` extension and use the MIME type `application/json`. 

    #### Common Operations with JSON

    1. **Parsing**: Transforming a JSON-formatted string into a native JavaScript object.
      ```js
      const obj = JSON.parse(jsonString);
      ```
      - Example:  
        ```js
        const jsonString = '{"name":"John","age":30}';
        const obj = JSON.parse(jsonString);  // { name: "John", age: 30 }
        ```

    2. **Stringification**: Converting a JavaScript object into a JSON-formatted string, commonly used for data transmission or storage.
      ```js
      const jsonString = JSON.stringify(object);
      ```
      - Example:  
        ```js
        const obj = { name: "Jane", age: 25 };
        const jsonString = JSON.stringify(obj);  // '{"name":"Jane","age":25}'
        ```

    **[⬆ Back to Top](#table-of-contents)**

4. ### What is the purpose of the array slice method

    The `slice()` method in JavaScript is used to extract a section of an array, returning a new array containing the selected elements. It does not modify the original array. The method takes two arguments:

    - **start**: The index at which extraction begins (inclusive).
    - **end** (optional): The index before which to end extraction (exclusive). If omitted, extraction continues to the end of the array.

    You can also use negative indices, which count from the end of the array.

    #### Examples:

    ```js
    let arrayIntegers = [1, 2, 3, 4, 5];

    let arrayIntegers1 = arrayIntegers.slice(0, 2);    // [1, 2]
    let arrayIntegers2 = arrayIntegers.slice(2, 3);    // [3]
    let arrayIntegers3 = arrayIntegers.slice(4);       // [5]
    let arrayIntegers4 = arrayIntegers.slice(-3, -1);  // [3, 4]
    ```

    **Note:**  
    The `slice()` method does **not** mutate (change) the original array; instead, it returns a new array containing the extracted elements.

    **[⬆ Back to Top](#table-of-contents)**

5. ### What is the purpose of the array splice method

    The `splice()` method in JavaScript is used to add, remove, or replace elements within an array. Unlike `slice()`, which creates a shallow copy and does not alter the original array, `splice()` **modifies the original array in place** and returns an array containing the removed elements.

    #### Syntax

    ```javascript
    array.splice(start, deleteCount, item1, item2, ...)
    ```
    - **start:** The index at which to start changing the array.
    - **deleteCount:** (Optional) The number of elements to remove from the array. If omitted, all elements from the start index to the end of the array will be removed.
    - **item1, item2, ...:** (Optional) Elements to add to the array, starting at the start position.

    #### Examples

    ```javascript
    let arrayIntegersOriginal1 = [1, 2, 3, 4, 5];
    let arrayIntegersOriginal2 = [1, 2, 3, 4, 5];
    let arrayIntegersOriginal3 = [1, 2, 3, 4, 5];

    // Remove the first two elements
    let arrayIntegers1 = arrayIntegersOriginal1.splice(0, 2); 
    // arrayIntegers1: [1, 2]
    // arrayIntegersOriginal1 (after): [3, 4, 5]

    // Remove all elements from index 3 onwards
    let arrayIntegers2 = arrayIntegersOriginal2.splice(3);     
    // arrayIntegers2: [4, 5]
    // arrayIntegersOriginal2 (after): [1, 2, 3]

    // Remove 1 element at index 3, then insert "a", "b", "c" at that position
    let arrayIntegers3 = arrayIntegersOriginal3.splice(3, 1, "a", "b", "c"); 
    // arrayIntegers3: [4]
    // arrayIntegersOriginal3 (after): [1, 2, 3, "a", "b", "c", 5]
    ```

    **Note:**  
    - The `splice()` method **modifies the original array**.
    - It returns an array containing the elements that were removed (if any).
    - You can use it both to remove and insert elements in a single operation.

    **[⬆ Back to Top](#table-of-contents)**

6. ### What is the difference between slice and splice
   
    Here are the key differences between `slice()` and `splice()` methods in JavaScript arrays:

    | `slice()`                                         | `splice()`                                          |
    | ------------------------------------------------- | --------------------------------------------------- |
    | Does **not** modify the original array (immutable) | Modifies the original array (mutable)               |
    | Returns a **shallow copy** (subset) of selected elements | Returns an array of the **removed** elements           |
    | Used to **extract** elements from an array         | Used to **add**, **remove**, or **replace** elements in an array |
    | Syntax: `array.slice(start, end)`                  | Syntax: `array.splice(start, deleteCount, ...items)`             |

    **Summary:**  
    - Use `slice()` when you want to copy or extract elements without altering the original array.
    - Use `splice()` when you need to add, remove, or replace elements and want to change the original array.

    **[⬆ Back to Top](#table-of-contents)**

7. ### How do you compare Object and Map

    **Objects** and **Maps** both allow you to associate keys with values, retrieve those values, delete keys, and check if a key exists. Historically, Objects have been used as Maps, but there are several key differences that make `Map` a better choice in certain scenarios:

    | Feature                  | Object                                              | Map                                                      |
    |--------------------------|-----------------------------------------------------|----------------------------------------------------------|
    | **Key Types**            | Only strings and symbols are valid keys             | Any value can be used as a key (objects, functions, primitives) |
    | **Key Order**            | Keys are unordered (in practice, insertion order is mostly preserved for string keys, but not guaranteed) | Keys are ordered by insertion; iteration follows insertion order |
    | **Size Property**        | No built-in way to get the number of keys; must use `Object.keys(obj).length` | Use the `.size` property for the number of entries        |
    | **Iterability**          | Not directly iterable; must use `Object.keys`, `Object.values`, or `Object.entries` | Directly iterable with `for...of`, `.keys()`, `.values()`, `.entries()` |
    | **Prototype**            | Has a prototype chain; may have default properties that can collide with custom keys (can be avoided with `Object.create(null)`) | Does not have a prototype, so there are no default keys   |
    | **Performance**          | May be less efficient for frequent additions/removals | Optimized for frequent additions and deletions            |
    | **Serialization**        | Can be easily serialized to JSON                    | Cannot be directly serialized to JSON                     |

    **[⬆ Back to Top](#table-of-contents)**

8. ### What are lambda expressions or arrow functions

    **Arrow functions** (also known as "lambda expressions") provide a concise syntax for writing function expressions in JavaScript. Introduced in ES6, arrow functions are often shorter and more readable, especially for simple operations or callbacks.

    #### Key Features:
    - Arrow functions do **not** have their own `this`, `arguments`, `super`, or `new.target` bindings. They inherit these from their surrounding (lexical) context.
    - They are best suited for non-method functions, such as callbacks or simple computations.
    - Arrow functions **cannot** be used as constructors and do not have a `prototype` property.
    - They also cannot be used with `new`, `yield`, or as generator functions.

    #### Syntax Examples:

    ```javascript
    const arrowFunc1 = (a, b) => a + b;    // Multiple parameters, returns a + b
    const arrowFunc2 = a => a * 10;        // Single parameter (parentheses optional), returns a * 10
    const arrowFunc3 = () => {};           // No parameters, returns undefined
    const arrowFunc4 = (a, b) => {
      // Multiple statements require curly braces and explicit return
      const sum = a + b;
      return sum * 2;
    };
    ```

    **[⬆ Back to Top](#table-of-contents)**

9. ### What is a first class function

    In JavaScript, **first-class functions(first-class citizens)** mean that functions are treated like any other variable. That means:

    1. You can assign a function to a variable.
    2. You can pass a function as an argument to another function.
    3. You can return a function from another function.

    This capability enables powerful patterns like callbacks, higher-order functions, event handling, and functional programming in JavaScript.
    
    For example, the handler function below is assigned to a variable and then passed as an argument to the `addEventListener` method.

    ```javascript
    const handler = () => console.log("This is a click handler function");
    document.addEventListener("click", handler);
    ```

    **[⬆ Back to Top](#table-of-contents)**

10. ### What is a first order function

    A first-order function is a function that doesn’t accept another function as an argument and doesn’t return a function as its return value. i.e,  It's a regular function that works with primitive or non-function values.

    ```javascript
    const firstOrder = () => console.log("I am a first order function!");
    ```

    **[⬆ Back to Top](#table-of-contents)**

11. ### What is a higher order function

    A higher-order function is a function that either accepts another function as an argument, returns a function as its result, or both. This concept is a core part of JavaScript's functional programming capabilities and is widely used for creating modular, reusable, and expressive code.

    The syntactic structure of higher order function will be explained with an example as follows,

      ```javascript
      // First-order function (does not accept or return another function)
      const firstOrderFunc = () => 
        console.log("Hello, I am a first-order function");

      // Higher-order function (accepts a function as an argument)
      const higherOrder = (callback) => callback();

      // Passing the first-order function to the higher-order function
      higherOrder(firstOrderFunc);
      ```

    In this example:

    1. `firstOrderFunc` is a regular (first-order) function.

    2. `higherOrder` is a higher-order function because it takes another function as an argument.

    3. `firstOrderFunc` is also called a **callback function** because it is passed to and executed by another function.

    **[⬆ Back to Top](#table-of-contents)**

12. ### What is the currying function
    
    **Currying** is the process of transforming a function with **multiple arguments** into a sequence of **nested functions**, each accepting **only one argument** at a time.

    This concept is named after mathematician **Haskell Curry**, and is commonly used in functional programming to enhance modularity and reuse.


    ## Before Currying (Normal n-ary Function)

    ```javascript
    const multiArgFunction = (a, b, c) => a + b + c;

    console.log(multiArgFunction(1, 2, 3)); // Output: 6
    ```
    This is a standard function that takes three arguments at once.

    ## After Currying (Unary Function Chain)
    ```javascript
    const curryUnaryFunction = (a) => (b) => (c) => a + b + c;

    console.log(curryUnaryFunction(1));       // Returns: function (b) => ...
    console.log(curryUnaryFunction(1)(2));    // Returns: function (c) => ...
    console.log(curryUnaryFunction(1)(2)(3)); // Output: 6

    ```
    Each function in the chain accepts one argument and returns the next function, until all arguments are provided and the final result is computed.

    ## Benefits of Currying
      - Improves code reusability
      → You can partially apply functions with known arguments.

      - Enhances functional composition
      → Easier to compose small, pure functions.

      - Encourages clean, modular code
      → You can split logic into smaller single-responsibility functions.

    **[⬆ Back to Top](#table-of-contents)**

13. ### What is a pure function

    A **pure function** is a function whose output depends only on its input arguments and produces no side effects. This means that given the same inputs, a pure function will always return the same output, and it does not modify any external state or data.

    Let's take an example to see the difference between pure and impure functions,

    #### Example: Pure vs. Impure Functions

    ```javascript
    // Impure Function
    let numberArray = [];
    const impureAddNumber = (number) => numberArray.push(number);

    // Pure Function
    const pureAddNumber = (number) => (inputArray) =>
      inputArray.concat([number]);

    // Usage
    console.log(impureAddNumber(6)); // returns 1
    console.log(numberArray);        // returns [6]

    console.log(pureAddNumber(7)(numberArray)); // returns [6, 7]
    console.log(numberArray);                   // remains [6]
    ```
    - `impureAddNumber` changes the external variable numberArray and returns the new length of the array, making it impure.
    - `pureAddNumber` creates a new array with the added number and does not modify the original array, making it pure.

14. ### What are the benefits of pure functions
    Some of the major benefits of pure functions are listed below,

    - **Easier testing:** Since output depends only on input, pure functions are simple to test.
    - **Predictability:** No hidden side effects make behavior easier to reason about.
    - **Immutability:** Pure functions align with ES6 best practices, such as preferring const over let, supporting safer and more maintainable code.
    - **No side effects:** Reduces bugs related to shared state or mutation.

    **[⬆ Back to Top](#table-of-contents)**

15. ### What is the reason to choose the name let as a keyword

    The keyword `let` was chosen because it originates from mathematical notation, where "let" is used to introduce new variables (for example, "let x = 5"). This term was adopted by several early programming languages such as Scheme and BASIC, establishing a tradition in computer science. JavaScript follows this convention by using `let` to declare variables with block scope, providing a modern alternative to `var`. The choice helps make the language more familiar to programmers coming from other languages and aligns with the mathematical practice of variable assignment.

    **[⬆ Back to Top](#table-of-contents)**

16. ### How do you decode or encode a URL in JavaScript?

    `encodeURI()` function is used to encode an URL. This function requires a URL string as a parameter and return that encoded string.
    `decodeURI()` function is used to decode an URL. This function requires an encoded URL string as parameter and return that decoded string.

    **Note:** If you want to encode characters such as `/ ? : @ & = + $ #` then you need to use `encodeURIComponent()`.

    ```javascript
    let uri = "employeeDetails?name=john&occupation=manager";
    let encoded_uri = encodeURI(uri);
    let decoded_uri = decodeURI(encoded_uri);
    ```

    **[⬆ Back to Top](#table-of-contents)**

17. ### What is memoization

    Memoization is a functional programming technique which attempts to increase a function’s performance by caching its previously computed results. Each time a memoized function is called, its parameters are used to index the cache. If the data is present, then it can be returned, without executing the entire function. Otherwise the function is executed and then the result is added to the cache.
    Let's take an example of adding function with memoization,

    ```javascript
    const memoizeAddition = () => {
      let cache = {};
      return (value) => {
        if (value in cache) {
          console.log("Fetching from cache");
          return cache[value]; // Here, cache.value cannot be used as property name starts with the number which is not a valid JavaScript  identifier. Hence, can only be accessed using the square bracket notation.
        } else {
          console.log("Calculating result");
          let result = value + 20;
          cache[value] = result;
          return result;
        }
      };
    };
    // returned function from memoizeAddition
    const addition = memoizeAddition();
    console.log(addition(20)); //output: 40 calculated
    console.log(addition(20)); //output: 40 cached
    ```

    **[⬆ Back to Top](#table-of-contents)**

18. ### What are classes in ES6

    In ES6, Javascript classes are primarily syntactic sugar over JavaScript’s existing prototype-based inheritance.
    For example, the prototype based inheritance written in function expression as below,

    ```javascript
    function Bike(model, color) {
      this.model = model;
      this.color = color;
    }

    Bike.prototype.getDetails = function () {
      return this.model + " bike has" + this.color + " color";
    };
    ```

    Whereas ES6 classes can be defined as an alternative

    ```javascript
    class Bike {
      constructor(color, model) {
        this.color = color;
        this.model = model;
      }

      getDetails() {
        return this.model + " bike has" + this.color + " color";
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

19. ### What are closures

    A closure is the combination of a function bundled(enclosed) together with its lexical environment within which that function was declared. i.e, It is an inner function that has access to the outer or enclosing function’s variables, functions and other data even after the outer function has finished its execution. The closure has three scope chains.

    1. Own scope where variables defined between its curly brackets
    2. Outer function's variables
    3. Global variables

    Let's take an example of closure concept,

    ```javascript
    function Welcome(name) {
      var greetingInfo = function (message) {
        console.log(message + " " + name);
      };
      return greetingInfo;
    }
    var myFunction = Welcome("John");
    myFunction("Welcome "); //Output: Welcome John
    myFunction("Hello Mr."); //output: Hello Mr. John
    ```

    As per the above code, the inner function(i.e, greetingInfo) has access to the variables in the outer function scope(i.e, Welcome) even after the outer function has returned.

    **[⬆ Back to Top](#table-of-contents)**

20. ### What are modules

    Modules refer to small units of independent, reusable code and also act as the foundation of many JavaScript design patterns. Most of the JavaScript modules export an object literal, a function, or a constructor

    **[⬆ Back to Top](#table-of-contents)**

21. ### Why do you need modules

    Below are the list of benefits using modules in javascript ecosystem

    1. Maintainability
    2. Reusability
    3. Namespacing

    **[⬆ Back to Top](#table-of-contents)**

22. ### Why do you need a promise
    Promises are **used to handle asynchronous operations**, especially in languages like JavaScript, which often work with non-blocking operations such as network requests, file I/O, and timers. When an operation is asynchronous, it doesn't immediately return a result; instead, it works in the background and provides the result later. Handling this in a clean, organized way can be difficult without a structured approach.

    Promises are used to:

    1.  **Handle asynchronous operations**.
    2.  **Provide a cleaner alternative to callbacks**.
    3.  **Avoid callback hell**.
    4.  **Make code more readable and maintainable**.

    **[⬆ Back to Top](#table-of-contents)**

23. ### Explain the three states of promise

    Promises have three states:

    1. **Pending:** This is an initial state of the Promise before an operation begins
    2. **Fulfilled:** This state indicates that the specified operation was completed.
    3. **Rejected:** This state indicates that the operation did not complete. In this case an error value will be thrown.

    **[⬆ Back to Top](#table-of-contents)**

24. ### What is a callback function

    A callback function is a function passed into another function as an argument. This function is invoked inside the outer function to complete an action.
    Let's take a simple example of how to use callback function

    ```javascript
    function callbackFunction(name) {
      console.log("Hello " + name);
    }

    function outerFunction(callback) {
      let name = prompt("Please enter your name.");
      callback(name);
    }

    outerFunction(callbackFunction);
    ```

    **[⬆ Back to Top](#table-of-contents)**

25. ### Why do we need callbacks

    The callbacks are needed because javascript is an event driven language. That means instead of waiting for a response, javascript will keep executing while listening for other events.
    Let's take an example with the first function invoking an API call(simulated by setTimeout) and the next function which logs the message.

    ```javascript
    function firstFunction() {
      // Simulate a code delay
      setTimeout(function () {
        console.log("First function called");
      }, 1000);
    }
    function secondFunction() {
      console.log("Second function called");
    }
    firstFunction();
    secondFunction();

    // Output:
    // Second function called
    // First function called
    ```

    As observed from the output, javascript didn't wait for the response of the first function and the remaining code block got executed. So callbacks are used in a way to make sure that certain code doesn’t execute until the other code finishes execution.

    **[⬆ Back to Top](#table-of-contents)**

26. ### What is a callback hell

    Callback Hell is an anti-pattern with multiple nested callbacks which makes code hard to read and debug when dealing with asynchronous logic. The callback hell looks like below,

    ```javascript
    async1(function(){
        async2(function(){
            async3(function(){
                async4(function(){
                    ....
                });
            });
        });
    });
    ```

    **[⬆ Back to Top](#table-of-contents)**

27. ### What are the events available for server sent events

    Below are the list of events available for server sent events
    | Event | Description |
    |---- | ---------
    | onopen | It is used when a connection to the server is opened |
    | onmessage | This event is used when a message is received |
    | onerror | It happens when an error occurs|

    **[⬆ Back to Top](#table-of-contents)**

28. ### What are the main rules of promise

    A promise must follow a specific set of rules:

    1. A promise is an object that supplies a standard-compliant `.then()` method
    2. A pending promise may transition into either fulfilled or rejected state
    3. A fulfilled or rejected promise is settled and it must not transition into any other state.
    4. Once a promise is settled, the value must not change.

    **[⬆ Back to Top](#table-of-contents)**

29. ### What is callback in callback

    You can nest one callback inside in another callback to execute the actions sequentially one by one. This is known as callbacks in callbacks. Beware, too many levels of nesting lead to [Callback hell](https://github.com/sudheerj/javascript-interview-questions?tab=readme-ov-file#what-is-a-callback-hell)

    ```javascript
    loadScript("/script1.js", function (script) {
      console.log("first script is loaded");

      loadScript("/script2.js", function (script) {
        console.log("second script is loaded");

        loadScript("/script3.js", function (script) {
          console.log("third script is loaded");
          // after all scripts are loaded
        });
      });
    });
    ```

    **[⬆ Back to Top](#table-of-contents)**

30. ### What is promise chaining

    The process of executing a sequence of asynchronous tasks one after another using promises is known as Promise chaining. Let's take an example of promise chaining for calculating the final result,

    ```javascript
    new Promise(function (resolve, reject) {
      setTimeout(() => resolve(1), 1000);
    })
      .then(function (result) {
        console.log(result); // 1
        return result * 2;
      })
      .then(function (result) {
        console.log(result); // 2
        return result * 3;
      })
      .then(function (result) {
        console.log(result); // 6
        return result * 4;
      });
    ```

    In the above handlers, the result is passed to the chain of .then() handlers with the below work flow,

    1. The initial promise resolves in 1 second,
    2. After that `.then` handler is called by logging the result(1) and then return a promise with the value of result \* 2.
    3. After that the value passed to the next `.then` handler by logging the result(2) and return a promise with result \* 3.
    4. Finally the value passed to the last `.then` handler by logging the result(6) and return a promise with result \* 4.

    **[⬆ Back to Top](#table-of-contents)**

31. ### What is promise.all

    Promise.all is a promise that takes an array of promises as an input (an iterable), and it gets resolved when all the promises get resolved or any one of them gets rejected. For example, the syntax of promise.all method is below,

    ```javascript
    Promise.all([Promise1, Promise2, Promise3]) .then(result) => {   console.log(result) }) .catch(error => console.log(`Error in promises ${error}`))
    ```

    **Note:** Remember that the order of the promises(output the result) is maintained as per input order.

    **[⬆ Back to Top](#table-of-contents)**

32. ### What is the purpose of the race method in promise

    Promise.race() method will return the promise instance which is firstly resolved or rejected. Let's take an example of race() method where promise2 is resolved first

    ```javascript
    var promise1 = new Promise(function (resolve, reject) {
      setTimeout(resolve, 500, "one");
    });
    var promise2 = new Promise(function (resolve, reject) {
      setTimeout(resolve, 100, "two");
    });

    Promise.race([promise1, promise2]).then(function (value) {
      console.log(value); // "two" // Both promises will resolve, but promise2 is faster
    });
    ```

    **[⬆ Back to Top](#table-of-contents)**

33. ### How do you declare strict mode

    The strict mode is declared by adding "use strict"; to the beginning of a script or a function.
    If declared at the beginning of a script, it has global scope.

    ```javascript
    "use strict";
    x = 3.14; // This will cause an error because x is not declared
    ```

    and if you declare inside a function, it has local scope

    ```javascript
    x = 3.14; // This will not cause an error.
    myFunction();

    function myFunction() {
      "use strict";
      y = 3.14; // This will cause an error
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

34. ### What is the purpose of double exclamation

    The double exclamation or negation(!!) ensures the resulting type is a boolean. If it was falsey (e.g. 0, null, undefined, etc.), it will be false, otherwise, it will be true.
    For example, you can test IE version using this expression as below,

    ```javascript
    let isIE8 = false;
    isIE8 = !!navigator.userAgent.match(/MSIE 8.0/);
    console.log(isIE8); // returns true or false
    ```

    If you don't use this expression then it returns the original value.

    ```javascript
    console.log(navigator.userAgent.match(/MSIE 8.0/)); // returns either an Array or null
    ```

    **Note:** The expression !! is not an operator, but it is just twice of ! operator.

    **[⬆ Back to Top](#table-of-contents)**

35. ### What is the purpose of the delete operator

    The delete operator is used to delete the property as well as its value.

    ```javascript
    var user = { firstName: "John", lastName: "Doe", age: 20 };
    delete user.age;

    console.log(user); // {firstName: "John", lastName:"Doe"}
    ```

    **[⬆ Back to Top](#table-of-contents)**

36. ### How do you detect caps lock key turned on or not

    The `mouseEvent getModifierState()` is used to return a boolean value that indicates whether the specified modifier key is activated or not. The modifiers such as CapsLock, ScrollLock and NumLock are activated when they are clicked, and deactivated when they are clicked again.

    Let's take an input element to detect the CapsLock on/off behavior with an example:

    ```html
    <input type="password" onmousedown="enterInput(event)" />

    <p id="feedback"></p>

    <script>
      function enterInput(e) {
        var flag = e.getModifierState("CapsLock");
        if (flag) {
          document.getElementById("feedback").innerHTML = "CapsLock activated";
        } else {
          document.getElementById("feedback").innerHTML =
            "CapsLock not activated";
        }
      }
    </script>
    ```

    **[⬆ Back to Top](#table-of-contents)**

37. ### What is isNaN

    The isNaN() function is used to determine whether a value is an illegal number (Not-a-Number) or not. i.e, This function returns true if the value equates to NaN. Otherwise it returns false.

    ```javascript
    isNaN("Hello"); //true
    isNaN("100"); //false
    ```

    **[⬆ Back to Top](#table-of-contents)**

38. ### What is NaN property

    The NaN property is a global property that represents "Not-a-Number" value. i.e, It indicates that a value is not a legal number. It is very rare to use NaN in a program but it can be used as return value for few cases

    ```javascript
    Math.sqrt(-1);
    parseInt("Hello");
    ```

    **[⬆ Back to Top](#table-of-contents)**

39. ### What is the purpose of isFinite function

    The isFinite() function is used to determine whether a number is a finite, legal number. It returns false if the value is +infinity, -infinity, or NaN (Not-a-Number), otherwise it returns true.

    ```javascript
    isFinite(Infinity); // false
    isFinite(NaN); // false
    isFinite(-Infinity); // false

    isFinite(100); // true
    ```

    **[⬆ Back to Top](#table-of-contents)**

40. ### What are the tools or techniques used for debugging JavaScript code

    You can use below tools or techniques for debugging javascript

    1. Chrome Devtools
    2. debugger statement
    3. Good old console.log statement

    **[⬆ Back to Top](#table-of-contents)**

41. ### What are the pros and cons of promises over callbacks

    Below are the list of pros and cons of promises over callbacks,

    **Pros:**

    1. It avoids callback hell which is unreadable
    2. Easy to write sequential asynchronous code with .then()
    3. Easy to write parallel asynchronous code with Promise.all()
    4. Solves some of the common problems of callbacks(call the callback too late, too early, many times and swallow errors/exceptions)

    **Cons:**

    5. It makes little complex code
    6. You need to load a polyfill if ES6 is not supported

    **[⬆ Back to Top](#table-of-contents)**

42. ### What is the purpose of void 0

    Void(0) is used to prevent the page from refreshing. This will be helpful to eliminate the unwanted side-effect, because it will return the undefined primitive value. It is commonly used for HTML documents that use href="JavaScript:Void(0);" within an `<a>` element. i.e, when you click a link, the browser loads a new page or refreshes the same page. But this behavior will be prevented using this expression.
    For example, the below link notify the message without reloading the page

    ```javascript
    <a href="JavaScript:void(0);" onclick="alert('Well done!')">
      Click Me!
    </a>
    ```

    **[⬆ Back to Top](#table-of-contents)**

43. ### Is JavaScript a compiled or interpreted language

    JavaScript is an interpreted language, not a compiled language. An interpreter in the browser reads over the JavaScript code, interprets each line, and runs it. Nowadays modern browsers use a technology known as Just-In-Time (JIT) compilation, which compiles JavaScript to executable bytecode just as it is about to run.

    **[⬆ Back to Top](#table-of-contents)**

44. ### Is there any relation between Java and JavaScript

      No, they are entirely two different programming languages and have nothing to do with each other. But both of them are Object Oriented Programming languages and like many other languages, they follow similar syntax for basic features(if, else, for, switch, break, continue etc).

      **[⬆ Back to Top](#table-of-contents)**

45. ### Who created javascript

      JavaScript was created by Brendan Eich in 1995 during his time at Netscape Communications. Initially it was developed under the name `Mocha`, but later the language was officially called `LiveScript` when it first shipped in beta releases of Netscape.

      **[⬆ Back to Top](#table-of-contents)**

46. ### What are the steps involved in return false usage

      The return false statement in event handlers performs the below steps,

      1. First it stops the browser's default action or behaviour.
      2. It prevents the event from propagating the DOM
      3. Stops callback execution and returns immediately when called.

      **[⬆ Back to Top](#table-of-contents)**

47. ### What is the use of setTimeout

      The setTimeout() method is used to call a function or evaluate an expression after a specified number of milliseconds. For example, let's log a message after 2 seconds using setTimeout method,

      ```javascript
      setTimeout(function () {
        console.log("Good morning");
      }, 2000);
      ```

      **[⬆ Back to Top](#table-of-contents)**

48. ### What is the use of setInterval

      The setInterval() method is used to call a function or evaluate an expression at specified intervals (in milliseconds). For example, let's log a message after 2 seconds using setInterval method,

      ```javascript
      setInterval(function () {
        console.log("Good morning");
      }, 2000);
      ```

      **[⬆ Back to Top](#table-of-contents)**

49. ### Why is JavaScript treated as Single threaded

      JavaScript is a single-threaded language. Because the language specification does not allow the programmer to write code so that the interpreter can run parts of it in parallel in multiple threads or processes. Whereas languages like java, go, C++ can make multi-threaded and multi-process programs.

      **[⬆ Back to Top](#table-of-contents)**

50. ### What is JSON

      JSON (JavaScript Object Notation) is a lightweight format that is used for data interchanging. It is based on a subset of JavaScript language in the way objects are built in JavaScript.

      **[⬆ Back to Top](#table-of-contents)**

51. ### What are the syntax rules of JSON

      Below are the list of syntax rules of JSON

      1. The data is in name/value pairs
      2. The data is separated by commas
      3. Curly braces hold objects
      4. Square brackets hold arrays

      **[⬆ Back to Top](#table-of-contents)**

52. ### What is the purpose JSON stringify

      When sending data to a web server, the data has to be in a string format. You can achieve this by converting JSON object into a string using stringify() method.

      ```javascript
      var userJSON = { name: "John", age: 31 };
      var userString = JSON.stringify(userJSON);
      console.log(userString); //"{"name":"John","age":31}"
      ```

      **[⬆ Back to Top](#table-of-contents)**

53. ### How do you parse JSON string

      When receiving the data from a web server, the data is always in a string format. But you can convert this string value to a javascript object using parse() method.

      ```javascript
      var userString = '{"name":"John","age":31}';
      var userJSON = JSON.parse(userString);
      console.log(userJSON); // {name: "John", age: 31}
      ```

      **[⬆ Back to Top](#table-of-contents)**

54. ### What is the purpose of clearTimeout method

      The clearTimeout() function is used in javascript to clear the timeout which has been set by setTimeout()function before that. i.e, The return value of setTimeout() function is stored in a variable and it’s passed into the clearTimeout() function to clear the timer.

      For example, the below setTimeout method is used to display the message after 3 seconds. This timeout can be cleared by the clearTimeout() method.

      ```javascript
      <script>
           var msg;
           function greeting() {
              alert('Good morning');
           }
           function start() {
             msg =setTimeout(greeting, 3000);

           }

           function stop() {
               clearTimeout(msg);
           }
      </script>
      ```

      **[⬆ Back to Top](#table-of-contents)**

55. ### What is the purpose of clearInterval method

      The clearInterval() function is used in javascript to clear the interval which has been set by setInterval() function. i.e, The return value returned by setInterval() function is stored in a variable and it’s passed into the clearInterval() function to clear the interval.

      For example, the below setInterval method is used to display the message for every 3 seconds. This interval can be cleared by the clearInterval() method.

      ```javascript
      <script>
           var msg;
           function greeting() {
              alert('Good morning');
           }
           function start() {
             msg = setInterval(greeting, 3000);

           }

           function stop() {
               clearInterval(msg);
           }
      </script>
      ```

      **[⬆ Back to Top](#table-of-contents)**

56. ### How do you check whether a string contains a substring

      There are 3 possible ways to check whether a string contains a substring or not,

      1. **Using includes:** ES6 provided `String.prototype.includes` method to test a string contains a substring

      ```javascript
      var mainString = "hello",
        subString = "hell";
      mainString.includes(subString);
      ```

      2. **Using indexOf:** In an ES5 or older environment, you can use `String.prototype.indexOf` which returns the index of a substring. If the index value is not equal to -1 then it means the substring exists in the main string.

      ```javascript
      var mainString = "hello",
        subString = "hell";
      mainString.indexOf(subString) !== -1;
      ```

      3. **Using RegEx:** The advanced solution is using Regular expression's test method(`RegExp.test`), which allows for testing for against regular expressions

      ```javascript
      var mainString = "hello",
        regex = /hell/;
      regex.test(mainString);
      ```

      **[⬆ Back to Top](#table-of-contents)**

57. ### How do you validate an email in javascript

      You can validate an email in javascript using regular expressions. It is recommended to do validations on the server side instead of the client side. Because the javascript can be disabled on the client side.

      ```javascript
      function validateEmail(email) {
        var re =
          /^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;
        return re.test(String(email).toLowerCase());
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

      The above regular expression accepts unicode characters.

58. ### How do you check if a key exists in an object

      You can check whether a key exists in an object or not using three approaches,

      1. **Using in operator:** You can use the in operator whether a key exists in an object or not

         ```javascript
         "key" in obj;
         ```

         and If you want to check if a key doesn't exist, remember to use parenthesis,

         ```javascript
         !("key" in obj);
         ```

      2. **Using hasOwnProperty method:** You can use `hasOwnProperty` to particularly test for properties of the object instance (and not inherited properties)

         ```javascript
         obj.hasOwnProperty("key"); // true
         ```

      3. **Using undefined comparison:** If you access a non-existing property from an object, the result is undefined. Let’s compare the properties against undefined to determine the existence of the property.

         ```javascript
         const user = {
           name: "John",
         };

         console.log(user.name !== undefined); // true
         console.log(user.nickName !== undefined); // false
         ```

      **[⬆ Back to Top](#table-of-contents)**

59. ### How do you loop through or enumerate javascript object

      You can use the `for-in` loop to loop through javascript object. You can also make sure that the key you get is an actual property of an object, and doesn't come from the prototype using `hasOwnProperty` method.

      ```javascript
      var object = {
        k1: "value1",
        k2: "value2",
        k3: "value3",
      };

      for (var key in object) {
        if (object.hasOwnProperty(key)) {
          console.log(key + " -> " + object[key]); // k1 -> value1 ...
        }
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

60. ### How do you test for an empty object

      There are different solutions based on ECMAScript versions

      1. **Using Object entries(ECMA 7+):** You can use object entries length along with constructor type.

      ```javascript
      Object.entries(obj).length === 0 && obj.constructor === Object; // Since date object length is 0, you need to check constructor check as well
      ```

      2. **Using Object keys(ECMA 5+):** You can use object keys length along with constructor type.

      ```javascript
      Object.keys(obj).length === 0 && obj.constructor === Object; // Since date object length is 0, you need to check constructor check as well
      ```

      3. **Using for-in with hasOwnProperty(Pre-ECMA 5):** You can use a for-in loop along with hasOwnProperty.

      ```javascript
      function isEmpty(obj) {
        for (var prop in obj) {
          if (obj.hasOwnProperty(prop)) {
            return false;
          }
        }

        return JSON.stringify(obj) === JSON.stringify({});
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

61. ### What is an arguments object

      The arguments object is an Array-like object accessible inside functions that contains the values of the arguments passed to that function. For example, let's see how to use arguments object inside sum function,

      ```javascript
      function sum() {
        var total = 0;
        for (var i = 0, len = arguments.length; i < len; ++i) {
          total += arguments[i];
        }
        return total;
      }

      sum(1, 2, 3); // returns 6
      ```

      **Note:** You can't apply array methods on arguments object. But you can convert into a regular array as below.

      ```javascript
      var argsArray = Array.prototype.slice.call(arguments);
      ```

      **[⬆ Back to Top](#table-of-contents)**

62. ### How do you make first letter of the string in an uppercase

      You can create a function which uses a chain of string methods such as charAt, toUpperCase and slice methods to generate a string with the first letter in uppercase.

      ```javascript
      function capitalizeFirstLetter(string) {
        return string.charAt(0).toUpperCase() + string.slice(1);
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

63. ### What are the pros and cons of for loops

      The for-loop is a commonly used iteration syntax in javascript. It has both pros and cons

      #### Pros

      1. Works on every environment
      2. You can use break and continue flow control statements

      #### Cons

      3. Too verbose
      4. Imperative
      5. You might face off-by-one errors.

      **[⬆ Back to Top](#table-of-contents)**

64. ### How do you compare two date objects

      You need to use date.getTime() method in order to compare unix timestamp values

      ```javascript
      var d1 = new Date();
      var d2 = new Date(d1);
      console.log(d1.getTime() === d2.getTime()); //True
      console.log(d1 === d2); // False
      ```

      **[⬆ Back to Top](#table-of-contents)**

65. ### How do you trim a string in javascript

      JavaScript provided a trim method on string types to trim any whitespaces present at the beginning or ending of the string.

      ```javascript
      "  Hello World   ".trim(); //Hello World
      ```

      If your browser(<IE9) doesn't support this method then you can use below polyfill.

      ```javascript
      if (!String.prototype.trim) {
        (function () {
          // Make sure we trim BOM and NBSP
          var rtrim = /^[\s\uFEFF\xA0]+|[\s\uFEFF\xA0]+$/g;
          String.prototype.trim = function () {
            return this.replace(rtrim, "");
          };
        })();
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

66. ### How do you add a key value pair in javascript

      There are two possible solutions to add new properties to an object.

      Let's take a simple object to explain these solutions.

      ```javascript
      var object = {
        key1: value1,
        key2: value2,
      };
      ```

      1. **Using dot notation:** This solution is useful when you know the name of the property

      ```javascript
      object.key3 = "value3";
      ```

      2. **Using square bracket notation:** This solution is useful when the name of the property is dynamically determined or the key's name is non-JS like "user-name"

      ```javascript
      obj["key3"] = "value3";
      ```

      **[⬆ Back to Top](#table-of-contents)**

67. ### Is the !-- notation represents a special operator

      No,that's not a special operator. But it is a combination of 2 standard operators one after the other,

      1. A logical not (!)
      2. A prefix decrement (--)

      At first, the value decremented by one and then tested to see if it is equal to zero or not for determining the truthy/falsy value.

      **[⬆ Back to Top](#table-of-contents)**

68. ### How do you define multiline strings

      You can define multiline string literals using the '\n' character followed by line terminator('\').

      ```javascript
      var str = "This is a \n very lengthy \n sentence!";
      console.log(str);
      ```

      But if you have a space after the '\n' character, there will be indentation inconsistencies.

      **[⬆ Back to Top](#table-of-contents)**

69. ### Can we define properties for functions

      Yes, we can define properties for functions because functions are also objects.

      ```javascript
      fn = function (x) {
        //Function code goes here
      };

      fn.name = "John";

      fn.profile = function (y) {
        //Profile code goes here
      };
      ```

      **[⬆ Back to Top](#table-of-contents)**

70. ### What is the way to find the number of parameters expected by a function

      You can use `function.length` syntax to find the number of parameters expected by a function. Let's take an example of `sum` function to calculate the sum of numbers,

      ```javascript
      function sum(num1, num2, num3, num4) {
        return num1 + num2 + num3 + num4;
      }
      sum.length; // 4 is the number of parameters expected.
      ```

      **[⬆ Back to Top](#table-of-contents)**

71. ### What is a polyfill

      A polyfill is a piece of JS code used to provide modern functionality on older browsers that do not natively support it. For example, Silverlight plugin polyfill can be used to mimic the functionality of an HTML Canvas element on Microsoft Internet Explorer 7.

      There are two main polyfill libraries available,

      1. **Core.js**: It is a modular javascript library used for cutting-edge ECMAScript features.
      2. **Polyfill.io:** It provides polyfills that are required for browser needs.

      **[⬆ Back to Top](#table-of-contents)**

72. ### What are break and continue statements

      The break statement is used to "jump out" of a loop. i.e, It breaks the loop and continues executing the code after the loop.

      ```javascript
      for (i = 0; i < 10; i++) {
        if (i === 5) {
          break;
        }
        text += "Number: " + i + "<br>";
      }
      ```

      The continue statement is used to "jump over" one iteration in the loop. i.e, It breaks one iteration (in the loop), if a specified condition occurs, and continues with the next iteration in the loop.

      ```javascript
      for (i = 0; i < 10; i++) {
        if (i === 5) {
          continue;
        }
        text += "Number: " + i + "<br>";
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

73. ### What are js labels

      The label statement allows us to name loops and blocks in JavaScript. We can then use these labels to refer back to the code later. For example, the below code with labels avoids printing the numbers when they are same,

      ```javascript
      var i, j;

      loop1: for (i = 0; i < 3; i++) {
        loop2: for (j = 0; j < 3; j++) {
          if (i === j) {
            continue loop1;
          }
          console.log("i = " + i + ", j = " + j);
        }
      }

      // Output is:
      //   "i = 1, j = 0"
      //   "i = 2, j = 0"
      //   "i = 2, j = 1"
      ```

      **[⬆ Back to Top](#table-of-contents)**

74. ### What are the recommendations to create new object

      It is recommended to avoid creating new objects using `new Object()`. Instead you can initialize values based on it's type to create the objects.

      1. Assign {} instead of new Object()
      2. Assign "" instead of new String()
      3. Assign 0 instead of new Number()
      4. Assign false instead of new Boolean()
      5. Assign [] instead of new Array()
      6. Assign /()/ instead of new RegExp()
      7. Assign function (){} instead of new Function()

      You can define them as an example,

      ```javascript
      var v1 = {};
      var v2 = "";
      var v3 = 0;
      var v4 = false;
      var v5 = [];
      var v6 = /()/;
      var v7 = function () {};
      ```

      **[⬆ Back to Top](#table-of-contents)**

75. ### How do you define JSON arrays

      JSON arrays are written inside square brackets and arrays contain javascript objects. For example, the JSON array of users would be as below,

      ```javascript
      "users":[
        {"firstName":"John", "lastName":"Abrahm"},
        {"firstName":"Anna", "lastName":"Smith"},
        {"firstName":"Shane", "lastName":"Warn"}
      ]
      ```

      **[⬆ Back to Top](#table-of-contents)**

76. ### How do you generate random integers

      You can use `Math.random()` with `Math.floor()` to return random integers. For example, if you want generate random integers between 1 to 10, the multiplication factor should be 10,

      ```javascript
      Math.floor(Math.random() * 10) + 1; // returns a random integer from 1 to 10
      Math.floor(Math.random() * 100) + 1; // returns a random integer from 1 to 100
      ```

      **Note:** `Math.random()` returns a random number between 0 (inclusive), and 1 (exclusive)

      **[⬆ Back to Top](#table-of-contents)**

77. ### Can you write a random integers function to print integers within a range

      Yes, you can create a proper random function to return a random number between min and max (both included)

      ```javascript
      function randomInteger(min, max) {
        return Math.floor(Math.random() * (max - min + 1)) + min;
      }
      randomInteger(1, 100); // returns a random integer from 1 to 100
      randomInteger(1, 1000); // returns a random integer from 1 to 1000
      ```

      **[⬆ Back to Top](#table-of-contents)**

78. ### What is tree shaking

      Tree shaking is a form of dead code elimination. It means that unused modules will not be included in the bundle during the build process and for that it relies on the static structure of ES2015 module syntax,( i.e. import and export). Initially this has been popularized by the ES2015 module bundler `rollup`, these days practically all bundlers use this technique.

      **[⬆ Back to Top](#table-of-contents)**

79. ### Is it recommended to use eval

      No, it allows arbitrary code to be run which causes a security problem. As we know that the eval() function is used to run text as code. In most of the cases, it should not be necessary to use it.

      **[⬆ Back to Top](#table-of-contents)**

80. ### What is a Regular Expression

      A regular expression is a sequence of characters that forms a search pattern. You can use this search pattern for searching data in a text. These can be used to perform all types of text search and text replace operations. Let's see the syntax format now,

      ```javascript
      /pattern/modifiers;
      ```

      For example, the regular expression or search pattern with case-insensitive username would be,

      ```javascript
      /John/i;
      ```

      **[⬆ Back to Top](#table-of-contents)**

81. ### What are the string methods that accept Regular expression

      There are six string methods: `search()`, `replace()`, `replaceAll()`, `match()`, `matchAll()`, and `split()`.

      The `search()` method uses an expression to search for a match, and returns the position of the match.

      ```javascript
      var msg = "Hello John";
      var n = msg.search(/John/i); // 6
      ```

      The `replace()` and `replaceAll()` methods are used to return a modified string where the pattern is replaced.

      ```javascript
      var msg = "ball bat";
      var n1 = msg.replace(/b/i, "c"); // call bat
      var n2 = msg.replaceAll(/b/i, "c"); // call cat
      ```

      The `match()` and `matchAll()` methods are used to return the matches when matching a string against a regular expression.

      ```javascript
      var msg = "Hello John";
      var n1 = msg.match(/[A-Z]/g); // ["H", "J"]
      var n2 = msg.matchAll(/[A-Z]/g); // this returns an iterator
      ```

      The `split()` method is used to split a string into an array of substrings, and returns the new array.

      ```javascript
      var msg = "Hello John";
      var n = msg.split(/\s/); // ["Hello", "John"]
      ```

      **[⬆ Back to Top](#table-of-contents)**

82. ### What are modifiers in regular expression

      Modifiers can be used to perform case-insensitive and global searches. Let's list some of the modifiers,

      | Modifier | Description                                             |
      | -------- | ------------------------------------------------------- |
      | i        | Perform case-insensitive matching                       |
      | g        | Perform a global match rather than stops at first match |
      | m        | Perform multiline matching                              |

      Let's take an example of global modifier,

      ```javascript
      var text = "Learn JS one by one";
      var pattern = /one/g;
      var result = text.match(pattern); // one,one
      ```

      **[⬆ Back to Top](#table-of-contents)**

83. ### What are regular expression patterns

      Regular Expressions provide a group of patterns in order to match characters. Basically they are categorized into 3 types,

      1. **Brackets:** These are used to find a range of characters.
         For example, below are some use cases,
         1. [abc]: Used to find any of the characters between the brackets(a,b,c)
         2. [0-9]: Used to find any of the digits between the brackets
         3. (a|b): Used to find any of the alternatives separated with |
      2. **Metacharacters:** These are characters with a special meaning.
         For example, below are some use cases,
         1. \\d: Used to find a digit
         2. \\s: Used to find a whitespace character
         3. \\b: Used to find a match at the beginning or ending of a word
      3. **Quantifiers:** These are useful to define quantities.
         For example, below are some use cases,
         1. n+: Used to find matches for any string that contains at least one n
         2. n\*: Used to find matches for any string that contains zero or more occurrences of n
         3. n?: Used to find matches for any string that contains zero or one occurrences of n

      **[⬆ Back to Top](#table-of-contents)**

84. ### What is a RegExp object

      RegExp object is a regular expression object with predefined properties and methods. Let's see the simple usage of RegExp object,

      ```javascript
      var regexp = new RegExp("\\w+");
      console.log(regexp);
      // expected output: /\w+/
      ```

      **[⬆ Back to Top](#table-of-contents)**

85. ### How do you search a string for a pattern

      You can use the `test()` method of regular expression in order to search a string for a pattern, and return true or false depending on the result.

      ```javascript
      var pattern = /you/;
      console.log(pattern.test("How are you?")); //true
      ```

      **[⬆ Back to Top](#table-of-contents)**

86. ### What is the purpose of exec method

      The purpose of exec method is similar to test method but it executes a search for a match in a specified string and returns a result array, or null instead of returning true/false.

      ```javascript
      var pattern = /you/;
      console.log(pattern.exec("How are you?")); //["you", index: 8, input: "How are you?", groups: undefined]
      ```

      **[⬆ Back to Top](#table-of-contents)**

87. ### What would be the result of 1+2+'3'

      The output is going to be `33`. Since `1` and `2` are numeric values, the result of the first two digits is going to be a numeric value `3`. The next digit is a string type value because of that the addition of numeric value `3` and string type value `3` is just going to be a concatenation value `33`. Other operationrs like `3 * '3'` do yield correct results because the string is coerced into a number.

      **[⬆ Back to Top](#table-of-contents)**

88. ### What is a debugger statement

      The debugger statement invokes any available debugging functionality, such as setting a breakpoint. If no debugging functionality is available, this statement has no effect.
      For example, in the below function a debugger statement has been inserted. So
      execution is paused at the debugger statement just like a breakpoint in the script source.

      ```javascript
      function getProfile() {
        // code goes here
        debugger;
        // code goes here
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

89. ### How do you detect a mobile browser

      You can use regex which returns a true or false value depending on whether or not the user is browsing with a mobile.

      ```javascript
      window.mobilecheck = function () {
        var mobileCheck = false;
        (function (a) {
          if (
            /(android|bb\d+|meego).+mobile|avantgo|bada\/|blackberry|blazer|compal|elaine|fennec|hiptop|iemobile|ip(hone|od)|iris|kindle|lge |maemo|midp|mmp|mobile.+firefox|netfront|opera m(ob|in)i|palm( os)?|phone|p(ixi|re)\/|plucker|pocket|psp|series(4|6)0|symbian|treo|up\.(browser|link)|vodafone|wap|windows ce|xda|xiino/i.test(
              a
            ) ||
            /1207|6310|6590|3gso|4thp|50[1-6]i|770s|802s|a wa|abac|ac(er|oo|s\-)|ai(ko|rn)|al(av|ca|co)|amoi|an(ex|ny|yw)|aptu|ar(ch|go)|as(te|us)|attw|au(di|\-m|r |s )|avan|be(ck|ll|nq)|bi(lb|rd)|bl(ac|az)|br(e|v)w|bumb|bw\-(n|u)|c55\/|capi|ccwa|cdm\-|cell|chtm|cldc|cmd\-|co(mp|nd)|craw|da(it|ll|ng)|dbte|dc\-s|devi|dica|dmob|do(c|p)o|ds(12|\-d)|el(49|ai)|em(l2|ul)|er(ic|k0)|esl8|ez([4-7]0|os|wa|ze)|fetc|fly(\-|_)|g1 u|g560|gene|gf\-5|g\-mo|go(\.w|od)|gr(ad|un)|haie|hcit|hd\-(m|p|t)|hei\-|hi(pt|ta)|hp( i|ip)|hs\-c|ht(c(\-| |_|a|g|p|s|t)|tp)|hu(aw|tc)|i\-(20|go|ma)|i230|iac( |\-|\/)|ibro|idea|ig01|ikom|im1k|inno|ipaq|iris|ja(t|v)a|jbro|jemu|jigs|kddi|keji|kgt( |\/)|klon|kpt |kwc\-|kyo(c|k)|le(no|xi)|lg( g|\/(k|l|u)|50|54|\-[a-w])|libw|lynx|m1\-w|m3ga|m50\/|ma(te|ui|xo)|mc(01|21|ca)|m\-cr|me(rc|ri)|mi(o8|oa|ts)|mmef|mo(01|02|bi|de|do|t(\-| |o|v)|zz)|mt(50|p1|v )|mwbp|mywa|n10[0-2]|n20[2-3]|n30(0|2)|n50(0|2|5)|n7(0(0|1)|10)|ne((c|m)\-|on|tf|wf|wg|wt)|nok(6|i)|nzph|o2im|op(ti|wv)|oran|owg1|p800|pan(a|d|t)|pdxg|pg(13|\-([1-8]|c))|phil|pire|pl(ay|uc)|pn\-2|po(ck|rt|se)|prox|psio|pt\-g|qa\-a|qc(07|12|21|32|60|\-[2-7]|i\-)|qtek|r380|r600|raks|rim9|ro(ve|zo)|s55\/|sa(ge|ma|mm|ms|ny|va)|sc(01|h\-|oo|p\-)|sdk\/|se(c(\-|0|1)|47|mc|nd|ri)|sgh\-|shar|sie(\-|m)|sk\-0|sl(45|id)|sm(al|ar|b3|it|t5)|so(ft|ny)|sp(01|h\-|v\-|v )|sy(01|mb)|t2(18|50)|t6(00|10|18)|ta(gt|lk)|tcl\-|tdg\-|tel(i|m)|tim\-|t\-mo|to(pl|sh)|ts(70|m\-|m3|m5)|tx\-9|up(\.b|g1|si)|utst|v400|v750|veri|vi(rg|te)|vk(40|5[0-3]|\-v)|vm40|voda|vulc|vx(52|53|60|61|70|80|81|83|85|98)|w3c(\-| )|webc|whit|wi(g |nc|nw)|wmlb|wonu|x700|yas\-|your|zeto|zte\-/i.test(
              a.substr(0, 4)
            )
          )
            mobileCheck = true;
        })(navigator.userAgent || navigator.vendor || window.opera);
        return mobileCheck;
      };
      ```

      **[⬆ Back to Top](#table-of-contents)**

90. ### How do you detect a mobile browser without regexp

      You can detect mobile browsers by simply running through a list of devices and checking if the useragent matches anything. This is an alternative solution for RegExp usage,

      ```javascript
      function detectmob() {
        if (
          navigator.userAgent.match(/Android/i) ||
          navigator.userAgent.match(/webOS/i) ||
          navigator.userAgent.match(/iPhone/i) ||
          navigator.userAgent.match(/iPad/i) ||
          navigator.userAgent.match(/iPod/i) ||
          navigator.userAgent.match(/BlackBerry/i) ||
          navigator.userAgent.match(/Windows Phone/i)
        ) {
          return true;
        } else {
          return false;
        }
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

91. ### How do you get the image width and height using JS

      You can programmatically get the image and check the dimensions(width and height) using Javascript.

      ```javascript
      var img = new Image();
      img.onload = function () {
        console.log(this.width + "x" + this.height);
      };
      img.src = "http://www.google.com/intl/en_ALL/images/logo.gif";
      ```

      **[⬆ Back to Top](#table-of-contents)**

92. ### How do you make synchronous HTTP request

      Browsers provide an XMLHttpRequest object which can be used to make synchronous HTTP requests from JavaScript.

      ```javascript
      function httpGet(theUrl) {
        var xmlHttpReq = new XMLHttpRequest();
        xmlHttpReq.open("GET", theUrl, false); // false for synchronous request
        xmlHttpReq.send(null);
        return xmlHttpReq.responseText;
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

93. ### How do you convert date to another timezone in javascript

      You can use the toLocaleString() method to convert dates in one timezone to another. For example, let's convert current date to British English timezone as below,

      ```javascript
      console.log(new Date().toLocaleString("en-GB", { timeZone: "UTC" })); //29/06/2019, 09:56:00
      ```

      **[⬆ Back to Top](#table-of-contents)**

94. ### What is a conditional operator in javascript

      The conditional (ternary) operator is the only JavaScript operator that takes three operands which acts as a shortcut for `if` statements.

      ```javascript
      var isAuthenticated = false;
      console.log(
        isAuthenticated ? "Hello, welcome" : "Sorry, you are not authenticated"
      ); // Sorry, you are not authenticated
      ```

      **[⬆ Back to Top](#table-of-contents)**

95. ### Can you apply chaining on conditional operator

      Yes, you can apply chaining on conditional operators similar to **`if … else if … else if … else`** chain. The syntax is going to be as below,

      ```javascript
      function traceValue(someParam) {
        return condition1
          ? value1
          : condition2
          ? value2
          : condition3
          ? value3
          : value4;
      }

      // The above conditional operator is equivalent to:

      function traceValue(someParam) {
        if (condition1) {
          return value1;
        } else if (condition2) {
          return value2;
        } else if (condition3) {
          return value3;
        } else {
          return value4;
        }
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

96. ### Can you give an example of when you really need a semicolon

      It is recommended to use semicolons after every statement in JavaScript. For example, in the below case (that is an IIFE = Immediately Invoked Function Expression) it throws an error ".. is not a function" at runtime due to missing semicolon.

      ```javascript
      // define a function
      var fn = (function () {
        //...
      })(
        // semicolon missing at this line

        // then execute some code inside a closure
        function () {
          //...
        }
      )();
      ```

      and it will be interpreted as

      ```javascript
      var fn = (function () {
        //...
      })(function () {
        //...
      })();
      ```

      In this case, we are passing the second function as an argument to the first function and then trying to call the result of the first function call as a function. Hence, the second function will fail with a "... is not a function" error at runtime.

      **[⬆ Back to Top](#table-of-contents)**

97. ### What is the freeze method

      The **`freeze()`** method is used to freeze an object. Freezing an object does not allow adding new properties to an object, prevents removing, and prevents changing the enumerability, configurability, or writability of existing properties. i.e. It returns the passed object and does not create a frozen copy.

      ```javascript
      const obj = {
        prop: 100,
      };

      Object.freeze(obj);
      obj.prop = 200; // Throws an error in strict mode

      console.log(obj.prop); //100
      ```

      Remember freezing is only applied to the top-level properties in objects but not for nested objects.
      For example, let's try to freeze user object which has employment details as nested object and observe that details have been changed.

      ```javascript
      const user = {
        name: "John",
        employment: {
          department: "IT",
        },
      };

      Object.freeze(user);
      user.employment.department = "HR";
      ```

      **Note:** It causes a TypeError if the argument passed is not an object.

      **[⬆ Back to Top](#table-of-contents)**

98. ### What is the purpose of the freeze method

      Below are the main benefits of using freeze method,

      1. It is used for freezing objects and arrays.
      2. It is used to make an object immutable.

      **[⬆ Back to Top](#table-of-contents)**

99. ### Why do I need to use the freeze method

      In the Object-oriented paradigm, an existing API contains certain elements that are not intended to be extended, modified, or re-used outside of their current context. Hence it works as the `final` keyword which is used in various languages.

      **[⬆ Back to Top](#table-of-contents)**

100. ### How to convert a string to title case with javascript

      Title case means that the first letter of each word is capitalized. You can convert a string to title case using the below function,

      ```javascript
      function toTitleCase(str) {
        return str.replace(/\w\S*/g, function (txt) {
          return txt.charAt(0).toUpperCase() + txt.substring(1).toLowerCase();
        });
      }
      toTitleCase("good morning john"); // Good Morning John
      ```

      **[⬆ Back to Top](#table-of-contents)**

101. ### What is a rest parameter

      Rest parameter is an improved way to handle function parameters which allows us to represent an indefinite number of arguments as an array. The syntax would be as below,

      ```javascript
      function f(a, b, ...theArgs) {
        // ...
      }
      ```

      For example, let's take a sum example to calculate on dynamic number of parameters,

      ```javascript
      function sum(...args) {
        let total = 0;
        for (const i of args) {
          total += i;
        }
        return total;
      }

      console.log(sum(1, 2)); //3
      console.log(sum(1, 2, 3)); //6
      console.log(sum(1, 2, 3, 4)); //10
      console.log(sum(1, 2, 3, 4, 5)); //15
      ```

      **Note:** Rest parameter is added in ES2015 or ES6

      **[⬆ Back to Top](#table-of-contents)**

102. ### What happens if you do not use rest parameter as a last argument

      The rest parameter should be the last argument, as its job is to collect all the remaining arguments into an array. For example, if you define a function like below it doesn’t make any sense and will throw an error.

      ```javascript
      function someFunc(a,…b,c){
      //You code goes here
      return;
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

103. ### What are the bitwise operators available in javascript

      Below are the list of bitwise logical operators used in JavaScript

      1. Bitwise AND ( & )
      2. Bitwise OR ( | )
      3. Bitwise XOR ( ^ )
      4. Bitwise NOT ( ~ )
      5. Left Shift ( << )
      6. Sign Propagating Right Shift ( >> )
      7. Zero fill Right Shift ( >>> )

      **[⬆ Back to Top](#table-of-contents)**

104. ### What is a spread operator

      Spread operator allows iterables( arrays / objects / strings ) to be expanded into single arguments/elements. Let's take an example to see this behavior,

      ```javascript
      function calculateSum(x, y, z) {
        return x + y + z;
      }

      const numbers = [1, 2, 3];

      console.log(calculateSum(...numbers)); // 6
      ```

      **[⬆ Back to Top](#table-of-contents)**

105. ### How do you determine whether object is frozen or not

      `Object.isFrozen()` method is used to determine if an object is frozen or not.An object is frozen if all of the below conditions hold true,

      1. If it is not extensible.
      2. If all of its properties are non-configurable.
      3. If all its data properties are non-writable.
         The usage is going to be as follows,

      ```javascript
      const object = {
        property: "Welcome JS world",
      };
      Object.freeze(object);
      console.log(Object.isFrozen(object));
      ```

      **[⬆ Back to Top](#table-of-contents)**

106. ### What is the purpose of using object is method

      Some of the applications of Object's `is` method are follows,

      1. It is used for comparison of two strings.
      2. It is used for comparison of two numbers.
      3. It is used for comparing the polarity of two numbers.
      4. It is used for comparison of two objects.

      **[⬆ Back to Top](#table-of-contents)**

107. ### How do you copy properties from one object to other

      You can use the `Object.assign()` method which is used to copy the values and properties from one or more source objects to a target object. It returns the target object which has properties and values copied from the source objects. The syntax would be as below,

      ```javascript
      Object.assign(target, ...sources);
      ```

      Let's take example with one source and one target object,

      ```javascript
      const target = { a: 1, b: 2 };
      const source = { b: 3, c: 4 };

      const returnedTarget = Object.assign(target, source);

      console.log(target); // { a: 1, b: 3, c: 4 }

      console.log(returnedTarget); // { a: 1, b: 3, c: 4 }
      ```

      As observed in the above code, there is a common property(`b`) from source to target so it's value has been overwritten.

      **[⬆ Back to Top](#table-of-contents)**

108. ### What are the applications of the assign method

      Below are the some of main applications of `Object.assign()` method,

      1. It is used for cloning an object.
      2. It is used to merge objects with the same properties.

      **[⬆ Back to Top](#table-of-contents)**

109. ### What is a proxy object

      The Proxy object is used to define custom behavior for fundamental operations such as property lookup, assignment, enumeration, function invocation, etc.

      A proxy is created with two parameters: a target object which you want to proxy and a handler object which contains methods to intercept fundamental operations. The syntax would be as follows,

      ```javascript
      var p = new Proxy(target, handler);
      ```

      Let's take a look at below examples of proxy object and how the get method which customize the lookup behavior,

      ```javascript
      //Example1:

      const person = {
        name: "Sudheer Jonna",
        age: 35,
      };

      const handler = {
        get(target, prop) {
          if (prop === "name") {
            return "Mr. " + target[prop];
          }
          return target[prop];
        },
      };

      const proxy = new Proxy(person, handler);

      //Example2:

      var handler1 = {
        get: function (obj, prop) {
          return prop in obj ? obj[prop] : 100;
        },
      };

      var p = new Proxy({}, handler1);
      p.a = 10;
      p.b = null;

      console.log(p.a, p.b); // 10, null
      console.log("c" in p, p.c); // false, 100
      ```

      In the above code, it uses `get` handler which define the behavior of the proxy when an operation is performed on it. These proxies are mainly used for some of the below cross-cutting concerns.

      1. Logging
      2. Authentication or Authorization
      3. Data binding and observables
      4. Function parameter validation

      **Note:** This feature was introduced with ES6.

      **[⬆ Back to Top](#table-of-contents)**

110. ### What is the purpose of the seal method

      The `Object.seal()` method is used to seal an object, by preventing new properties from being added to it and marking all existing properties as non-configurable. But **values of present properties can still be changed as long as they are writable**. The next level of immutability would be the [`Object.freeze()`](#what-is-a-freeze-method) method. Let's see the below example to understand more about `seal()` method

      ```javascript
      const object = {
        property: "Welcome JS world",
      };
      Object.seal(object);
      object.property = "Welcome to object world";
      console.log(Object.isSealed(object)); // true
      delete object.property; // You cannot delete when sealed
      console.log(object.property); //Welcome to object world
      ```

      **[⬆ Back to Top](#table-of-contents)**

111. ### What are the applications of the seal method

      Below are the main applications of `Object.seal()` method,

      1. It is used for sealing objects and arrays.
      2. It is used to make properties of an object non-configurable.

      **[⬆ Back to Top](#table-of-contents)**

112. ### What are the differences between the freeze and seal methods

      If an object is frozen using the `Object.freeze()` method then its properties become immutable and no changes can be made in them whereas if an object is sealed using the `Object.seal()` method then the changes can be made in the existing properties of the object.

      **[⬆ Back to Top](#table-of-contents)**

113. ### How do you determine if an object is sealed or not

      The `Object.isSealed()` method is used to determine if an object is sealed or not. An object is sealed if all of the below conditions hold true

      1. If it is not extensible.
      2. If all of its properties are non-configurable.
      3. If it is not removable (but not necessarily non-writable).
         Let's see it in the action

      ```javascript
      const object = {
        property: "Hello, Good morning",
      };

      Object.seal(object); // Using seal() method to seal the object

      console.log(Object.isSealed(object)); // checking whether the object is sealed or not
      ```

      **[⬆ Back to Top](#table-of-contents)**

114. ### How do you get enumerable key and value pairs

      The `Object.entries()` method is used to return an array of a given object's own enumerable string-keyed property [key, value] pairs, in the same order as that provided by a `for...in` loop. Let's see the functionality of `object.entries()` method in an example,

      ```javascript
      const object = {
        a: "Good morning",
        b: 100,
      };

      for (let [key, value] of Object.entries(object)) {
        console.log(`${key}: ${value}`); // a: 'Good morning'
        // b: 100
      }
      ```

      **Note:** The order is not guaranteed as object defined.

      **[⬆ Back to Top](#table-of-contents)**

115. ### What is the main difference between Object.values and Object.entries method

      The `Object.values()` method's behavior is similar to `Object.entries()` method but it returns an array of values instead [key,value] pairs.

      ```javascript
      const object = {
        a: "Good morning",
        b: 100,
      };

      for (let value of Object.values(object)) {
        console.log(`${value}`); // 'Good morning \n100'
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

116. ### How can you get the list of keys of any object

      You can use the `Object.keys()` method which is used to return an array of a given object's own property names, in the same order as we get with a normal loop. For example, you can get the keys of a user object,

      ```javascript
      const user = {
        name: "John",
        gender: "male",
        age: 40,
      };

      console.log(Object.keys(user)); //['name', 'gender', 'age']
      ```

      **[⬆ Back to Top](#table-of-contents)**

117. ### How do you create an object with a prototype

      The `Object.create()` method is used to create a new object with the specified prototype object and properties. i.e, It uses an existing object as the prototype of the newly created object. It returns a new object with the specified prototype object and properties.

      ```javascript
      const user = {
        name: "John",
        printInfo: function () {
          console.log(`My name is ${this.name}.`);
        },
      };

      const admin = Object.create(user);

      admin.name = "Nick"; // Remember that "name" is a property set on "admin" but not on "user" object

      admin.printInfo(); // My name is Nick
      ```

      **[⬆ Back to Top](#table-of-contents)**

118. ### What is a WeakSet

      A `WeakSet` is used to store a collection of weakly(weak references) held objects. The syntax would be as follows,

      ```javascript
      new WeakSet([iterable]);
      ```

      Let's see the below example to explain it's behavior,

      ```javascript
      var ws = new WeakSet();
      var user = {};
      ws.add(user);
      ws.has(user); // true
      ws.delete(user); // removes user from the set
      ws.has(user); // false, user has been removed
      ```

      **[⬆ Back to Top](#table-of-contents)**

119. ### What are the differences between WeakSet and Set

      The main difference is that references to objects in `Set` are strong while references to objects in `WeakSet` are weak. i.e, An object in `WeakSet` can be garbage collected if there is no other reference to it.
      Other differences are:

      1. `Set` can store any value whereas `WeakSet` can store only collections of objects
      2. `WeakSet` does not have size property unlike `Set`
      3. `WeakSet` does not have methods such as clear, keys, values, entries, forEach.
      4. `WeakSet` is not iterable.

      **[⬆ Back to Top](#table-of-contents)**

120. ### List down the collection of methods available on WeakSet

      Below are the list of methods available on `WeakSet`,

      1. `add(value)`: A new object is appended with the given value
      2. `delete(value)`: Deletes the value from the collection.
      3. `has(value)`: It returns true if the value is present in the collection, otherwise it returns false.

      Let's see the functionality of all the above methods in an example,

      ```javascript
      var weakSetObject = new WeakSet();
      var firstObject = {};
      var secondObject = {};
      // add(value)
      weakSetObject.add(firstObject);
      weakSetObject.add(secondObject);
      console.log(weakSetObject.has(firstObject)); //true
      weakSetObject.delete(secondObject);
      ```

      **[⬆ Back to Top](#table-of-contents)**

121. ### What is a WeakMap

      A `WeakMap` object is a collection of key/value pairs in which the keys are weakly referenced. In this case, keys must be objects and the values can be arbitrary values. The syntax looks like the following:

      ```javascript
      new WeakMap([iterable]);
      ```

      Let's see the below example to explain it's behavior,

      ```javascript
      var ws = new WeakMap();
      var user = {};
      ws.set(user);
      ws.has(user); // true
      ws.delete(user); // removes user from the map
      ws.has(user); // false, user has been removed
      ```

      **[⬆ Back to Top](#table-of-contents)**

122. ### What are the differences between WeakMap and Map

      The main difference is that references to key objects in `Map` are strong while references to key objects in `WeakMap` are weak. i.e, A key object in `WeakMap` can be garbage collected if there is no other reference to it.
      Other differences are,

      1. `Map` can store any key type whereas `WeakMap` can store only collections of key objects
      2. `WeakMap` does not have size property unlike `Map`
      3. `WeakMap` does not have methods such as clear, keys, values, entries, forEach.
      4. `WeakMap` is not iterable.

      **[⬆ Back to Top](#table-of-contents)**

123. ### List down the collection of methods available on WeakMap

      Below are the list of methods available on `WeakMap`,

      1. `set(key, value)`: Sets the value for the key in the `WeakMap` object. Returns the `WeakMap` object.
      2. `delete(key)`: Removes any value associated to the key.
      3. `has(key)`: Returns a Boolean asserting whether a value has been associated to the key in the `WeakMap` object or not.
      4. `get(key)`: Returns the value associated to the key, or undefined if there is none.
         Let's see the functionality of all the above methods in an example,

      ```javascript
      var weakMapObject = new WeakMap();
      var firstObject = {};
      var secondObject = {};
      // set(key, value)
      weakMapObject.set(firstObject, "John");
      weakMapObject.set(secondObject, 100);
      console.log(weakMapObject.has(firstObject)); //true
      console.log(weakMapObject.get(firstObject)); // John
      weakMapObject.delete(secondObject);
      ```

      **[⬆ Back to Top](#table-of-contents)**

124. ### What is the purpose of uneval

      The `uneval()` is an builtin function which is used to create a string representation of the source code of an Object. It is a top-level function and is not associated with any object. Let's see the below example to know more about it's functionality,

      ```javascript
      var a = 1;
      uneval(a); // returns a String containing 1
      uneval(function user() {}); // returns "(function user(){})"
      ```

      The `uneval()` function has been deprecated. It is recommended to use `toString()` for functions and `JSON.stringify()` for other cases.

      ```javascript
      function user() {}
      console.log(user.toString()); // returns "(function user(){})"
      ```

      **[⬆ Back to Top](#table-of-contents)**

125. ### How do you encode an URL

      The `encodeURI()` function is used to encode complete URI which has special characters except (, / ? : @ & = + $ #) characters.

      ```javascript
      var uri = "https://mozilla.org/?x=шеллы";
      var encoded = encodeURI(uri);
      console.log(encoded); // https://mozilla.org/?x=%D1%88%D0%B5%D0%BB%D0%BB%D1%8B
      ```

      **[⬆ Back to Top](#table-of-contents)**

126. ### How do you decode an URL

      The `decodeURI()` function is used to decode a Uniform Resource Identifier (URI) previously created by `encodeURI()`.

      ```javascript
      var uri = "https://mozilla.org/?x=шеллы";
      var encoded = encodeURI(uri);
      console.log(encoded); // https://mozilla.org/?x=%D1%88%D0%B5%D0%BB%D0%BB%D1%8B
      try {
        console.log(decodeURI(encoded)); // "https://mozilla.org/?x=шеллы"
      } catch (e) {
        // catches a malformed URI
        console.error(e);
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

127. ### What is the difference between uneval and eval

      The `uneval` function returns the source of a given object; whereas the `eval` function does the opposite, by evaluating that source code in a different memory area. Let's see an example to clarify the difference,

      ```javascript
      var msg = uneval(function greeting() {
        return "Hello, Good morning";
      });
      var greeting = eval(msg);
      greeting(); // returns "Hello, Good morning"
      ```

      **[⬆ Back to Top](#table-of-contents)**

128. ### What is an anonymous function

      An anonymous function is a function without a name! Anonymous functions are commonly assigned to a variable name or used as a callback function. The syntax would be as below,

      ```javascript
      function (optionalParameters) {
        //do something
      }

      const myFunction = function(){ //Anonymous function assigned to a variable
        //do something
      };

      [1, 2, 3].map(function(element){ //Anonymous function used as a callback function
        //do something
      });
      ```

      Let's see the above anonymous function in an example,

      ```javascript
      var x = function (a, b) {
        return a * b;
      };
      var z = x(5, 10);
      console.log(z); // 50
      ```

      **[⬆ Back to Top](#table-of-contents)**

129. ### What are javascript accessors

      ECMAScript 5 introduced javascript object accessors or computed properties through getters and setters. Getters uses the `get` keyword whereas Setters uses the `set` keyword.

      ```javascript
      var user = {
        firstName: "John",
        lastName: "Abraham",
        language: "en",
        get lang() {
          return this.language;
        },
        set lang(lang) {
          this.language = lang;
        },
      };
      console.log(user.lang); // getter access lang as en
      user.lang = "fr";
      console.log(user.lang); // setter used to set lang as fr
      ```

      **[⬆ Back to Top](#table-of-contents)**

130. ### How do you define property on Object constructor

      The `Object.defineProperty()` static method is used to define a new property directly on an object, or modify an existing property on an object, and returns the object. Let's see an example to know how to define property,

      ```javascript
      const newObject = {};

      Object.defineProperty(newObject, "newProperty", {
        value: 100,
        writable: false,
      });

      console.log(newObject.newProperty); // 100

      newObject.newProperty = 200; // It throws an error in strict mode due to writable setting
      ```

      **[⬆ Back to Top](#table-of-contents)**

131. ### What are the advantages of Getters and Setters

      Below are the list of benefits of Getters and Setters,

      1. They provide simpler syntax
      2. They are used for defining computed properties, or accessors in JS.
      3. Useful to provide equivalence relation between properties and methods
      4. They can provide better data quality
      5. Useful for doing things behind the scenes with the encapsulated logic.

      **[⬆ Back to Top](#table-of-contents)**

132. ### Can I add getters and setters using defineProperty method

      Yes, You can use the `Object.defineProperty()` method to add Getters and Setters. For example, the below counter object uses increment, decrement, add and subtract properties,

      ```javascript
      var obj = { counter: 0 };

      // Define getters
      Object.defineProperty(obj, "increment", {
        get: function () {
          this.counter++;
          return this.counter;
        },
      });
      Object.defineProperty(obj, "decrement", {
        get: function () {
          this.counter--;
          return this.counter;
        },
      });

      // Define setters
      Object.defineProperty(obj, "add", {
        set: function (value) {
          this.counter += value;
        },
      });
      Object.defineProperty(obj, "subtract", {
        set: function (value) {
          this.counter -= value;
        },
      });

      obj.add = 10;
      obj.subtract = 5;
      console.log(obj.increment); //6
      console.log(obj.decrement); //5
      ```

      **[⬆ Back to Top](#table-of-contents)**

133. ### What is the purpose of switch-case

      The `switch case` statement in JavaScript is used for decision making purposes. In a few cases, using the `switch case` statement is going to be more convenient than `if-else` statements. The syntax would be as below,

      ```javascript
      switch (expression)
      {
          case value1:
              statement1;
              break;
          case value2:
              statement2;
              break;
          .
          .
          case valueN:
              statementN;
              break;
          default:
              statementDefault;
      }
      ```

      The above multi-way branch statement provides an easy way to dispatch execution to different parts of code based on the value of the expression.

      **[⬆ Back to Top](#table-of-contents)**

134. ### What are the conventions to be followed for the usage of switch case

      Below are the list of conventions should be taken care,

      1. The expression can be of type either number or string.
      2. Duplicate values are not allowed for the expression.
      3. The default statement is optional. If the expression passed to switch does not match with any case value then the statement within default case will be executed.
      4. The break statement is used inside the switch to terminate a statement sequence.
      5. The break statement is optional. But if it is omitted, the execution will continue on into the next case.

      **[⬆ Back to Top](#table-of-contents)**

135. ### What are primitive data types

      A primitive data type is data that has a primitive value (which has no properties or methods). There are 7 types of primitive data types.

      1. string
      2. number
      3. boolean
      4. null
      5. undefined
      6. bigint
      7. symbol

      **[⬆ Back to Top](#table-of-contents)**

136. ### What are the different ways to access object properties

      There are 3 possible ways for accessing the property of an object.

      1. **Dot notation:** It uses dot for accessing the properties

      ```javascript
      objectName.property;
      ```

      2. **Square brackets notation:** It uses square brackets for property access

      ```javascript
      objectName["property"];
      ```

      3. **Expression notation:** It uses expression in the square brackets

      ```javascript
      objectName[expression];
      ```

      **[⬆ Back to Top](#table-of-contents)**

137. ### What are the function parameter rules

      JavaScript functions follow below rules for parameters,

      1. The function definitions do not specify data types for parameters.
      2. Do not perform type checking on the passed arguments.
      3. Do not check the number of arguments received.
         i.e, The below function follows the above rules,

      ```javascript
      function functionName(parameter1, parameter2, parameter3) {
        console.log(parameter1); // 1
      }
      functionName(1);
      ```

      **[⬆ Back to Top](#table-of-contents)**

138. ### What is an error object

      An error object is a built in error object that provides error information when an error occurs. It has two properties: name and message. For example, the below function logs error details,

      ```javascript
      try {
        greeting("Welcome");
      } catch (err) {
        console.log(err.name + "<br>" + err.message);
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

139. ### When do you get a syntax error

      A SyntaxError is thrown if you try to evaluate code with a syntax error. For example, the below missing quote for the function parameter throws a syntax error

      ```javascript
      try {
        eval("greeting('welcome)"); // Missing ' will produce an error
      } catch (err) {
        console.log(err.name);
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

140. ### What are the different error names from error object

      There are 7 different types of error names returned from error object,
      | Error Name | Description |
      |---- | ---------
      | `AggregateError` | An error indicating that multiple errors occurred |
      | `EvalError` | An error has occurred in the eval() function |
      | `RangeError` | An error has occurred with a number "out of range" |
      | `ReferenceError` | An error due to an illegal reference|
      | `SyntaxError` | An error due to a syntax error|
      | `TypeError` | An error due to a type error |
      | `URIError` | An error due to encodeURI() |

      **[⬆ Back to Top](#table-of-contents)**

141. ### What are the two types of loops in javascript

      1. **Entry Controlled loops:** In this kind of loop type, the test condition is tested before entering the loop body. For example, For Loop and While Loop comes under this category.
      2. **Exit Controlled Loops:** In this kind of loop type, the test condition is tested or evaluated at the end of the loop body. i.e, the loop body will execute at least once irrespective of test condition true or false. For example, do-while loop comes under this category.

      **[⬆ Back to Top](#table-of-contents)**

142. ### What is nodejs

      Node.js is a server-side platform built on Chrome's JavaScript runtime for easily building fast and scalable network applications. It is an event-based, non-blocking, asynchronous I/O runtime that uses Google's V8 JavaScript engine and libuv library.

      **[⬆ Back to Top](#table-of-contents)**

143. ### What is the Intl object

      The `Intl` object is the namespace for the ECMAScript Internationalization API, which provides language sensitive string comparison, number formatting, and date and time formatting. It provides access to several constructors and language sensitive functions.

      **[⬆ Back to Top](#table-of-contents)**

144. ### How do you perform language specific date and time formatting

      You can use the `Intl.DateTimeFormat` object which is a constructor for objects that enable language-sensitive date and time formatting. Let's see this behavior with an example,

      ```javascript
      var date = new Date(Date.UTC(2019, 07, 07, 3, 0, 0));
      console.log(new Intl.DateTimeFormat("en-GB").format(date)); // 07/08/2019
      console.log(new Intl.DateTimeFormat("en-AU").format(date)); // 07/08/2019
      ```

      **[⬆ Back to Top](#table-of-contents)**

145. ### What is an Iterator

      An iterator is an object which defines a sequence and a return value upon its termination. It implements the Iterator protocol with a `next()` method which returns an object with two properties: `value` (the next value in the sequence) and `done` (which is true if the last value in the sequence has been consumed).

      **[⬆ Back to Top](#table-of-contents)**

146. ### How does synchronous iteration works

      Synchronous iteration was introduced in ES6 and it works with below set of components,

      **Iterable:** It is an object which can be iterated over via a method whose key is Symbol.iterator.

      **Iterator:** It is an object returned by invoking `[Symbol.iterator]()` on an iterable. This iterator object wraps each iterated element in an object and returns it via `next()` method one by one.

      **IteratorResult:** It is an object returned by `next()` method. The object contains two properties; the `value` property contains an iterated element and the `done` property determines whether the element is the last element or not.

      Let's demonstrate synchronous iteration with an array as below

      ```javascript
      const iterable = ["one", "two", "three"];
      const iterator = iterable[Symbol.iterator]();
      console.log(iterator.next()); // { value: 'one', done: false }
      console.log(iterator.next()); // { value: 'two', done: false }
      console.log(iterator.next()); // { value: 'three', done: false }
      console.log(iterator.next()); // { value: 'undefined, done: true }
      ```

      **[⬆ Back to Top](#table-of-contents)**

147. ### What is the event loop

      The event loop is a process that continuously monitors both the call stack and the event queue and checks whether or not the call stack is empty. If the call stack is empty and there are pending events in the event queue, the event loop dequeues the event from the event queue and pushes it to the call stack. The call stack executes the event, and any additional events generated during the execution are added to the end of the event queue.

      **Note:** The event loop allows Node.js to perform non-blocking I/O operations, even though JavaScript is single-threaded, by offloading operations to the system kernel whenever possible. Since most modern kernels are multi-threaded, they can handle multiple operations executing in the background.

      **[⬆ Back to Top](#table-of-contents)**

148. ### What is the call stack

      Call Stack is a data structure for javascript interpreters to keep track of function calls(creates execution context) in the program. It has two major actions,

      1. Whenever you call a function for its execution, you are pushing it to the stack.
      2. Whenever the execution is completed, the function is popped out of the stack.

      Let's take an example and it's state representation in a diagram format

      ```javascript
      function hungry() {
        eatFruits();
      }
      function eatFruits() {
        return "I'm eating fruits";
      }

      // Invoke the `hungry` function
      hungry();
      ```

      The above code processed in a call stack as below,

      3. Add the `hungry()` function to the call stack list and execute the code.
      4. Add the `eatFruits()` function to the call stack list and execute the code.
      5. Delete the `eatFruits()` function from our call stack list.
      6. Delete the `hungry()` function from the call stack list since there are no items anymore.

      ![Screenshot](images/call-stack.png)

      **[⬆ Back to Top](#table-of-contents)**

149. ### What is the event queue

      The event queue follows the queue data structure. It stores async callbacks to be added to the call stack. It is also known as the Callback Queue or Macrotask Queue.

      Whenever the call stack receives an async function, it is moved into the Web API. Based on the function, Web API executes it and awaits the result. Once it is finished, it moves the callback into the event queue (the callback of a promise is moved into the microtask queue).

      The event loop constantly checks whether or not the call stack is empty. Once the call stack is empty and there is a callback in the event queue, the event loop moves the callback into the call stack. But if there is a callback in the microtask queue as well, it is moved first. The microtask queue has a higher priority than the event queue.

      **[⬆ Back to Top](#table-of-contents)**

150. ### What is a decorator

      A decorator is an expression that evaluates to a function and that takes the target, name, and decorator descriptor as arguments. Also, it optionally returns a decorator descriptor to install on the target object. Let's define admin decorator for user class at design time,

      ```javascript
      function admin(isAdmin) {
         return function(target) {
             target.isAdmin = isAdmin;
         }
      }

      @admin(true)
      class User() {
      }
      console.log(User.isAdmin); //true

       @admin(false)
       class User() {
       }
       console.log(User.isAdmin); //false
      ```

      **[⬆ Back to Top](#table-of-contents)**

151. ### What are the properties of the Intl object

      Below are the list of properties available on the `Intl` object,

      1. **Collator:** These are the objects that enable language-sensitive string comparison.
      2. **DateTimeFormat:** These are the objects that enable language-sensitive date and time formatting.
      3. **ListFormat:** These are the objects that enable language-sensitive list formatting.
      4. **NumberFormat:** Objects that enable language-sensitive number formatting.
      5. **PluralRules:** Objects that enable plural-sensitive formatting and language-specific rules for plurals.
      6. **RelativeTimeFormat:** Objects that enable language-sensitive relative time formatting.

      **[⬆ Back to Top](#table-of-contents)**

152. ### How do you sort elements in an array

      The `sort()` method is used to sort the elements of an array in place and returns the sorted array. The default sort order is ascending, based on the string Unicode order. The example usage would be as below,

      ```javascript
      var months = ["Aug", "Sep", "Jan", "June"];
      months.sort();
      console.log(months); //  ["Aug", "Jan", "June", "Sep"]
      ```

      **Beware:** `sort()` is changing the original array.

      **[⬆ Back to Top](#table-of-contents)**

153. ### What is the purpose of compareFunction while sorting arrays

      The compareFunction is used to define the sort order. If omitted, the array elements are converted to strings, then sorted according to each character's Unicode code point value.

      Let's take an example to see the usage of compareFunction,

      ```javascript
      let numbers = [1, 2, 5, 3, 4];
      numbers.sort((a, b) => b - a);
      console.log(numbers); // [5, 4, 3, 2, 1]
      ```

      **[⬆ Back to Top](#table-of-contents)**

154. ### How do you reverse an array

      You can use the `reverse()` method to reverse the elements in an array. This method is useful to sort an array in descending order. Let's see the usage of `reverse()` method in an example,

      ```javascript
      let numbers = [1, 2, 5, 3, 4];
      numbers.sort((a, b) => b - a);
      numbers.reverse();
      console.log(numbers); // [1, 2, 3, 4 ,5]
      ```

      **[⬆ Back to Top](#table-of-contents)**

155. ### How do you find the min and max values in an array

      You can use `Math.min` and `Math.max` methods on array variables to find the minimum and maximum elements within an array. Let's create two functions to find the min and max value with in an array,

      ```javascript
      var marks = [50, 20, 70, 60, 45, 30];
      function findMin(arr) {
        return Math.min.apply(null, arr);
      }
      function findMax(arr) {
        return Math.max.apply(null, arr);
      }

      console.log(findMin(marks));
      console.log(findMax(marks));
      ```

      **[⬆ Back to Top](#table-of-contents)**

156. ### How do you find the min and max values without Math functions

      You can write functions which loop through an array comparing each value with the lowest value or highest value to find the min and max values. Let's create those functions to find min and max values,

      ```javascript
      var marks = [50, 20, 70, 60, 45, 30];
      function findMin(arr) {
        var length = arr.length;
        var min = Infinity;
        while (length--) {
          if (arr[length] < min) {
            min = arr[length];
          }
        }
        return min;
      }

      function findMax(arr) {
        var length = arr.length;
        var max = -Infinity;
        while (length--) {
          if (arr[length] > max) {
            max = arr[length];
          }
        }
        return max;
      }

      console.log(findMin(marks));
      console.log(findMax(marks));
      ```

      **[⬆ Back to Top](#table-of-contents)**

157. ### How do you get the metadata of a module

      You can use the `import.meta` object which is a meta-property exposing context-specific meta data to a JavaScript module. It contains information about the current module, such as the module's URL. In browsers, you might get different meta data than NodeJS.

      ```javascript
      <script type="module" src="welcome-module.js"></script>;
      console.log(import.meta); // { url: "file:///home/user/welcome-module.js" }
      ```

      **[⬆ Back to Top](#table-of-contents)**

158. ### What is the comma operator

      The comma operator is used to evaluate each of its operands from left to right and returns the value of the last operand. This is totally different from comma usage within arrays, objects, and function arguments and parameters. For example, the usage for numeric expressions would be as below,

      ```javascript
      var x = 1;
      x = (x++, x);

      console.log(x); // 2
      ```

      **[⬆ Back to Top](#table-of-contents)**

159. ### What is the advantage of the comma operator

      It is normally used to include multiple expressions in a location that requires a single expression. One of the common usages of this comma operator is to supply multiple parameters in a `for` loop. For example, the below for loop uses multiple expressions in a single location using comma operator,

      ```javascript
      for (var a = 0, b =10; a <= 10; a++, b--)
      ```

      You can also use the comma operator in a return statement where it processes before returning.

      ```javascript
      function myFunction() {
        var a = 1;
        return (a += 10), a; // 11
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

160. ### What is typescript

      TypeScript is a typed superset of JavaScript created by Microsoft that adds optional types, classes
      and many other features, and compiles to plain JavaScript. Angular is built entirely in TypeScript and it is used as the primary language there. You can install it globally as

      ```bash
      npm install -g typescript
      ```

      Let's see a simple example of TypeScript usage,

      ```typescript
      function greeting(name: string): string {
        return "Hello, " + name;
      }

      let user = "Sudheer";

      console.log(greeting(user));
      ```

      The greeting method allows only string type as argument.

      **[⬆ Back to Top](#table-of-contents)**

161. ### What are the differences between javascript and typescript

      Below are the list of differences between javascript and typescript,

      | feature             | typescript                            | javascript                                      |
      | ------------------- | ------------------------------------- | ----------------------------------------------- |
      | Language paradigm   | Object oriented programming language  | Multi-paradigm language                         |
      | Typing support      | Supports static typing                | Dynamic typing                                  |
      | Modules             | Supported                             | Not supported                                   |
      | Interface           | It has interfaces concept             | Doesn't support interfaces                      |
      | Optional parameters | Functions support optional parameters | No support of optional parameters for functions |

      **[⬆ Back to Top](#table-of-contents)**

162. ### What is an object initializer

      An object initializer is an expression that describes the initialization of an Object. The syntax for this expression is represented as a comma-delimited list of zero or more pairs of property names and associated values of an object, enclosed in curly braces ({}). This is also known as literal notation. It is one of the ways to create an object.

      ```javascript
      var initObject = { a: "John", b: 50, c: {} };

      console.log(initObject.a); // John
      ```

      **[⬆ Back to Top](#table-of-contents)**

163. ### What is a constructor method

      The constructor method is a special method for creating and initializing an object created within a class. If you do not specify a constructor method, a default constructor is used. The example usage of constructor would be as below,

      ```javascript
      class Employee {
        constructor() {
          this.name = "John";
        }
      }

      var employeeObject = new Employee();

      console.log(employeeObject.name); // John
      ```

      **[⬆ Back to Top](#table-of-contents)**

164. ### What happens if you write constructor more than once in a class

      The "constructor" in a class is a special method and it should be defined only once in a class. i.e, If you write a constructor method more than once in a class it will throw a `SyntaxError` error.

      ```javascript
       class Employee {
         constructor() {
           this.name = "John";
         }
         constructor() {   //  Uncaught SyntaxError: A class may only have one constructor
           this.age = 30;
         }
       }

       var employeeObject = new Employee();

       console.log(employeeObject.name);
      ```

      This constructor is called by using the special function call `new` (see example above).

      **[⬆ Back to Top](#table-of-contents)**

165. ### How do you call the constructor of a parent class

      You can use the `super` keyword to call the constructor of a parent class. Remember that `super()` must be called before using `this` reference. Otherwise it will cause a reference error. Let's the usage of it,

      ```javascript
      class Square extends Rectangle {
        constructor(length) {
          super(length, length);
          this.name = "Square";
        }

        get area() {
          return this.width * this.height;
        }

        set area(value) {
          this.area = value;
        }
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

166. ### How do you get the prototype of an object

      You can use the `Object.getPrototypeOf(obj)` method to return the prototype of the specified object. i.e. The value of the internal `prototype` property. If there are no inherited properties then `null` value is returned.

      ```javascript
      const newPrototype = {};
      const newObject = Object.create(newPrototype);

      console.log(Object.getPrototypeOf(newObject) === newPrototype); // true
      ```

      **[⬆ Back to Top](#table-of-contents)**

167. ### What happens If I pass string type for getPrototype method

      In ES5, it will throw a TypeError exception if the obj parameter isn't an object. Whereas in ES2015, the parameter will be coerced to an `Object`.

      ```javascript
      // ES5
      Object.getPrototypeOf("James"); // TypeError: "James" is not an object
      // ES2015
      Object.getPrototypeOf("James"); // String.prototype
      ```

      **[⬆ Back to Top](#table-of-contents)**

168. ### How do you set the prototype of one object to another

      You can use the `Object.setPrototypeOf()` method that sets the prototype (i.e., the internal `Prototype` property) of a specified object to another object or null. For example, if you want to set prototype of a square object to rectangle object would be as follows,

      ```javascript
      Object.setPrototypeOf(Square.prototype, Rectangle.prototype);
      Object.setPrototypeOf({}, null);
      ```

      **[⬆ Back to Top](#table-of-contents)**

169. ### How do you check whether an object can be extended or not

      The `Object.isExtensible()` method is used to determine if an object is extendable or not. i.e, Whether it can have new properties added to it or not.

      ```javascript
      const newObject = {};
      console.log(Object.isExtensible(newObject)); //true
      ```

      **Note:** By default, all the objects are extendable. i.e, The new properties can be added or modified.

      **[⬆ Back to Top](#table-of-contents)**

170. ### How do you prevent an object from being extend

      The `Object.preventExtensions()` method is used to prevent new properties from ever being added to an object. In other words, it prevents future extensions to the object. Let's see the usage of this property,

      ```javascript
      const newObject = {};
      Object.preventExtensions(newObject); // NOT extendable

      try {
        Object.defineProperty(newObject, "newProperty", {
          // Adding new property
          value: 100,
        });
      } catch (e) {
        console.log(e); // TypeError: Cannot define property newProperty, object is not extensible
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

171. ### What are the different ways to make an object non-extensible

      You can mark an object non-extensible in 3 ways,

      1. `Object.preventExtensions`
      2. `Object.seal`
      3. `Object.freeze`

      ```javascript
      var newObject = {};

      Object.preventExtensions(newObject); // Prevent objects are non-extensible
      Object.isExtensible(newObject); // false

      var sealedObject = Object.seal({}); // Sealed objects are non-extensible
      Object.isExtensible(sealedObject); // false

      var frozenObject = Object.freeze({}); // Frozen objects are non-extensible
      Object.isExtensible(frozenObject); // false
      ```

      **[⬆ Back to Top](#table-of-contents)**

172. ### How do you define multiple properties on an object

      The `Object.defineProperties()` method is used to define new or modify existing properties directly on an object and returning the object. Let's define multiple properties on an empty object,

      ```javascript
      const newObject = {};

      Object.defineProperties(newObject, {
        newProperty1: {
          value: "John",
          writable: true,
        },
        newProperty2: {},
      });
      ```

      **[⬆ Back to Top](#table-of-contents)**

173. ### What is obfuscation in javascript

      Obfuscation is the deliberate act of creating obfuscated javascript code(i.e, source or machine code) that is difficult for humans to understand. It is something similar to encryption, but a machine can understand the code and execute it.
      Let's see the below function before Obfuscation,

      ```javascript
      function greeting() {
        console.log("Hello, welcome to JS world");
      }
      ```

      And after the code Obfuscation, it would be appeared as below,

      ```javascript
      eval(
        (function (p, a, c, k, e, d) {
          e = function (c) {
            return c;
          };
          if (!"".replace(/^/, String)) {
            while (c--) {
              d[c] = k[c] || c;
            }
            k = [
              function (e) {
                return d[e];
              },
            ];
            e = function () {
              return "\\w+";
            };
            c = 1;
          }
          while (c--) {
            if (k[c]) {
              p = p.replace(new RegExp("\\b" + e(c) + "\\b", "g"), k[c]);
            }
          }
          return p;
        })(
          "2 1(){0.3('4, 7 6 5 8')}",
          9,
          9,
          "console|greeting|function|log|Hello|JS|to|welcome|world".split("|"),
          0,
          {}
        )
      );
      ```

      **[⬆ Back to Top](#table-of-contents)**

174. ### Why do you need Obfuscation

      Below are the few reasons for Obfuscation,

      1. The Code size will be reduced. So data transfers between server and client will be fast.
      2. It hides the business logic from outside world and protects the code from others
      3. Reverse engineering is highly difficult
      4. The download time will be reduced

      **[⬆ Back to Top](#table-of-contents)**

175. ### What are the advantages of minification

      Normally it is recommended to use minification for heavy traffic and intensive requirements of resources. It reduces file sizes with below benefits,

      1. Decreases loading times of a web page
      2. Saves bandwidth usages

      **[⬆ Back to Top](#table-of-contents)**

176. ### What are the differences between obfuscation and Encryption

      Below are the main differences between obfuscation and encryption,

      | Feature            | Obfuscation                                     | Encryption                                                              |
      | ------------------ | ----------------------------------------------- | ----------------------------------------------------------------------- |
      | Definition         | Changing the form of any data in any other form | Changing the form of information to an unreadable format by using a key |
      | A key to decode    | It can be decoded without any key               | It is required                                                          |
      | Target data format | It will be converted to a complex form          | Converted into an unreadable format                                     |

      **[⬆ Back to Top](#table-of-contents)**

177. ### What are the common tools used for minification

      There are many online/offline tools to minify the javascript files,

      1. Google's Closure Compiler
      2. UglifyJS2
      3. jsmin
      4. javascript-minifier.com/
      5. prettydiff.com

      **[⬆ Back to Top](#table-of-contents)**

178. ### How do you perform form validation using javascript

      JavaScript can be used to perform HTML form validation. For example, if the form field is empty, the function needs to notify, and return false, to prevent the form being submitted.
      Lets' perform user login in an html form,

      ```html
      <form name="myForm" onsubmit="return validateForm()" method="post">
        User name:
        <input type="text" name="uname" />
        <input type="submit" value="Submit" />
      </form>
      ```

      And the validation on user login is below,

      ```javascript
      function validateForm() {
        var x = document.forms["myForm"]["uname"].value;
        if (x == "") {
          alert("The username shouldn't be empty");
          return false;
        }
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

179. ### What are the validity properties

      The validity property of an input element provides a set of properties related to the validity of data.

      1. `customError`: It returns true, if a custom validity message is set.
      2. `patternMismatch`: It returns true, if an element's value does not match its pattern attribute.
      3. `rangeOverflow`: It returns true, if an element's value is greater than its max attribute.
      4. `rangeUnderflow`: It returns true, if an element's value is less than its min attribute.
      5. `stepMismatch`: It returns true, if an element's value is invalid according to step attribute.
      6. `tooLong`: It returns true, if an element's value exceeds its maxLength attribute.
      7. `typeMismatch`: It returns true, if an element's value is invalid according to type attribute.
      8. `valueMissing`: It returns true, if an element with a required attribute has no value.
      9. `valid`: It returns true, if an element's value is valid.

      **[⬆ Back to Top](#table-of-contents)**

180. ### Are enums available in javascript

      No, javascript does not natively support enums. But there are different kinds of solutions to simulate them even though they may not provide exact equivalents. For example, you can use freeze or seal on object,

      ```javascript
      var DaysEnum = Object.freeze({"monday":1, "tuesday":2, "wednesday":3, ...})
      ```

      **[⬆ Back to Top](#table-of-contents)**

181. ### How do you list all properties of an object

      You can use the `Object.getOwnPropertyNames()` method which returns an array of all properties found directly in a given object. Let's see the usage of this in an example below:

      ```javascript
      const newObject = {
        a: 1,
        b: 2,
        c: 3,
      };

      console.log(Object.getOwnPropertyNames(newObject));
      ["a", "b", "c"];
      ```

      **[⬆ Back to Top](#table-of-contents)**

182. ### How do you get property descriptors of an object

      You can use the `Object.getOwnPropertyDescriptors()` method which returns all own property descriptors of a given object. The example usage of this method is below,

      ```javascript
      const newObject = {
        a: 1,
        b: 2,
        c: 3,
      };
      const descriptorsObject = Object.getOwnPropertyDescriptors(newObject);
      console.log(descriptorsObject.a.writable); //true
      console.log(descriptorsObject.a.configurable); //true
      console.log(descriptorsObject.a.enumerable); //true
      console.log(descriptorsObject.a.value); // 1
      ```

      **[⬆ Back to Top](#table-of-contents)**

183. ### What are the attributes provided by a property descriptor

      A property descriptor is a record which has the following attributes

      1. `value`: The value associated with the property
      2. `writable`: Determines whether the value associated with the property can be changed or not
      3. `configurable`: Returns true if the type of this property descriptor can be changed and if the property can be deleted from the corresponding object.
      4. `enumerable`: Determines whether the property appears during enumeration of the properties on the corresponding object or not.
      5. `set`: A function which serves as a setter for the property
      6. `get`: A function which serves as a getter for the property

      **[⬆ Back to Top](#table-of-contents)**

184. ### How do you extend classes

      The `extends` keyword is used in class declarations/expressions to create a class which is a child of another class. It can be used to subclass custom classes as well as built-in objects. The syntax would be as below,

      ```javascript
      class ChildClass extends ParentClass { ... }
      ```

      Let's take an example of Square subclass from Polygon parent class,

      ```javascript
      class Square extends Rectangle {
        constructor(length) {
          super(length, length);
          this.name = "Square";
        }

        get area() {
          return this.width * this.height;
        }

        set area(value) {
          this.area = value;
        }
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

185. ### How do you check whether or not an array includes a particular value

      The `Array#includes()` method is used to determine whether an array includes a particular value among its entries by returning either true or false. Let's see an example to find an element(numeric and string) within an array.

      ```javascript
      var numericArray = [1, 2, 3, 4];
      console.log(numericArray.includes(3)); // true

      var stringArray = ["green", "yellow", "blue"];
      console.log(stringArray.includes("blue")); //true
      ```

      **[⬆ Back to Top](#table-of-contents)**

186. ### How do you compare scalar arrays

      You can use length and every method of arrays to compare two scalars (compared directly using `===`) arrays. The combination of these expressions can give the expected result,

      ```javascript
      const arrayFirst = [1, 2, 3, 4, 5];
      const arraySecond = [1, 2, 3, 4, 5];
      console.log(
        arrayFirst.length === arraySecond.length &&
          arrayFirst.every((value, index) => value === arraySecond[index])
      ); // true
      ```

      If you would like to compare arrays irrespective of order then you should sort them before,

      ```javascript
      const arrayFirst = [2, 3, 1, 4, 5];
      const arraySecond = [1, 2, 3, 4, 5];
      console.log(
        arrayFirst.length === arraySecond.length &&
          arrayFirst
            .sort()
            .every((value, index) => value === arraySecond[index])
      ); //true
      ```

      **[⬆ Back to Top](#table-of-contents)**

187. ### How do you print numbers with commas as thousand separators

      You can use the `Number.prototype.toLocaleString()` method which returns a string with a language-sensitive representation such as thousand separator, currency etc. of this number.

      ```javascript
      function convertToThousandFormat(x) {
        return x.toLocaleString(); // 12,345.679
      }

      console.log(convertToThousandFormat(12345.6789));
      ```

      **[⬆ Back to Top](#table-of-contents)**

188. ### How do you get the timezone offset of a date object

      You can use the `getTimezoneOffset` method of the date object. This method returns the time zone difference, in minutes, from current locale (host system settings) to UTC

      ```javascript
      var offset = new Date().getTimezoneOffset();
      console.log(offset); // -480
      ```

      **[⬆ Back to Top](#table-of-contents)**

189. ### What is a void operator

      The `void` operator evaluates the given expression and then returns `undefined` (i.e, without returning value). The syntax would be as below,

      ```javascript
      void expression;
      void expression;
      ```

      Let's display a message without any redirection or reload

      ```javascript
      <a href="javascript:void(alert('Welcome to JS world'))">
        Click here to see a message
      </a>
      ```

      **Note:** This operator is often used to obtain the undefined primitive value, using `void(0)`. Also it can be used to call asynchronous functions without waiting for the result.

      **[⬆ Back to Top](#table-of-contents)**

190. ### How do you create an infinite loop

      You can create infinite loops using for and while loops without using any expressions. The for loop construct or syntax is better approach in terms of ESLint and code optimizer tools,

      ```javascript
      for (;;) {}
      while (true) {}
      ```

      **[⬆ Back to Top](#table-of-contents)**

191. ### What is ES6

      ES6 is the sixth edition of the javascript language and it was released in June 2015. It was initially known as ECMAScript 6 (ES6) and later renamed to ECMAScript 2015. Almost all the modern browsers support ES6 but for the old browsers there are many transpilers, like Babel.js etc.

      **[⬆ Back to Top](#table-of-contents)**

192. ### What are default parameters

      In ES5, we need to depend on logical OR operators to handle default values of function parameters. Whereas in ES6, Default function parameters feature allows parameters to be initialized with default values if no value or undefined is passed. Let's compare the behavior with an examples,

      ```javascript
      //ES5
      var calculateArea = function (height, width) {
        height = height || 50;
        width = width || 60;

        return width * height;
      };
      console.log(calculateArea()); //300
      ```

      The default parameters makes the initialization more simpler,

      ```javascript
      //ES6
      var calculateArea = function (height = 50, width = 60) {
        return width * height;
      };

      console.log(calculateArea()); //300
      ```

      **[⬆ Back to Top](#table-of-contents)**

193. ### What are template literals

      Template literals or template strings are string literals allowing embedded expressions. These are enclosed by the back-tick (`) character instead of double or single quotes.
      In ES6, this feature enables using dynamic expressions as below,

      ```javascript
      var greeting = `Welcome to JS World, Mr. ${firstName} ${lastName}.`;
      ```

      In ES5, you need break string like below,

      ```javascript
      var greeting = 'Welcome to JS World, Mr. ' + firstName + ' ' + lastName.`
      ```

      **Note:** You can use multi-line strings and string interpolation features with template literals.

      **[⬆ Back to Top](#table-of-contents)**

194. ### How do you write multi-line strings in template literals

      In ES5, you would have to use newline escape characters('\\n') and concatenation symbols(+) in order to get multi-line strings.

      ```javascript
      console.log("This is string sentence 1\n" + "This is string sentence 2");
      ```

      Whereas in ES6, You don't need to mention any newline sequence character,

      ```javascript
      console.log(`This is string sentence
      'This is string sentence 2`);
      ```

      **[⬆ Back to Top](#table-of-contents)**

195. ### What are tagged templates

      Tagged templates are the advanced form of templates in which tags allow you to parse template literals with a function. The tag function accepts the first parameter as an array of strings and remaining parameters as expressions. This function can also return manipulated strings based on parameters. Let's see the usage of this tagged template behavior of an IT professional skill set in an organization,

      ```javascript
      var user1 = "John";
      var skill1 = "JavaScript";
      var experience1 = 15;

      var user2 = "Kane";
      var skill2 = "JavaScript";
      var experience2 = 5;

      function myInfoTag(strings, userExp, experienceExp, skillExp) {
        var str0 = strings[0]; // "Mr/Ms. "
        var str1 = strings[1]; // " is a/an "
        var str2 = strings[2]; // "in"

        var expertiseStr;
        if (experienceExp > 10) {
          expertiseStr = "expert developer";
        } else if (skillExp > 5 && skillExp <= 10) {
          expertiseStr = "senior developer";
        } else {
          expertiseStr = "junior developer";
        }

        return `${str0}${userExp}${str1}${expertiseStr}${str2}${skillExp}`;
      }

      var output1 = myInfoTag`Mr/Ms. ${user1} is a/an ${experience1} in ${skill1}`;
      var output2 = myInfoTag`Mr/Ms. ${user2} is a/an ${experience2} in ${skill2}`;

      console.log(output1); // Mr/Ms. John is a/an expert developer in JavaScript
      console.log(output2); // Mr/Ms. Kane is a/an junior developer in JavaScript
      ```

      **[⬆ Back to Top](#table-of-contents)**

196. ### What are raw strings

      ES6 provides a raw strings feature using the `String.raw()` method which is used to get the raw string form of template strings. This feature allows you to access the raw strings as they were entered, without processing escape sequences. For example, the usage would be as below,

      ```javascript
      var calculationString = String.raw`The sum of numbers is \n${
        1 + 2 + 3 + 4
      }!`;
      console.log(calculationString); // The sum of numbers is \n10!
      ```

      If you don't use raw strings, the newline character sequence will be processed by displaying the output in multiple lines

      ```javascript
      var calculationString = `The sum of numbers is \n${1 + 2 + 3 + 4}!`;
      console.log(calculationString);
      // The sum of numbers is
      // 10!
      ```

      Also, the raw property is available on the first argument to the tag function

      ```javascript
      function tag(strings) {
        console.log(strings.raw[0]);
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

197. ### What are enhanced object literals

      Object literals make it easy to quickly create objects with properties inside the curly braces. For example, it provides shorter syntax for common object property definition as below.

      ```javascript
      //ES6
      var x = 10,
        y = 20;
      obj = { x, y };
      console.log(obj); // {x: 10, y:20}
      //ES5
      var x = 10,
        y = 20;
      obj = { x: x, y: y };
      console.log(obj); // {x: 10, y:20}
      ```

      **[⬆ Back to Top](#table-of-contents)**

198. ### What are dynamic imports

      The dynamic imports using `import()` function syntax allows us to load modules on demand by using promises or the async/await syntax. Currently this feature is in [stage4 proposal](https://github.com/tc39/proposal-dynamic-import). The main advantage of dynamic imports is reduction of our bundle's sizes, the size/payload response of our requests and overall improvements in the user experience.
      The syntax of dynamic imports would be as below,

      ```javascript
      import("./Module").then((Module) => Module.method());
      ```

      **[⬆ Back to Top](#table-of-contents)**

199. ### What are typed arrays

      Typed arrays are array-like objects from ECMAScript 6 API for handling binary data. JavaScript provides 12 Typed array types,

      1. Int8Array: An array of 8-bit signed integers
      2. Uint8Array: An array of 8-bit unsigned integers
      3. Uint8ClampedArray: An array of 8-bit unsigned integers clamped to 0-255
      4. Int16Array: An array of 16-bit signed integers
      5. Uint16Array: An array of 16-bit unsigned integers
      6. Int32Array: An array of 32-bit signed integers
      7. Uint32Array: An array of 32-bit unsigned integers
      8. BigInt64Array: An array of 64-bit signed BigInts
      9. BigUint64Array: An array of 64-bit unsigned BigInts
      10. Float16Array: An array of 16-bit floating point numbers
      11. Float32Array: An array of 32-bit floating point numbers
      12. Float64Array: An array of 64-bit floating point numbers

      For example, you can create an array of 8-bit signed integers as below

      ```javascript
      const a = new Int8Array();
      // You can pre-allocate n bytes
      const bytes = 1024;
      const a = new Int8Array(bytes);
      ```

      **[⬆ Back to Top](#table-of-contents)**

200. ### What are the advantages of module loaders

      The module loaders provides the below features,

      1. Dynamic loading
      2. State isolation
      3. Global namespace isolation
      4. Compilation hooks
      5. Nested virtualization

      **[⬆ Back to Top](#table-of-contents)**

201. ### What is collation

      Collation is used for sorting a set of strings and searching within a set of strings. It is parameterized by locale and aware of Unicode. Let's take comparison and sorting features,

      1. **Comparison:**

      ```javascript
      var list = ["ä", "a", "z"]; // In German,  "ä" sorts with "a" Whereas in Swedish, "ä" sorts after "z"
      var l10nDE = new Intl.Collator("de");
      var l10nSV = new Intl.Collator("sv");
      console.log(l10nDE.compare("ä", "z") === -1); // true
      console.log(l10nSV.compare("ä", "z") === +1); // true
      ```

      2. **Sorting:**

      ```javascript
      var list = ["ä", "a", "z"]; // In German,  "ä" sorts with "a" Whereas in Swedish, "ä" sorts after "z"
      var l10nDE = new Intl.Collator("de");
      var l10nSV = new Intl.Collator("sv");
      console.log(list.sort(l10nDE.compare)); // [ "a", "ä", "z" ]
      console.log(list.sort(l10nSV.compare)); // [ "a", "z", "ä" ]
      ```

      **[⬆ Back to Top](#table-of-contents)**

202. ### What is for...of statement

      The for...of statement creates a loop iterating over iterable objects or elements such as built-in String, Array, Array-like objects (like arguments or NodeList), TypedArray, Map, Set, and user-defined iterables. The basic usage of for...of statement on arrays would be as below,

      ```javascript
      let arrayIterable = [10, 20, 30, 40, 50];

      for (let value of arrayIterable) {
        value++;
        console.log(value); // 11 21 31 41 51
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

203. ### What is the output of below spread operator array

      ```javascript
      [..."John Resig"];
      ```

      The output of the array is ['J', 'o', 'h', 'n', ' ', 'R', 'e', 's', 'i', 'g']

      **Explanation:** The string is an iterable type and the spread operator within an array maps every character of an iterable to one element. Hence, each character of a string becomes an element within an Array.

      **[⬆ Back to Top](#table-of-contents)**

204. ### Is PostMessage secure

      Yes, postMessages can be considered very secure as long as the programmer/developer is careful about checking the origin and source of an arriving message. But if you try to send/receive a message without verifying its source will create cross-site scripting attacks.

      **[⬆ Back to Top](#table-of-contents)**

205. ### Can I avoid using postMessages completely

      You cannot avoid using postMessages completely(or 100%). Even though your application doesn’t use postMessage considering the risks, a lot of third party scripts use postMessage to communicate with the third party service. So your application might be using postMessage without your knowledge.

      **[⬆ Back to Top](#table-of-contents)**

206. ### Is postMessages synchronous

      The postMessages are synchronous in IE8 browser but they are asynchronous in IE9 and all other modern browsers (i.e, IE9+, Firefox, Chrome, Safari).Due to this asynchronous behaviour, we use a callback mechanism when the postMessage is returned.

      **[⬆ Back to Top](#table-of-contents)**

207. ### What paradigm is Javascript

      JavaScript is a multi-paradigm language, supporting imperative/procedural programming, Object-Oriented Programming and functional programming. JavaScript supports Object-Oriented Programming with prototypical inheritance.

      **[⬆ Back to Top](#table-of-contents)**

208. ### What is the difference between internal and external javascript

      **Internal JavaScript:** It is the source code within the script tag.
      **External JavaScript:** The source code is stored in an external file(stored with .js extension) and referred with in the tag.

      **[⬆ Back to Top](#table-of-contents)**

209. ### Is JavaScript faster than server side script

      Yes, JavaScript is faster than server side scripts. Because JavaScript is a client-side script it does not require any web server’s help for its computation or calculation. So JavaScript is always faster than any server-side script like ASP, PHP, etc.

      **[⬆ Back to Top](#table-of-contents)**

210. ### What is the purpose of double tilde operator

      The double tilde operator(~~) is known as double NOT bitwise operator. This operator is a slightly quicker substitute for Math.floor().

      **[⬆ Back to Top](#table-of-contents)**

211. ### How do you convert character to ASCII code

      You can use the `String.prototype.charCodeAt()` method to convert string characters to ASCII numbers. For example, let's find ASCII code for the first letter of 'ABC' string,

      ```javascript
      "ABC".charCodeAt(0); // returns 65
      ```

      Whereas `String.fromCharCode()` method converts numbers to equal ASCII characters.

      ```javascript
      String.fromCharCode(65, 66, 67); // returns 'ABC'
      ```

      **[⬆ Back to Top](#table-of-contents)**

212. ### What is ArrayBuffer

      An ArrayBuffer object is used to represent a generic, fixed-length raw binary data buffer. You can create it as below,

      ```javascript
      let buffer = new ArrayBuffer(16); // create a buffer of length 16
      alert(buffer.byteLength); // 16
      ```

      To manipulate an ArrayBuffer, we need to use a “view” object.

      ```javascript
      //Create a DataView referring to the buffer
      let view = new DataView(buffer);
      ```

      **[⬆ Back to Top](#table-of-contents)**

213. ### What is the purpose of Error object

      The Error constructor creates an error object and the instances of error objects are thrown when runtime errors occur. The Error object can also be used as a base object for user-defined exceptions. The syntax of error object would be as below,

      ```javascript
      new Error([message[, fileName[, lineNumber]]])
      ```

      You can throw user defined exceptions or errors using Error object in try...catch block as below,

      ```javascript
      try {
        if (withdraw > balance)
          throw new Error("Oops! You don't have enough balance");
      } catch (e) {
        console.log(e.name + ": " + e.message);
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

214. ### What is the purpose of EvalError object

      The EvalError object indicates an error regarding the global `eval()` function. Even though this exception is not thrown by JavaScript anymore, the EvalError object remains for compatibility. The syntax of this expression would be as below,

      ```javascript
      new EvalError([message[, fileName[, lineNumber]]])
      ```

      You can throw EvalError with in try...catch block as below,

      ```javascript
      try {
        throw new EvalError('Eval function error', 'someFile.js', 100);
      } catch (e) {
        console.log(e.message, e.name, e.fileName);              // "Eval function error", "EvalError", "someFile.js"
      ```

      **[⬆ Back to Top](#table-of-contents)**

215. ### Do all objects have prototypes

      No. All objects have prototypes except two exceptions:
      *  **Object.prototype** itself — This is the base object in the prototype chain, and **its prototype is** `null`.
      *   **Objects created with** `**Object.create(null)**` — These are deliberately created with **no prototype**, so they don’t inherit from `Object.prototype`.

      All other standard objects do have a prototype.  

      **[⬆ Back to Top](#table-of-contents)**

216. ### What is the purpose of some method in arrays

      The some() method is used to test whether at least one element in the array passes the test implemented by the provided function. The method returns a boolean value. Let's take an example to test for any odd elements,

      ```javascript
      var array = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

      var odd = (element) => element % 2 !== 0;

      console.log(array.some(odd)); // true (the odd element exists)
      ```

      **[⬆ Back to Top](#table-of-contents)**

217. ### How do you combine two or more arrays

      The concat() method is used to join two or more arrays by returning a new array containing all the elements. The syntax would be as below,

      ```javascript
      array1.concat(array2, array3, ..., arrayX)
      ```

      Let's take an example of array's concatenation with veggies and fruits arrays,

      ```javascript
      var veggies = ["Tomato", "Carrot", "Cabbage"];
      var fruits = ["Apple", "Orange", "Pears"];
      var veggiesAndFruits = veggies.concat(fruits);
      console.log(veggiesAndFruits); // Tomato, Carrot, Cabbage, Apple, Orange, Pears
      ```

      **[⬆ Back to Top](#table-of-contents)**

218. ### How do you create specific number of copies of a string

      The `repeat()` method is used to construct and return a new string which contains the specified number of copies of the string on which it was called, concatenated together. Remember that this method has been added to the ECMAScript 2015 specification.
      Let's take an example of Hello string to repeat it 4 times,

      ```javascript
      "Hello".repeat(4); // 'HelloHelloHelloHello'
      ```

219. ### How do you return all matching strings against a regular expression

      The `matchAll()` method can be used to return an iterator of all results matching a string against a regular expression. For example, the below example returns an array of matching string results against a regular expression,

      ```javascript
      let regexp = /Hello(\d?)/g;
      let greeting = "Hello1Hello2Hello3";

      let greetingList = [...greeting.matchAll(regexp)];

      console.log(greetingList[0][0]); //Hello1
      console.log(greetingList[1][0]); //Hello2
      console.log(greetingList[2][0]); //Hello3
      ```

      **[⬆ Back to Top](#table-of-contents)**

220. ### How do you trim a string at the beginning or ending

      The `trim` method of string prototype is used to trim on both sides of a string. But if you want to trim especially at the beginning or ending of the string then you can use `trimStart/trimLeft` and `trimEnd/trimRight` methods. Let's see an example of these methods on a greeting message,

      ```javascript
      var greeting = "   Hello, Goodmorning!   ";

      console.log(greeting); // "   Hello, Goodmorning!   "
      console.log(greeting.trimStart()); // "Hello, Goodmorning!   "
      console.log(greeting.trimLeft()); // "Hello, Goodmorning!   "

      console.log(greeting.trimEnd()); // "   Hello, Goodmorning!"
      console.log(greeting.trimRight()); // "   Hello, Goodmorning!"
      ```

      **[⬆ Back to Top](#table-of-contents)**

221. ### What is the output of below console statement with unary operator

      Let's take console statement with unary operator as given below,

      ```javascript
      console.log(+"Hello"); // NaN
      ```

      The output of the above console log statement returns NaN. Because the element is prefixed by the unary operator and the JavaScript interpreter will try to convert that element into a number type. Since the conversion fails, the value of the statement results in NaN value.

      **[⬆ Back to Top](#table-of-contents)**

222. ### Does javascript uses mixins

      JavaScript does not have built-in support for mixins as a formal language feature. However, developers commonly implement mixins using various patterns to enable code reuse and composition.

      A mixin is a way to add reusable functionality from one or more objects into a class or another object, without using classical inheritance. It promotes object composition by combining behaviors or properties from different sources into a single destination.

223. ### Mixin Example using Object composition
      ```javascript
      // Define a mixin
      const canEat = {
        eat() {
          console.log("Eating...");
        }
      };

      const canWalk = {
        walk() {
          console.log("Walking...");
        }
      };

      const canRead = {
        read() {
          console.log("Reading...");
        }
      };

      // Create a class
      class Person {
        constructor(name) {
          this.name = name;
        }
      }

      // Apply mixins
      Object.assign(Person.prototype, canEat, canWalk, canRead);

      // Use it
      const person = new Person("Sudheer");
      person.eat();  // Output: Eating...
      person.walk(); // Output: Walking...
      person.read(); // Output: Reading...
      ```
224. ### Benefits
      - Avoids deep inheritance hierarchies
      - Encourages composition over inheritance
      - Promotes reusable and modular code
  
      Modern JavaScript favors mixin alternatives like composition, delegation, higher-order functions, and class mixins to promote reusable and modular code. Libraries like Lodash offer utilities for object composition, while frameworks like Vue.js provide built-in mixin features to promote reusable and modular code.

      **[⬆ Back to Top](#table-of-contents)**

225. ### What is a thunk function

      A thunk is just a function which delays the evaluation of the value. It doesn’t take any arguments but gives the value whenever you invoke the thunk. i.e, It is used not to execute now but it will be sometime in the future. Let's take a synchronous example,

      ```javascript
      const add = (x, y) => x + y;

      const thunk = () => add(2, 3);

      thunk(); // 5
      ```

      **[⬆ Back to Top](#table-of-contents)**

226. ### What are asynchronous thunks

      The asynchronous thunks are useful to make network requests. Let's see an example of network requests,

      ```javascript
      function fetchData(fn) {
        fetch("https://jsonplaceholder.typicode.com/todos/1")
          .then((response) => response.json())
          .then((json) => fn(json));
      }

      const asyncThunk = function () {
        return fetchData(function getData(data) {
          console.log(data);
        });
      };

      asyncThunk();
      ```

      The `getData` function won't be called immediately but it will be invoked only when the data is available from API endpoint. The setTimeout function is also used to make our code asynchronous. The best real time example is redux state management library which uses the asynchronous thunks to delay the actions to dispatch.

      **[⬆ Back to Top](#table-of-contents)**

227. ### What is the output of below function calls

      **Code snippet:**

      ```javascript
      const circle = {
        radius: 20,
        diameter() {
          return this.radius * 2;
        },
        perimeter: () => 2 * Math.PI * this.radius,
      };
      ```

      ```javascript
      console.log(circle.diameter());
      console.log(circle.perimeter());
      ```

      **Output:**

      The output is 40 and NaN. Remember that diameter is a regular function, whereas the value of perimeter is an arrow function. The `this` keyword of a regular function(i.e, diameter) refers to the surrounding scope which is a class(i.e, Shape object). Whereas this keyword of perimeter function refers to the surrounding scope which is a window object. Since there is no radius property on window objects it returns an undefined value and the multiple of number value returns NaN value.

      **[⬆ Back to Top](#table-of-contents)**

228. ### How to remove all line breaks from a string

      The easiest approach is using regular expressions to detect and replace newlines in the string. In this case, we use replace function along with string to replace with, which in our case is an empty string.

      ```javascript
      function remove_linebreaks( var message ) {
          return message.replace( /[\r\n]+/gm, "" );
      }
      ```

      In the above expression, g and m are for global and multiline flags.

      **[⬆ Back to Top](#table-of-contents)**

229. ### What happens with negating an array

      Negating an array with `!` character will coerce the array into a boolean. Since Arrays are considered to be truthy So negating it will return `false`.

      ```javascript
      console.log(![]); // false
      ```

      **[⬆ Back to Top](#table-of-contents)**

230. ### What happens if we add two arrays

      If you add two arrays together, it will convert them both to strings and concatenate them. For example, the result of adding arrays would be as below,

      ```javascript
      console.log(["a"] + ["b"]); // "ab"
      console.log([] + []); // ""
      console.log(![] + []); // "false", because ![] returns false.
      ```

      **[⬆ Back to Top](#table-of-contents)**

231. ### How do you create self string using special characters

      The self string can be formed with the combination of `[]()!+` characters. You need to remember the below conventions to achieve this pattern.

      1. Since Arrays are truthful values, negating the arrays will produce false: ![] === false
      2. As per JavaScript coercion rules, the addition of arrays together will toString them: [] + [] === ""
      3. Prepend an array with + operator will convert an array to false, the negation will make it true and finally converting the result will produce value '1': +(!(+[])) === 1

      By applying the above rules, we can derive below conditions

      ```javascript
      (![] + [] === "false" + !+[]) === 1;
      ```

      Now the character pattern would be created as below,

      ```javascript
            s               e               l               f
       ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^

       (![] + [])[3] + (![] + [])[4] + (![] + [])[2] + (![] + [])[0]
       ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^
      (![] + [])[+!+[]+!+[]+!+[]] +
      (![] + [])[+!+[]+!+[]+!+[]+!+[]] +
      (![] + [])[+!+[]+!+[]] +
      (![] + [])[+[]]
      ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
      (![]+[])[+!+[]+!+[]+!+[]]+(![]+[])[+!+[]+!+[]+!+[]+!+[]]+(![]+[])[+!+[]+!+[]]+(![]+[])[+[]]
      ```

      **[⬆ Back to Top](#table-of-contents)**

232. ### How do you remove falsy values from an array

      You can apply the filter method on the array by passing Boolean as a parameter. This way it removes all falsy values(0, undefined, null, false and "") from the array.

      ```javascript
      const myArray = [false, null, 1, 5, undefined];
      myArray.filter(Boolean); // [1, 5] // is same as myArray.filter(x => x);
      ```

      **[⬆ Back to Top](#table-of-contents)**

233. ### How do you get unique values of an array

      You can get unique values of an array with the combination of `Set` and rest expression/spread(...) syntax.

      ```javascript
      console.log([...new Set([1, 2, 4, 4, 3])]); // [1, 2, 4, 3]
      ```

      **[⬆ Back to Top](#table-of-contents)**

234. ### How do you map the array values without using map method

      You can map the array values without using the `map` method by just using the `from` method of Array. Let's map city names from Countries array,

      ```javascript
      const countries = [
        { name: "India", capital: "Delhi" },
        { name: "US", capital: "Washington" },
        { name: "Russia", capital: "Moscow" },
        { name: "Singapore", capital: "Singapore" },
        { name: "China", capital: "Beijing" },
        { name: "France", capital: "Paris" },
      ];

      const cityNames = Array.from(countries, ({ capital }) => capital);
      console.log(cityNames); // ['Delhi, 'Washington', 'Moscow', 'Singapore', 'Beijing', 'Paris']
      ```

      **[⬆ Back to Top](#table-of-contents)**

235. ### How do you empty an array

      You can empty an array quickly by setting the array length to zero.

      ```javascript
      let cities = ["Singapore", "Delhi", "London"];
      cities.length = 0; // cities becomes []
      ```

      **[⬆ Back to Top](#table-of-contents)**

236. ### How do you round numbers to certain decimals

      You can round numbers to a certain number of decimals using `toFixed` method from native javascript.

      ```javascript
      let pie = 3.141592653;
      pie = pie.toFixed(3); // 3.142
      ```

      **[⬆ Back to Top](#table-of-contents)**

237. ### What is the easiest way to convert an array to an object

      You can convert an array to an object with the same data using spread(...) operator.

      ```javascript
      var fruits = ["banana", "apple", "orange", "watermelon"];
      var fruitsObject = { ...fruits };
      console.log(fruitsObject); // {0: "banana", 1: "apple", 2: "orange", 3: "watermelon"}
      ```

      **[⬆ Back to Top](#table-of-contents)**

238. ### How do you create an array with some data

      You can create an array with some data or an array with the same values using `fill` method.

      ```javascript
      var newArray = new Array(5).fill("0");
      console.log(newArray); // ["0", "0", "0", "0", "0"]
      ```

      **[⬆ Back to Top](#table-of-contents)**

239. ### What is the purpose of dir method of console object

      The `console.dir()` is used to display an interactive list of the properties of the specified JavaScript object as JSON.

      ```javascript
      const user = { name: "John", id: 1, city: "Delhi" };
      console.dir(user);
      ```

      The user object displayed in JSON representation
      ![Screenshot](images/console-dir.png)

      **[⬆ Back to Top](#table-of-contents)**

240. ### How do you display data in a tabular format using console object

      The `console.table()` is used to display data in the console in a tabular format to visualize complex arrays or objects.

      ```js
      const users = [
        { name: "John", id: 1, city: "Delhi" },
        { name: "Max", id: 2, city: "London" },
        { name: "Rod", id: 3, city: "Paris" },
      ];
      console.table(users);
      ```

      The data visualized in a table format,

      ![Screenshot](images/console-table.png)
      **Not:** Remember that `console.table()` is not supported in IE.

      **[⬆ Back to Top](#table-of-contents)**

241. ### How do you verify that an argument is a Number or not

      The combination of IsNaN and isFinite methods are used to confirm whether an argument is a number or not.

      ```javascript
      function isNumber(n) {
        return !isNaN(parseFloat(n)) && isFinite(n);
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

242. ### What is the shortcut to get timestamp

      You can use `new Date().getTime()` to get the current timestamp. There is an alternative shortcut to get the value.

      ```javascript
      console.log(+new Date());
      console.log(Date.now());
      ```

      **[⬆ Back to Top](#table-of-contents)**

243. ### How do you flattening multi dimensional arrays

      Flattening bi-dimensional arrays is trivial with Spread operator.

      ```javascript
      const biDimensionalArr = [11, [22, 33], [44, 55], [66, 77], 88, 99];
      const flattenArr = [].concat(...biDimensionalArr); // [11, 22, 33, 44, 55, 66, 77, 88, 99]
      ```

      But you can make it work with multi-dimensional arrays by recursive calls,

      ```javascript
      function flattenMultiArray(arr) {
        const flattened = [].concat(...arr);
        return flattened.some((item) => Array.isArray(item))
          ? flattenMultiArray(flattened)
          : flattened;
      }
      const multiDimensionalArr = [
        11,
        [22, 33],
        [44, [55, 66, [77, [88]], 99]],
      ];
      const flatArr = flattenMultiArray(multiDimensionalArr); // [11, 22, 33, 44, 55, 66, 77, 88, 99]
      ```

      Also you can use the `flat` method of Array.

      ```javascript
      const arr = [1, [2, 3], 4, 5, [6, 7]];
      const fllattenArr = arr.flat(); // [1, 2, 3, 4, 5, 6, 7]

      // And for multiDimensional arrays
      const multiDimensionalArr = [
        11,
        [22, 33],
        [44, [55, 66, [77, [88]], 99]],
      ];
      const oneStepFlat = multiDimensionalArr.flat(1); // [11, 22, 33, 44, [55, 66, [77, [88]], 99]]
      const towStep = multiDimensionalArr.flat(2); // [11, 22, 33, 44, 55, 66, [77, [88]], 99]
      const fullyFlatArray = multiDimensionalArr.flat(Infinity); // [11, 22, 33, 44, 55, 66, 77, 88, 99]
      ```

      **[⬆ Back to Top](#table-of-contents)**

244. ### What is the easiest multi condition checking

      You can use `indexOf` to compare input with multiple values instead of checking each value as one condition.

      ```javascript
      // Verbose approach
      if (
        input === "first" ||
        input === 1 ||
        input === "second" ||
        input === 2
      ) {
        someFunction();
      }
      // Shortcut
      if (["first", 1, "second", 2].indexOf(input) !== -1) {
        someFunction();
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

245. ### How do you capture browser back button

      The `beforeunload` event is triggered when the window, the document and its resources are about to be unloaded. This event is helpful to warn users about losing the current data and detect back button event.

      ```javascript
      window.addEventListener("beforeunload", () => {
        console.log("Clicked browser back button");
      });
      ```

      You can also use `popstate` event to detect the browser back button.
      **Note:** The history entry has been activated using `history.pushState` method.

      ```javascript
      window.addEventListener("popstate", () => {
        console.log("Clicked browser back button");
        box.style.backgroundColor = "white";
      });

      const box = document.getElementById("div");

      box.addEventListener("click", () => {
        box.style.backgroundColor = "blue";
        window.history.pushState({}, null, null);
      });
      ```


    In the preceeding code, When the box element clicked, its background color appears in blue color and changed to while color upon clicking the browser back button using `popstate` event handler. The `state` property of `popstate` contains the copy of history entry's state object.

     **[⬆ Back to Top](#table-of-contents)**

246. ### How do you disable right click in the web page

     The right click on the page can be disabled by returning false from the `oncontextmenu` attribute on the body element.

     ```html
     <body oncontextmenu="return false;"></body>
     ```

     **[⬆ Back to Top](#table-of-contents)**

247. ### What are wrapper objects

     Primitive Values like string,number and boolean don't have properties and methods but they are temporarily converted or coerced to an object(Wrapper object) when you try to perform actions on them. For example, if you apply toUpperCase() method on a primitive string value, it does not throw an error but returns uppercase of the string.

     ```javascript
     let name = "john";

     console.log(name.toUpperCase()); // Behind the scenes treated as console.log(new String(name).toUpperCase());
     ```

     i.e, Every primitive except null and undefined have Wrapper Objects and the list of wrapper objects are String,Number,Boolean,Symbol and BigInt.

     **[⬆ Back to Top](#table-of-contents)**

248. ### What are the different ways to deal with Asynchronous Code

     Below are the list of different ways to deal with Asynchronous code.

     1. Callbacks
     2. Promises
     3. Async/await
     4. Third-party libraries such as async.js,bluebird etc

     **[⬆ Back to Top](#table-of-contents)**

249. ### What is web speech API

     Web speech API is used to enable modern browsers recognize and synthesize speech(i.e, voice data into web apps). This API was introduced by W3C Community in the year 2012. It has two main parts:

     1. **SpeechRecognition (Asynchronous Speech Recognition or Speech-to-Text):** It provides the ability to recognize voice context from an audio input and respond accordingly. This is accessed by the `SpeechRecognition` interface.
        The example below shows how to use this API to get text from speech,

     ```javascript
     window.SpeechRecognition =
       window.webkitSpeechRecognition || window.SpeechRecognition; // webkitSpeechRecognition for Chrome and SpeechRecognition for FF
     const recognition = new window.SpeechRecognition();
     recognition.onresult = (event) => {
       // SpeechRecognitionEvent type
       const speechToText = event.results[0][0].transcript;
       console.log(speechToText);
     };
     recognition.start();
     ```

     In this API, browser is going to ask you for permission to use your microphone

     2. **SpeechSynthesis (Text-to-Speech):** It provides the ability to recognize voice context from an audio input and respond. This is accessed by the `SpeechSynthesis` interface.
        For example, the below code is used to get voice/speech from text,

     ```javascript
     if ("speechSynthesis" in window) {
       var speech = new SpeechSynthesisUtterance("Hello World!");
       speech.lang = "en-US";
       window.speechSynthesis.speak(speech);
     }
     ```

     The above examples can be tested on chrome(33+) browser's developer console.
     **Note:** This API is still a working draft and only available in Chrome and Firefox browsers(ofcourse Chrome only implemented the specification)

     **[⬆ Back to Top](#table-of-contents)**

250. ### How do you implement zero timeout in modern browsers

     You can't use setTimeout(fn, 0) to execute the code immediately due to minimum delay of greater than 0ms. But you can use window.postMessage() to achieve this behavior.

     **[⬆ Back to Top](#table-of-contents)**

251. ### What are tasks in event loop

     A task is any javascript code/program which is scheduled to be run by the standard mechanisms such as initially starting to run a program, run an event callback, or an interval or timeout being fired. All these tasks are scheduled on a task queue.
     Below are the list of use cases to add tasks to the task queue,

     1. When a new javascript program is executed directly from console or running by the `<script>` element, the task will be added to the task queue.
     2. When an event fires, the event callback added to task queue
     3. When a setTimeout or setInterval is reached, the corresponding callback added to task queue

     **[⬆ Back to Top](#table-of-contents)**

252. ### What is microtask
     
     A microtask is a type of JavaScript callback that is scheduled to run immediately after the currently executing script and before the next event loop tick. Microtasks are executed after the current task completes and before any new tasks (macrotasks) are run. This ensures a fast and predictable update cycle.

     Common sources of microtasks stored in the microtask queue include:

     1. **Promises:**
        When a Promise is resolved or rejected, its `.then()`, `.catch()`, and `.finally()` callbacks are placed in the microtask queue.

        ```javascript
        Promise.resolve().then(() => {
         console.log('Microtask from a Promise');
        });
        ```

      2. **queueMicrotask():**
     
         A method that explicitly schedules a function to be run in the microtask queue.

         ```javascript
          queueMicrotask(() => {
             console.log('Microtask from  queueMicrotask');
           });
         ```

      3. **MutationObserver callbacks:**

         Observers changes in the DOM and triggers a callback as a microtask.

         ```javascript
            const observer = new MutationObserver(() => {
              console.log('Microtask from MutationObserver');
            })
            observer.observe(document.body, {childList: true});
         ```

      4. **await:**  
         Await internally uses Promises, so the code after `await` is scheduled as a microtask.

         ```javascript
          async function asyncFunction() {
            await null;
            console.log('Microtask from Await'); // Schedule this code as microtask
          }
         ```
     **Note:** All of these microtasks are processed in the same turn of the event loop.

     **[⬆ Back to Top](#table-of-contents)**

253. ### What are the differences between promises and observables

     Some of the major difference in a tabular form

     | Promises                                                           | Observables                                                                              |
     | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------- |
     | Emits only a single value at a time                                | Emits multiple values over a period of time(stream of values ranging from 0 to multiple) |
     | Eager in nature; they are going to be called immediately           | Lazy in nature; they require subscription to be invoked                                  |
     | Promise is always asynchronous even though it resolved immediately | Observable can be either synchronous or asynchronous                                     |
     | Doesn't provide any operators                                      | Provides operators such as map, forEach, filter, reduce, retry, and retryWhen etc        |
     | Cannot be canceled                                                 | Canceled by using unsubscribe() method                                                   |

     **[⬆ Back to Top](#table-of-contents)**

254. ### What is an event table

     Event Table is a data structure that stores and keeps track of all the events which will be executed asynchronously like after some time interval or after the resolution of some API requests. i.e Whenever you call a setTimeout function or invoke async operation, it is added to the Event Table.
     It doesn't not execute functions on it’s own. The main purpose of the event table is to keep track of events and send them to the Event Queue as shown in the below diagram.

     ![Screenshot](images/event-table.png)

     **[⬆ Back to Top](#table-of-contents)**

255. ### What is a microTask queue

     Microtask Queue is the new queue where all the tasks initiated by promise objects get processed before the callback queue.
     The microtasks queue are processed before the next rendering and painting jobs. But if these microtasks are running for a long time then it leads to visual degradation.

     **[⬆ Back to Top](#table-of-contents)**

256. ### How do you detect primitive or non primitive value type

     In JavaScript, primitive types include boolean, string, number, BigInt, null, Symbol and undefined. Whereas non-primitive types include the Objects. But you can easily identify them with the below function,

     ```javascript
     var myPrimitive = 30;
     var myNonPrimitive = {};
     function isPrimitive(val) {
       return Object(val) !== val;
     }

     isPrimitive(myPrimitive);
     isPrimitive(myNonPrimitive);
     ```

     If the value is a primitive data type, the Object constructor creates a new wrapper object for the value. But If the value is a non-primitive data type (an object), the Object constructor will give the same object.

     **[⬆ Back to Top](#table-of-contents)**

257. ### Is Node.js completely single threaded

     Node is a single thread, but some of the functions included in the Node.js standard library(e.g, fs module functions) are not single threaded. i.e, Their logic runs outside of the Node.js single thread to improve the speed and performance of a program.

     **[⬆ Back to Top](#table-of-contents)**

258. ### What is RxJS

     RxJS (Reactive Extensions for JavaScript) is a library for implementing reactive programming using observables that makes it easier to compose asynchronous or callback-based code. It also provides utility functions for creating and working with observables.

     **[⬆ Back to Top](#table-of-contents)**

259. ### What is the difference between Function constructor and function declaration

     The functions which are created with `Function constructor` do not create closures to their creation contexts but they are always created in the global scope. i.e, the function can access its own local variables and global scope variables only. Whereas function declarations can access outer function variables(closures) too.

     Let's see this difference with an example,

     **Function Constructor:**

     ```javascript
     var a = 100;
     function createFunction() {
       var a = 200;
       return new Function("return a;");
     }
     console.log(createFunction()()); // 100
     ```

     **Function declaration:**

     ```javascript
     var a = 100;
     function createFunction() {
       var a = 200;
       return function func() {
         return a;
       };
     }
     console.log(createFunction()()); // 200
     ```

     **[⬆ Back to Top](#table-of-contents)**

260. ### What is a Short circuit condition

     Short circuit conditions are meant for condensed way of writing simple if statements. Let's demonstrate the scenario using an example. If you would like to login to a portal with an authentication condition, the expression would be as below,

     ```javascript
     if (authenticate) {
       loginToPorta();
     }
     ```

     Since the javascript logical operators evaluated from left to right, the above expression can be simplified using && logical operator

     ```javascript
     authenticate && loginToPorta();
     ```

     **[⬆ Back to Top](#table-of-contents)**

261. ### What is the easiest way to resize an array

     The length property of an array is useful to resize or empty an array quickly. Let's apply length property on number array to resize the number of elements from 5 to 2,

     ```javascript
     var array = [1, 2, 3, 4, 5];
     console.log(array.length); // 5

     array.length = 2;
     console.log(array.length); // 2
     console.log(array); // [1,2]
     ```

     and the array can be emptied too

     ```javascript
     var array = [1, 2, 3, 4, 5];
     array.length = 0;
     console.log(array.length); // 0
     console.log(array); // []
     ```

     **[⬆ Back to Top](#table-of-contents)**

262. ### What is an observable

     An Observable is basically a function that can return a stream of values either synchronously or asynchronously to an observer over time. The consumer can get the value by calling `subscribe()` method.
     Let's look at a simple example of an Observable

     ```javascript
     import { Observable } from "rxjs";

     const observable = new Observable((observer) => {
       setTimeout(() => {
         observer.next("Message from a Observable!");
       }, 3000);
     });

     observable.subscribe((value) => console.log(value));
     ```

     ![Screenshot](images/observables.png)

     **Note:** Observables are not part of the JavaScript language yet but they are being proposed to be added to the language

     **[⬆ Back to Top](#table-of-contents)**

263. ### What is the difference between function and class declarations

     The main difference between function declarations and class declarations is `hoisting`. The function declarations are hoisted but not class declarations.

     **Classes:**

     ```javascript
     const user = new User(); // ReferenceError

     class User {}
     ```

     **Constructor Function:**

     ```javascript
     const user = new User(); // No error

     function User() {}
     ```

     **[⬆ Back to Top](#table-of-contents)**

264. ### How do you prevent promises swallowing errors

     While using asynchronous code, JavaScript’s ES6 promises can make your life a lot easier without having callback pyramids and error handling on every second line. But Promises have some pitfalls and the biggest one is swallowing errors by default.

     Let's say you expect to print an error to the console for all the below cases,

     ```javascript
     Promise.resolve("promised value").then(function () {
       throw new Error("error");
     });

     Promise.reject("error value").catch(function () {
       throw new Error("error");
     });

     new Promise(function (resolve, reject) {
       throw new Error("error");
     });
     ```

     But there are many modern JavaScript environments that won't print any errors. You can fix this problem in different ways,

     1. **Add catch block at the end of each chain:** You can add catch block to the end of each of your promise chains

        ```javascript
        Promise.resolve("promised value")
          .then(function () {
            throw new Error("error");
          })
          .catch(function (error) {
            console.error(error.stack);
          });
        ```

        But it is quite difficult to type for each promise chain and verbose too.

     2. **Add done method:** You can replace first solution's then and catch blocks with done method

        ```javascript
        Promise.resolve("promised value").done(function () {
          throw new Error("error");
        });
        ```

        Let's say you want to fetch data using HTTP and later perform processing on the resulting data asynchronously. You can write `done` block as below,

        ```javascript
        getDataFromHttp()
          .then(function (result) {
            return processDataAsync(result);
          })
          .done(function (processed) {
            displayData(processed);
          });
        ```

        In future, if the processing library API changed to synchronous then you can remove `done` block as below,

        ```javascript
        getDataFromHttp().then(function (result) {
          return displayData(processDataAsync(result));
        });
        ```

        and then you forgot to add `done` block to `then` block leads to silent errors.

     3. **Extend ES6 Promises by Bluebird:**
        Bluebird extends the ES6 Promises API to avoid the issue in the second solution. This library has a “default” onRejection handler which will print all errors from rejected Promises to stderr. After installation, you can process unhandled rejections

        ```javascript
        Promise.onPossiblyUnhandledRejection(function (error) {
          throw error;
        });
        ```

        and discard a rejection, just handle it with an empty catch

        ```javascript
        Promise.reject("error value").catch(function () {});
        ```

     **[⬆ Back to Top](#table-of-contents)**

265. ### What is deno

     Deno is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 JavaScript engine and the Rust programming language. It solves the inherent problems of Node.Js and has been officially released in May 2018. Unlike Node.JS, by default Deno executes the code in a sandbox, which means that runtime has no access to below areas:

     1. The file system
     2. The network
     3. Execution of other scripts
     4. The environment variables

     **[⬆ Back to Top](#table-of-contents)**

266. ### How do you make an object iterable in javascript

     By default, plain objects are not iterable. But you can make the object iterable by defining a `Symbol.iterator` property on it.

     Let's demonstrate this with an example,

     ```javascript
     const collection = {
       one: 1,
       two: 2,
       three: 3,
       [Symbol.iterator]() {
         const values = Object.keys(this);
         let i = 0;
         return {
           next: () => {
             return {
               value: this[values[i++]],
               done: i > values.length,
             };
           },
         };
       },
     };

     const iterator = collection[Symbol.iterator]();

     console.log(iterator.next()); // → {value: 1, done: false}
     console.log(iterator.next()); // → {value: 2, done: false}
     console.log(iterator.next()); // → {value: 3, done: false}
     console.log(iterator.next()); // → {value: undefined, done: true}
     ```

     The above process can be simplified using a generator function,

     ```javascript
     const collection = {
       one: 1,
       two: 2,
       three: 3,
       [Symbol.iterator]: function* () {
         for (let key in this) {
           yield this[key];
         }
       },
     };
     const iterator = collection[Symbol.iterator]();
     console.log(iterator.next()); // {value: 1, done: false}
     console.log(iterator.next()); // {value: 2, done: false}
     console.log(iterator.next()); // {value: 3, done: false}
     console.log(iterator.next()); // {value: undefined, done: true}
     ```

     **[⬆ Back to Top](#table-of-contents)**

267. ### What is a Proper Tail Call

     First, we should know about tail call before talking about "Proper Tail Call". A tail call is a subroutine or function call performed as the final action of a calling function. Whereas **Proper tail call(PTC)** is a technique where the program or code will not create additional stack frames for a recursion when the function call is a tail call.

     For example, the below classic or head recursion of factorial function relies on stack for each step. Each step need to be processed upto `n * factorial(n - 1)`

     ```javascript
     function factorial(n) {
       if (n === 0) {
         return 1;
       }
       return n * factorial(n - 1);
     }
     console.log(factorial(5)); //120
     ```

     But if you use Tail recursion functions, they keep passing all the necessary data it needs down the recursion without relying on the stack.

     ```javascript
     function factorial(n, acc = 1) {
       if (n === 0) {
         return acc;
       }
       return factorial(n - 1, n * acc);
     }
     console.log(factorial(5)); //120
     ```

     The above pattern returns the same output as the first one. But the accumulator keeps track of total as an argument without using stack memory on recursive calls.

     **[⬆ Back to Top](#table-of-contents)**

268. ### How do you check an object is a promise or not

     If you don't know if a value is a promise or not, wrapping the value as `Promise.resolve(value)` which returns a promise

     ```javascript
     function isPromise(object) {
       if (Promise && Promise.resolve) {
         return Promise.resolve(object) == object;
       } else {
         throw "Promise not supported in your environment";
       }
     }

     var i = 1;
     var promise = new Promise(function (resolve, reject) {
       resolve();
     });

     console.log(isPromise(i)); // false
     console.log(isPromise(promise)); // true
     ```

     Another way is to check for `.then()` handler type

     ```javascript
     function isPromise(value) {
       return Boolean(value && typeof value.then === "function");
     }
     var i = 1;
     var promise = new Promise(function (resolve, reject) {
       resolve();
     });

     console.log(isPromise(i)); // false
     console.log(isPromise(promise)); // true
     ```

     **[⬆ Back to Top](#table-of-contents)**

269. ### How to detect if a function is called as constructor

     You can use `new.target` pseudo-property to detect whether a function was called as a constructor(using the new operator) or as a regular function call.

     1. If a constructor or function invoked using the new operator, new.target returns a reference to the constructor or function.
     2. For function calls, new.target is undefined.

     ```javascript
     function Myfunc() {
       if (new.target) {
         console.log("called with new");
       } else {
         console.log("not called with new");
       }
     }

     new Myfunc(); // called with new
     Myfunc(); // not called with new
     Myfunc.call({}); // not called with new
     ```

     **[⬆ Back to Top](#table-of-contents)**

270. ### What are the differences between arguments object and rest parameter

     There are three main differences between arguments object and rest parameters

     1. The arguments object is an array-like but not an array. Whereas the rest parameters are array instances.
     2. The arguments object does not support methods such as sort, map, forEach, or pop. Whereas these methods can be used in rest parameters.
     3. The rest parameters are only the ones that haven’t been given a separate name, while the arguments object contains all arguments passed to the function

     **[⬆ Back to Top](#table-of-contents)**

271. ### What are the differences between spread operator and rest parameter

     Rest parameter collects all remaining elements into an array. Whereas Spread operator allows iterables( arrays / objects / strings ) to be expanded into single arguments/elements. i.e, Rest parameter is opposite to the spread operator.

     **[⬆ Back to Top](#table-of-contents)**

272. ### What are the different kinds of generators

     There are five kinds of generators,

     1. **Generator function declaration:**

        ```javascript
        function* myGenFunc() {
          yield 1;
          yield 2;
          yield 3;
        }
        const genObj = myGenFunc();
        ```

     2. **Generator function expressions:**

        ```javascript
        const myGenFunc = function* () {
          yield 1;
          yield 2;
          yield 3;
        };
        const genObj = myGenFunc();
        ```

     3. **Generator method definitions in object literals:**

        ```javascript
        const myObj = {
          *myGeneratorMethod() {
            yield 1;
            yield 2;
            yield 3;
          },
        };
        const genObj = myObj.myGeneratorMethod();
        ```

     4. **Generator method definitions in class:**

        ```javascript
        class MyClass {
          *myGeneratorMethod() {
            yield 1;
            yield 2;
            yield 3;
          }
        }
        const myObject = new MyClass();
        const genObj = myObject.myGeneratorMethod();
        ```

     5. **Generator as a computed property:**

        ```javascript
        const SomeObj = {
          *[Symbol.iterator]() {
            yield 1;
            yield 2;
            yield 3;
          },
        };

        console.log(Array.from(SomeObj)); // [ 1, 2, 3 ]
        ```

     **[⬆ Back to Top](#table-of-contents)**

273. ### What are the differences between for...of and for...in statements

     Both for...in and for...of statements iterate over js data structures. The only difference is over what they iterate:

     1. for..in iterates over all enumerable property keys of an object
     2. for..of iterates over the values of an iterable object.

     Let's explain this difference with an example,

     ```javascript
     let arr = ["a", "b", "c"];

     arr.newProp = "newVlue";

     // key are the property keys
     for (let key in arr) {
       console.log(key); // 0, 1, 2 & newProp
     }

     // value are the property values
     for (let value of arr) {
       console.log(value); // a, b, c
     }
     ```

     Since for..in loop iterates over the keys of the object, the first loop logs 0, 1, 2 and newProp while iterating over the array object. The for..of loop iterates over the values of a arr data structure and logs a, b, c in the console.

     **[⬆ Back to Top](#table-of-contents)**

274. ### How do you define instance and non-instance properties

     The Instance properties must be defined inside of class methods. For example, name and age properties defined inside constructor as below,

     ```javascript
     class Person {
       constructor(name, age) {
         this.name = name;
         this.age = age;
       }
     }
     ```

     But Static(class) and prototype data properties must be defined outside of the ClassBody declaration. Let's assign the age value for Person class as below,

     ```javascript
     Person.staticAge = 30;
     Person.prototype.prototypeAge = 40;
     ```

     **[⬆ Back to Top](#table-of-contents)**

275. ### What is the difference between isNaN and Number.isNaN?

     1. **isNaN**: The global function `isNaN` converts the argument to a Number and returns true if the resulting value is NaN.
     2. **Number.isNaN**: This method does not convert the argument. But it returns true when the type is a Number and value is NaN.

     Let's see the difference with an example,

     ```javascript
     isNaN(‘hello’);   // true
     Number.isNaN('hello'); // false
     ```

     **[⬆ Back to Top](#table-of-contents)**

276. ### How to invoke an IIFE without any extra brackets?

     Immediately Invoked Function Expressions(IIFE) requires a pair of parenthesis to wrap the function which contains set of statements.

     ```js
     (function (dt) {
       console.log(dt.toLocaleTimeString());
     })(new Date());
     ```

     Since both IIFE and void operator discard the result of an expression, you can avoid the extra brackets using `void operator` for IIFE as below,

     ```js
     void (function (dt) {
       console.log(dt.toLocaleTimeString());
     })(new Date());
     ```

     **[⬆ Back to Top](#table-of-contents)**

277. ### Is that possible to use expressions in switch cases?

     You might have seen expressions used in switch condition but it is also possible to use for switch cases by assigning true value for the switch condition. Let's see the weather condition based on temperature as an example,

     ```js
     const weather = (function getWeather(temp) {
       switch (true) {
         case temp < 0:
           return "freezing";
         case temp < 10:
           return "cold";
         case temp < 24:
           return "cool";
         default:
           return "unknown";
       }
     })(10);
     ```

     **[⬆ Back to Top](#table-of-contents)**

278. ### What is the easiest way to ignore promise errors?

     The easiest and safest way to ignore promise errors is void that error. This approach is ESLint friendly too.

     ```js
     await promise.catch((e) => void e);
     ```

     **[⬆ Back to Top](#table-of-contents)**

279. ### What is nullish coalescing operator (??)?

     It is a logical operator that returns its right-hand side operand when its left-hand side operand is null or undefined, and otherwise returns its left-hand side operand. This can be contrasted with the logical OR (||) operator, which returns the right-hand side operand if the left operand is any falsy value, not only null or undefined.

     ```js
     console.log(null ?? true); // true
     console.log(false ?? true); // false
     console.log(undefined ?? true); // true
     ```

     **[⬆ Back to Top](#table-of-contents)**

280. ### How do you group and nest console output?

     The `console.group()` can be used to group related log messages to be able to easily read the logs and use console.groupEnd()to close the group. Along with this, you can also nest groups which allows to output message in hierarchical manner.

     For example, if you’re logging a user’s details:

     ```js
     console.group("User Details");
     console.log("name: Sudheer Jonna");
     console.log("job: Software Developer");

     // Nested Group
     console.group("Address");
     console.log("Street: Commonwealth");
     console.log("City: Los Angeles");
     console.log("State: California");

     // Close nested group
     console.groupEnd();

     // Close outer group
     console.groupEnd();
     ```

     You can also use `console.groupCollapsed()` instead of `console.group()` if you want the groups to be collapsed by default.

     **[⬆ Back to Top](#table-of-contents)**

281. ### What is the difference between dense and sparse arrays?

     An array contains items at each index starting from first(0) to last(array.length - 1) is called as Dense array. Whereas if at least one item is missing at any index, the array is called as sparse.

     Let's see the below two kind of arrays,

     ```js
     const avengers = ["Ironman", "Hulk", "CaptainAmerica"];
     console.log(avengers[0]); // 'Ironman'
     console.log(avengers[1]); // 'Hulk'
     console.log(avengers[2]); // 'CaptainAmerica'
     console.log(avengers.length); // 3

     const justiceLeague = ["Superman", "Aquaman", , "Batman"];
     console.log(justiceLeague[0]); // 'Superman'
     console.log(justiceLeague[1]); // 'Aquaman'
     console.log(justiceLeague[2]); // undefined
     console.log(justiceLeague[3]); // 'Batman'
     console.log(justiceLeague.length); // 4
     ```

     **[⬆ Back to Top](#table-of-contents)**

282. ### What are the different ways to create sparse arrays?

     There are 4 different ways to create sparse arrays in JavaScript

     1. **Array literal:** Omit a value when using the array literal
        ```js
        const justiceLeague = ["Superman", "Aquaman", , "Batman"];
        console.log(justiceLeague); // ['Superman', 'Aquaman', empty ,'Batman']
        ```
     2. **Array() constructor:** Invoking Array(length) or new Array(length)
        ```js
        const array = Array(3);
        console.log(array); // [empty, empty ,empty]
        ```
     3. **Delete operator:** Using delete array[index] operator on the array
        ```js
        const justiceLeague = ["Superman", "Aquaman", "Batman"];
        delete justiceLeague[1];
        console.log(justiceLeague); // ['Superman', empty, ,'Batman']
        ```
     4. **Increase length property:** Increasing length property of an array
        ```js
        const justiceLeague = ["Superman", "Aquaman", "Batman"];
        justiceLeague.length = 5;
        console.log(justiceLeague); // ['Superman', 'Aquaman', 'Batman', empty, empty]
        ```

     **[⬆ Back to Top](#table-of-contents)**

283. ### What is the difference between setTimeout, setImmediate and process.nextTick?

     1. **Set Timeout:** setTimeout() is to schedule execution of a one-time callback after delay milliseconds.
     2. **Set Immediate:** The setImmediate function is used to execute a function right after the current event loop finishes.
     3. **Process NextTick:** If process.nextTick() is called in a given phase, all the callbacks passed to process.nextTick() will be resolved before the event loop continues. This will block the event loop and create I/O Starvation if process.nextTick() is called recursively.

     **[⬆ Back to Top](#table-of-contents)**

284. ### How do you reverse an array without modifying original array?

     The `reverse()` method reverses the order of the elements in an array but it mutates the original array. Let's take a simple example to demonistrate this case,

     ```javascript
     const originalArray = [1, 2, 3, 4, 5];
     const newArray = originalArray.reverse();

     console.log(newArray); // [ 5, 4, 3, 2, 1]
     console.log(originalArray); // [ 5, 4, 3, 2, 1]
     ```

     There are few solutions that won't mutate the original array. Let's take a look.

     1. **Using slice and reverse methods:**
        In this case, just invoke the `slice()` method on the array to create a shallow copy followed by `reverse()` method call on the copy.

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = originalArray.slice().reverse(); //Slice an array gives a new copy

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     2. **Using spread and reverse methods:**
        In this case, let's use the spread syntax (...) to create a copy of the array followed by `reverse()` method call on the copy.

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = [...originalArray].reverse();

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     3. **Using reduce and spread methods:**
        Here execute a reducer function on an array elements and append the accumulated array on right side using spread syntax

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = originalArray.reduce((accumulator, value) => {
          return [value, ...accumulator];
        }, []);

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     4. **Using reduceRight and spread methods:**
        Here execute a right reducer function(i.e. opposite direction of reduce method) on an array elements and append the accumulated array on left side using spread syntax

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = originalArray.reduceRight((accumulator, value) => {
          return [...accumulator, value];
        }, []);

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     5. **Using reduceRight and push methods:**
        Here execute a right reducer function(i.e. opposite direction of reduce method) on an array elements and push the iterated value to the accumulator

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = originalArray.reduceRight((accumulator, value) => {
          accumulator.push(value);
          return accumulator;
        }, []);

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     **[⬆ Back to Top](#table-of-contents)**

285. ### How do you create custom HTML element?

     The creation of custom HTML elements involves two main steps,

     1. **Define your custom HTML element:** First you need to define some custom class by extending HTMLElement class.
        After that define your component properties (styles,text etc) using `connectedCallback` method.
        **Note:** The browser exposes a function called `customElements.define` inorder to reuse the element.
        ```javascript
        class CustomElement extends HTMLElement {
          connectedCallback() {
            this.innerHTML = "This is a custom element";
          }
        }
        customElements.define("custom-element", CustomElement);
        ```
     2. **Use custom element just like other HTML element:** Declare your custom element as a HTML tag.

     ```javascript
        <body>
             <custom-element>
        </body>
     ```

     **[⬆ Back to Top](#table-of-contents)**

286. ### What is function execution context?

     Whenever a function is invoked, the JavaScript engine creates a different type of Execution Context known as a Function Execution Context (FEC) within the Global Execution Context (GEC) to evaluate and execute the code within that function.

     **[⬆ Back to Top](#table-of-contents)**

287. ### What is debouncing?

    Debouncing is a programming technique used to limit how often a function is executed. Specifically, it ensures that a function is only triggered after a certain amount of time has passed since it was last invoked. This prevents unnecessary or excessive function calls, which can help optimize performance and reduce unnecessary CPU usage or API requests.

    For example, when a user types in a search box, you typically want to wait until they’ve finished typing before fetching suggestions. Without debouncing, an API call would be triggered on every keystroke, potentially causing performance issues. With debouncing, the function call is postponed until the user stops typing for a specified period (e.g., 300ms). If the user types again before this time elapses, the timer resets.

    **Typical use cases for debouncing include:**

    *   Search box suggestions (wait until typing pauses before fetching results)
    *   Auto-saving text fields (save only after the user stops typing)
    *   Preventing double-clicks on buttons
    *   Handling window resize or scroll events efficiently

    **Example Debounce Function:**

    JavaScript

    ```css
    function debounce(func, timeout = 500) {
      let timer;
      return function (...args) {
        clearTimeout(timer);
        timer = setTimeout(() => {
          func.apply(this, args);
        }, timeout);
      };
    }
    ```

    **Usage Example:**

    JavaScript

    ```css
    function fetchResults() {
      console.log("Fetching input suggestions");
    }
    const processChange = debounce(fetchResults, 300);

    // Attach to input element
    <input type="text" onkeyup="processChange()" />

    // Attach to button
    <button onclick="processChange()">Click me</button>

    // Attach to window event
    window.addEventListener("scroll", processChange);
    ```

    **How it works:**  
    When `processChange` is invoked (e.g., by typing or clicking), any pending execution is canceled, and the function is scheduled to run after the specified delay. If another event occurs before the delay is up, the timer resets, and the function will only run after events have stopped for the delay duration.

    Debouncing is an essential tool for improving user experience and application performance, especially when dealing with events that can fire rapidly and repeatedly.

 **[⬆ Back to Top](#table-of-contents)**

288. ### What is throttling?
      Throttling is a programming technique used to control the rate at which a function is executed. When an event is triggered continuously—such as during window resizing, scrolling, or mouse movement—throttling ensures that the associated event handler is not called more often than a specified interval. This helps improve performance by reducing the number of expensive function calls and preventing performance bottlenecks.

      **Common use cases:**

      *   Window resize events
      *   Scroll events
      *   Mouse movement or drag events
      *   API rate limiting

      **How does throttling work?**  
      Throttling will execute the function at most once every specified time interval, ignoring additional calls until the interval has passed.

      **Example: Throttle Implementation and Usage**

      JavaScript

      ```css
      // Simple throttle function: allows 'func' to run at most once every 'limit' ms
      function throttle(func, limit) {
        let inThrottle = false;
        return function(...args) {
          if (!inThrottle) {
            func.apply(this, args);
            inThrottle = true;
            setTimeout(() => (inThrottle = false), limit);
          }
        };
      }

      // Usage: throttling a scroll event handler
      function handleScrollAnimation() {
        console.log('Scroll event triggered');
      }

      window.addEventListener(
        "scroll",
        throttle(handleScrollAnimation, 100) // Will run at most once every 100ms
      );
      ```
     **[⬆ Back to Top](#table-of-contents)**

289. ### What is optional chaining?

     According to MDN official docs, the optional chaining operator (?.) permits reading the value of a property located deep within a chain of connected objects without having to expressly validate that each reference in the chain is valid.

     The ?. operator is like the . chaining operator, except that instead of causing an error if a reference is nullish (null or undefined), the expression short-circuits with a return value of undefined. When used with function calls, it returns undefined if the given function does not exist.

     ```js
     const adventurer = {
       name: "Alice",
       cat: {
         name: "Dinah",
       },
     };

     const dogName = adventurer.dog?.name;
     console.log(dogName);
     // expected output: undefined

     console.log(adventurer.someNonExistentMethod?.());
     // expected output: undefined
     ```

     **[⬆ Back to Top](#table-of-contents)**

290. ### What are the differences between primitives and non-primitives?

     JavaScript language has both primitives and non-primitives but there are few differences between them as below,

     | Primitives                 | Non-primitives       |
     | -------------------------- | -------------------- |
     | These types are predefined | Created by developer |
     | These are immutable        | Mutable              |
     | Compare by value           | Compare by reference |
     | Stored in Stack            | Stored in heap       |
     | Contain certain value      | Can contain NULL too |

     **[⬆ Back to Top](#table-of-contents)**

291. ### How do you create your own bind method using either call or apply method?

     The custom bind function needs to be created on Function prototype inorder to use it as other builtin functions. This custom function should return a function similar to original bind method and the implementation of inner function needs to use apply method call.

     The function which is going to bind using custom `myOwnBind` method act as the attached function(`boundTargetFunction`) and argument as the object for `apply` method call.

     ```js
     Function.prototype.myOwnBind = function (whoIsCallingMe) {
       if (typeof this !== "function") {
         throw new Error(this + "cannot be bound as it's not callable");
       }
       const boundTargetFunction = this;
       return function () {
         boundTargetFunction.apply(whoIsCallingMe, arguments);
       };
     };
     ```

     **[⬆ Back to Top](#table-of-contents)**

292. ### What are the differences between pure and impure functions?

     Some of the major differences between pure and impure function are as below,

| Pure function                       | Impure function                                                        |
| ----------------------------------- | ---------------------------------------------------------------------- |
| It has no side effects              | It causes side effects                                                 |
| It is always return the same result | It returns different result on each call                               |
| Easy to read and debug              | Difficult to read and debug because they are affected by external code |

**[⬆ Back to Top](#table-of-contents)**

293. ### What is referential transparency?

An expression in javascript that can be replaced by its value without affecting the behaviour of the program is called referential transparency. Pure functions are referentially transparent.

```javascript
const add = (x, y) => x + y;
const multiplyBy2 = (x) => x * 2;

//Now add (2, 3) can be replaced by 5.

multiplyBy2(add(2, 3));
```

**[⬆ Back to Top](#table-of-contents)**

294. ### What are compose and pipe functions?

     The "compose" and "pipe" are two techniques commonly used in functional programming to simplify complex operations and make code more readable. They are not native to JavaScript and higher-order functions. the `compose()` applies right to left any number of functions to the output of the previous function.

     **[⬆ Back to Top](#table-of-contents)**

295. ### What is module pattern?

     Module pattern is a designed pattern used to wrap a set of variables and functions together in a single scope returned as an object. JavaScript doesn't have access specifiers similar to other languages(Java, Python, etc) to provide private scope. It uses IIFE (Immediately invoked function expression) to allow for private scopes. i.e., a closure that protect variables and methods.

     The module pattern looks like below,

     ```javascript
     (function () {
       // Private variables or functions goes here.

       return {
         // Return public variables or functions here.
       };
     })();
     ```

     Let's see an example of a module pattern for an employee with private and public access,

     ```javascript
     const createEmployee = (function () {
       // Private
       const name = "John";
       const department = "Sales";
       const getEmployeeName = () => name;
       const getDepartmentName = () => department;

       // Public
       return {
         name,
         department,
         getName: () => getEmployeeName(),
         getDepartment: () => getDepartmentName(),
       };
     })();

     console.log(createEmployee.name);
     console.log(createEmployee.department);
     console.log(createEmployee.getName());
     console.log(createEmployee.getDepartment());
     ```

     **Note:** It mimic the concepts of classes with private variables and methods.

     **[⬆ Back to Top](#table-of-contents)**

296. ### What is Function Composition?

     It is an approach where the result of one function is passed on to the next function, which is passed to another until the final function is executed for the final result.

     ```javascript
     //example
     const double = (x) => x * 2;
     const square = (x) => x * x;

     var output1 = double(2);
     var output2 = square(output1);
     console.log(output2);

     var output_final = square(double(2));
     console.log(output_final);
     ```

     **[⬆ Back to Top](#table-of-contents)**

297. ### How to use await outside of async function prior to ES2022?

     Prior to ES2022, if you attempted to use an await outside of an async function resulted in a SyntaxError.

     ```javascript
     await Promise.resolve(console.log("Hello await")); // SyntaxError: await is only valid in async function
     ```

     But you can fix this issue with an alternative IIFE (Immediately Invoked Function Expression) to get access to the feature.

     ```javascript
     (async function () {
       await Promise.resolve(console.log("Hello await")); // Hello await
     })();
     ```

     In ES2022, you can write top-level await without writing any hacks.

     ```javascript
     await Promise.resolve(console.log("Hello await")); //Hello await
     ```

**[⬆ Back to Top](#table-of-contents)**

298. ### What are the uses of closures?
     Closures are a powerful feature in programming languages like JavaScript. They allow functions to retain access to variables from their containing (enclosing) scope even after the outer function has finished executing. This means that a function defined within another function can access variables from the outer function, even if the outer function has already returned.
     Here are some common use cases of closures:

- Data Privacy: Closures can be used to create private variables and methods. By defining variables within a function's scope and returning inner functions that have access to those variables, you can create a form of encapsulation, limiting access to certain data or functionality.

- Function Factories: Closures are often used to create functions with pre-set parameters. This is useful when you need to create multiple functions with similar behavior but different configurations.

- Callback Functions: Closures are frequently used in asynchronous programming, such as handling event listeners or AJAX requests. The inner function captures variables from the outer scope and can access them when the callback is invoked.

- Memoization: Closures can be used for memoization, a technique to optimize performance by caching the results of expensive function calls. The inner function can remember the results of previous calls and return the cached result if the same input is provided again.

- iterators and Generators: Closures can be used to create iterators and generators, which are essential for working with collections of data in modern JavaScript.

**[⬆ Back to Top](#table-of-contents)**

299. ### What are the optimization techniques of V8 engine?

     V8 engine uses the below optimization techniques.

     1. **Inline expansion:** It is a compiler optimization by replacing the function calls with the corresponding function blocks.
     2. **Copy elision:** This is a compiler optimization method to prevent expensive extra objects from being duplicated or copied.
     3. **Inline caching:** It is a runtime optimization technique where it caches the execution of older tasks those can be lookup while executing the same task in the future.

     **[⬆ Back to Top](#table-of-contents)**

300. ### What are the benefits higher order functions?
     The main benefits of higher order functions are:
     1. Abstraction
     2. Reusability
     3. Immutability
     4. Modularity

**[⬆ Back to Top](#table-of-contents)**

301. ### How do you create polyfills for map, filter and reduce methods?

The polyfills for array methods such as map, filter and reduce methods can be created using array prototype.

1.  **map:**

    The built-in `Array.map` method syntax will be helpful to write polyfill. The map method takes the callback function as an argument and that callback function can have below three arguments passed into it.

    i. Current value
    ii. Index of current value(optional)
    iii. array(optional)

    The syntax would like below,

    ```js
    let newArray = arr.map(callback(currentValue[, index, arr) {
       // return new array after executing the code
    })
    ```

    Let's build our map polyfill based on the above syntax,

    ```js
    Array.prototype.myMap = function (cb) {
      let newArr = [];
      for (let i = 0; i < this.length; i++) {
        newArr.push(cb(this[i], i, this));
      }
      return newArr;
    };

    const nums = [1, 2, 3, 4, 5];
    const multiplyByTwo = nums.myMap((x) => x * 2);
    console.log(multiplyByTwo); // [2, 4, 6, 8, 10]
    ```

    In the above code, custom method name 'myMap' has been used to avoid conflicts with built-in method.

2.  **filter:**
    Similar to map method, `Array.filter` method takes callback function as an argument and the callback function can have three agurguments passed into it.

        i. Current value
        ii. Index of current value(optional)
        iii. array(optional)

    The syntax looks like below,

    ```js
    let newArray = arr.filter(callback(currentValue[, index, arr) {
      // return new array whose elements satisfy the callback conditions
    })
    ```

    Let's build our filter polyfill based on the above syntax,

    ```js
    Array.prototype.myFilter = function (cb) {
      let newArr = [];
      for (let i = 0; i < this.length; i++) {
        if (cb(this[i], i, this)) {
          newArr.push(this[i]);
        }
      }
      return newArr;
    };

    const nums = [1, 2, 3, 4, 5, 6];
    const evenNums = nums.myFilter((x) => x % 2);
    console.log(evenNums); // [2, 4, 6]
    ```

3.  **reduce:**

          The built-in `Array.reduce` method syntax will be helpful to write our own polyfill. The reduce method takes the callback function as first argument and the initial value as second argument.

          The callback function can have four arguments passed into it.
          i. Accumulator
          ii. Current value
          iii. Index of current value(optional)
          iv. array(optional)

        The syntax would like below,

        ```js
        arr.reduce(callback((acc, curr, i, arr) => {}), initValue);
        ```
        Let's build our reduce polyfill based on the above syntax,

        ```js
        Array.prototype.myReduce = function(cb, initialValue) {
            let accumulator = initialValue;
            for(let i=0; i< this.length; i++) {
                accumulator = accumulator ? cb(accumulator, this[i], i, this) : this[i];
            }
            return accumulator;
        }
          const nums = [1, 2, 3, 4, 5, 6];
          const sum = nums.myReduce((acc, curr, i, arr) => {
            return acc += curr
          }, 0);
          console.log(sum); // 21
        ```

    **[⬆ Back to Top](#table-of-contents)**

302. ### What is the difference between map and forEach functions?

    Both map and forEach functions are used to iterate over an arrays but there are some differences in their functionality.

    1. **Returning values:** The `map` method returns a new array with transformed elements whereas `forEach` method returns `undefined` eventhough both of them are doing the same job.

    ```javascript
      const arr = [1, 2, 3, 4, 5];
      arr.map(x => x * x); // [1, 4, 9, 16, 25]
      arr.forEach(x => x * x); //

      The `forEach()` method in JavaScript always returns undefined. This is because forEach() is used to iterate over arrays and perform side effects on each element, rather than returning a `new array or transforming the original array`
    ```

    2. **Chaining methods:** The `map` method is chainable. i.e, It can be attached with `reduce`, `filter`, `sort` and other methods as well. Whereas `forEach` cannot be attached with any other methods because it returns `undefined` value.

    ```javascript
    const arr = [1, 2, 3, 4, 5];
    arr.map((x) => x * x).reduce((total, cur) => total + cur); // 55
    arr.forEach((x) => x * x).reduce((total, cur) => total + cur); //Uncaught TypeError: Cannot read properties of undefine(reading 'reduce')
    ```

    3. **Mutation:** The `map` method doesn't mutate the original array by returning new array. Whereas `forEach` method also doesn't mutate the original array but it's callback is allowed to mutate the original array.

    **Note:** Both these methods existed since ES5 onwards.

**[⬆ Back to Top](#table-of-contents)**

303. ### Give an example of statements affected by automatic semicolon insertion?

     The javascript parser will automatically add a semicolon while parsing the source code. For example, the below common statements affected by Automatic Semicolon Insertion(ASI).

     1. An empty statement
     2. var statement
     3. An expression statement
     4. do-while statement
     5. continue statement
     6. break statement
     7. return statement
     8. throw statement

**[⬆ Back to Top](#table-of-contents)**

304. ### What are hidden classes?

     Since JavaScript is a dynamic programming language, you can add or remove properties and methods from objects on the fly at runtime. This nature of JavaScript increases the dynamic dictionary lookups(because objects implemented as HashTables in memory) for retrieving a property on an object.

     Let's consider the following example to see how the additional properties `age` and `gender` added at runtime.

     ```javascript
     function Person(name) {
       this.name = name;
     }

     var person1 = new Person("John");
     var person2 = new Person("Randy");

     person1.age = 40;
     person1.gender = "Male";

     person2.gender = "Female";
     person2.age = 50;
     ```

     As a result, this behavior leads to lower JavaScript performance compared to the contiguous buffer method used in non-dynamic languages. The V8 engine provided a solution named **hidden classes** to optimize the access time when retrieving a property on an object. This optimization is achieved by sharing hidden classes among objects created in a similar fashion. These hidden classes are attached to each and every object to track its shape.

     When V8 engine sees the constructor function(e.g, Person) is declared, it creates a hidden class (let's say Class01) without any offsets. Once the first property assignment statement (`this.name = name`) is executed, V8 engine will create a new hidden class (let's say Class02), inheriting all properties from the previous hidden class (Class01), and assign the property to offset 0. This process enables compiler to skip dictionary lookup when you try to retrieve the same property(i.e, name). Instead, V8 will directly point to Class02. The same procedure happens when you add new properties to the object.

     For example, adding `age` and `gender` properties to `Person` constructor leads to transition of hidden classes(Class02 -> Class03 -> Class04). If you create a second object(Person2) based on the same Person object, both Class01 and Class02 hidden classes are going to be shared. However, the hidden classes Class03 and Class04 cannot be shared because second object has been modified with a different order of properties assignment.

     Since both the objects(person1 and person2) do not share the hidden classes, now V8 engine cannot use **Inline Caching** technique for the faster access of properties.

**[⬆ Back to Top](#table-of-contents)**

305. ### What is inline caching?

Inline caching is an optimization technique based on the observation that repeated calls to same function tends to occur on same type of objects. The V8 compiler stores a cache of the type of objects that were passed as a parameter in recent method calls. Upon next time when same function is called, compiler can directly search for the type in cache.

Let's consider an example where the compiler stores the shape type in cache for repeated calls in the loop.

```js
let shape = { width: 30, height: 20 }; // Compiler store the type in cache as { width: <int>, height: <int>} after repeated calls

function area(obj) {
  //Calculate area
}
for (let i = 0; i < 100; i++) {
  area(shape);
}
```

After few successful calls of the same area method to its same hidden class, V8 engine omits the hidden class lookup and simply adds the offset of the property to the object pointer itself. As a result, it increases the execution speed.

There are mainly 3 types of inline caching possible:

1. Monomorphic: This is a optimized caching technique in which there can be always same type of objects passed.
2. Polymorphic: This ia slightly optimized caching technique in which limited number of different types of objects can be passed.
3. Megamorphic: It is an unoptimized caching in which any number of different objects can be passed.

**[⬆ Back to Top](#table-of-contents)**

306. ### What is the difference between substring and substr methods?

     Both `substring` and `substr` are used to extract parts of a string, but there are subtle differences between the substring() and substr() methods in terms of **syntax** and **behavior**.

     1. `substring(start, end)`
         - **Parameters:**
             - `start`: The index to start extracting (inclusive).
             - `end`: The index to stop extracting (exclusive).
         - **Behavior:**
             - If `start > end`, it **swaps the arguments**.
             - Negative values are treated as `0`.

         ```javascript
          let str = "Hello World";
          console.log(str.substring(0, 5));   // "Hello"
          console.log(str.substring(5, 0));   // "Hello" (swapped)
          console.log(str.substring(-3, 4));  // "Hell" (negative = 0)
         ```
     2. `substr(start, length)` _(Deprecated)_

         - **Parameters:**
           - `start`: The index to start extracting.
           - `length`: The number of characters to extract.
         - **Behavior:**
           - If `start` is negative, it counts from the **end** of the string.
           - If `length` is omitted, it extracts to the end of the string.

         ```javascript
         let str = "Hello World"; console.log(str.substr(0, 5)); // "Hello" 
         console.log(str.substr(-5, 3)); // "Wor" (starts from 'W')`
         ```
         **Note:** substr() is considered a legacy feature in ECMAScript, so it is best to avoid using it if possible.


**[⬆ Back to Top](#table-of-contents)**

307. ### How to find the number of parameters expected by a function?
     The function's object has a **length** property which tells you how many formal parameters expected by a function. This is a static value defined by the function, not the number of arguments the function is called with(**arguments.length**). The basic usage of length propery is,

```javascript
function multiply(x, y) {
  return x * y;
}

function sum(a, b, c) {
  return a + b + c;
}

console.log(multiply.length); //2
console.log(sum.length); //3
```

But there are few important rules which needs to be noted while using length property.

1. **Default values:** Only the parameters which exists before a default value are considered.
   ```javascript
   function sum(a, b = 2, c = 3) {
     return a + b + c;
   }
   console.log(sum.length); // 1
   ```
2. **Rest params:** The rest parameters are excluded with in length property.
   ```javascript
   function sum(a, b, ...moreArgs) {
     let total = a + b;
     for (const arg of moreArgs) {
       total += arg;
     }
     return total;
   }
   console.log(sum.length); // 2
   ```
3. **Destructuring patterns:** Each destructuring pattern counted as a single parameter.

   ```javascript
   function func([a, b], { x, y }) {
     console.log(a + b, x, y);
   }

   console.log(func.length); // 2
   ```

**Note:** The Function constructor is itself a function object and it has a length property of 1.

**[⬆ Back to Top](#table-of-contents)**

308. ### What are the array mutation methods?
     JavaScript array methods can be categorized into two groups:
1. Mutating methods: These are the methods that directly modify the original array.
1. Non-mutating methods: These methods return a new array without altering the original one.

There are 9 methods in total that mutate the arrays,

1.  **push:** Adds one or more elements to the end of the array and returns the new length.
2.  **pop:** Removes the last element from the array and returns that element.
3.  **unshift:** Adds one or more elements to the beginning of the array and returns the new length..
4.  **shift:** Removes the first element from the array and returns that element.
5.  **splice:** Adds or removes elements from the array at a specific index position.
6.  **sort:** Sorts the elements of the array in-place based on a given sorting criteria.
7.  **reverse:** Reverses the order of elements in the given array.
8.  **fill:** Fills all elements of the array with a specific value.
9.  **copyWithIn:** Copies a sequence of elements within the array to a specified target index in the same array.

**[⬆ Back to Top](#table-of-contents)**

309. ### What is module scope in JavaScript?
     Module scope is a feature introduced with ES6 (ES2015) modules that creates a scope specific to a module file, isolating variables and functions declared within it from the global scope and other modules. Variables and functions declared in a module are private by default and can only be accessed by other modules if they are explicitly exported.

Key characteristics of module scope:

1.  Variables declared in a module are scoped to that module only.
2.  Each module has its own top-level scope
3.  Variables and functions need to be explicitly exported to be used in other modules
4.  The global scope cannot access module variables unless they are explicitly exported and imported
5.  Modules are always executed in strict mode

```javascript
// moduleA.js

// This variable is PRIVATE to moduleA. It's like a tool inside a closed box.
const privateVariable = "I am private";

// This variable is PUBLIC because it's exported. Others can use it when they import moduleA.
export const publicVariable = "I am public";

// PUBLIC function because it's exported. But it can still access privateVariable inside moduleA.
export function publicFunction() {
  console.log(privateVariable); // ✅ This works because we're inside the same module.
  return "Hello from publicFunction!";
}

// moduleB.js

// Importing PUBLIC items from moduleA.
import { publicVariable, publicFunction } from "./moduleA.js";

console.log(publicVariable); // ✅ "I am public" - Works because it's exported.
console.log(publicFunction()); // ✅ "Hello from publicFunction!" - Works as well.

// ❌ This will cause an ERROR because privateVariable was NOT exported from moduleA.
// console.log(privateVariable);   // ❌ ReferenceError: privateVariable is not defined
```

Common use cases and benefits:

- Encapsulation of module-specific code
- Prevention of global scope pollution
- Better code organization and maintenance
- Explicit dependency management
- Protection of private implementation details

**[⬆ Back to Top](#table-of-contents)**

310. ### Why is it important to remove event listeners after use?
     
  In JavaScript, you need to be mindful of removing event listeners to avoid memory leaks — especially in long-lived apps like single-page applications (SPAs) or when working with frameworks/libraries. Eventhough JavaScript has automatic garbage collection, memory leaks can still happen if:

  1. A DOM element is removed, but a listener still references it.
  2. A callback (event listener) holds a reference to a large object or closure that can't be cleaned up.
  3. Global objects like window, document etc retain listeners indefinitely unless manually removed.

  So if you add any event listeners to DOM element, it is a good practice to remove it after its usage as shown below,

  ```javascript
     const button = document.getElementById("btn");

      function handleClick() {
        console.log("Clicked!");
      }

      button.addEventListener("click", handleClick);

      // Always remove when done
      button.removeEventListener("click", handleClick);
  ```

  **[⬆ Back to Top](#table-of-contents)**

<!-- QUESTIONS_END -->

### Coding Exercise

#### 1. What is the output of below code

```javascript
var car = new Vehicle("Honda", "white", "2010", "UK");
console.log(car);

function Vehicle(model, color, year, country) {
  this.model = model;
  this.color = color;
  this.year = year;
  this.country = country;
}
```

- 1: Undefined
- 2: ReferenceError
- 3: null
- 4: {model: "Honda", color: "white", year: "2010", country: "UK"}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

The function declarations are hoisted similar to any variables. So the placement for `Vehicle` function declaration doesn't make any difference.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 2. What is the output of below code

```javascript
function foo() {
  let x = (y = 0);
  x++;
  y++;
  return x;
}

console.log(foo(), typeof x, typeof y);
```

- 1: 1, undefined and undefined
- 2: ReferenceError: X is not defined
- 3: 1, undefined and number
- 4: 1, number and number

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

Of course the return value of `foo()` is 1 due to the increment operator. But the statement `let x = y = 0` declares a local variable x. Whereas y declared as a global variable accidentally. This statement is equivalent to,

```javascript
let x;
window.y = 0;
x = window.y;
```

Since the block scoped variable x is undefined outside of the function, the type will be undefined too. Whereas the global variable `y` is available outside the function, the value is 0 and type is number.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 3. What is the output of below code

```javascript
function main() {
  console.log("A");
  setTimeout(function print() {
    console.log("B");
  }, 0);
  console.log("C");
}
main();
```

- 1: A, B and C
- 2: B, A and C
- 3: A and C
- 4: A, C and B

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

The statements order is based on the event loop mechanism. The order of statements follows the below order,

1. At first, the main function is pushed to the stack.
2. Then the browser pushes the first statement of the main function( i.e, A's console.log) to the stack, executing and popping out immediately.
3. But `setTimeout` statement moved to Browser API to apply the delay for callback.
4. In the meantime, C's console.log added to stack, executed and popped out.
5. The callback of `setTimeout` moved from Browser API to message queue.
6. The `main` function popped out from stack because there are no statements to execute
7. The callback moved from message queue to the stack since the stack is empty.
8. The `console.log` for B is added to the stack and display on the console.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 4. What is the output of below equality check

```javascript
console.log(0.1 + 0.2 === 0.3);
```

- 1: false
- 2: true

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

This is due to the float point math problem. Since the floating point numbers are encoded in binary format, the addition operations on them lead to rounding errors. Hence, the comparison of floating points doesn't give expected results.
You can find more details about the explanation here [0.30000000000000004.com/](https://0.30000000000000004.com/)

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 5. What is the output of below code

```javascript
var y = 1;
if (function f() {}) {
  y += typeof f;
}
console.log(y);
```

- 1: 1function
- 2: 1object
- 3: ReferenceError
- 4: 1undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

The main points in the above code snippets are,

1. You can see function expression instead function declaration inside if statement. So it always returns true.
2. Since it is not declared(or assigned) anywhere, f is undefined and typeof f is undefined too.

In other words, it is same as

```javascript
var y = 1;
if ("foo") {
  y += typeof f;
}
console.log(y);
```

**Note:** It returns 1object for MS Edge browser

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 6. What is the output of below code

```javascript
function foo() {
  return;
  {
    message: "Hello World";
  }
}
console.log(foo());
```

- 1: Hello World
- 2: Object {message: "Hello World"}
- 3: Undefined
- 4: SyntaxError

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

This is a semicolon issue. Normally semicolons are optional in JavaScript. So if there are any statements(in this case, return) missing semicolon, it is automatically inserted immediately. Hence, the function returned as undefined.

Whereas if the opening curly brace is along with the return keyword then the function is going to be returned as expected.

```javascript
function foo() {
  return {
    message: "Hello World",
  };
}
console.log(foo()); // {message: "Hello World"}
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 7. What is the output of below code

```javascript
var myChars = ["a", "b", "c", "d"];
delete myChars[0];
console.log(myChars);
console.log(myChars[0]);
console.log(myChars.length);
```

- 1: [empty, 'b', 'c', 'd'], empty, 3
- 2: [null, 'b', 'c', 'd'], empty, 3
- 3: [empty, 'b', 'c', 'd'], undefined, 4
- 4: [null, 'b', 'c', 'd'], undefined, 4

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

The `delete` operator will delete the object property but it will not reindex the array or change its length. So the number or elements or length of the array won't be changed.
If you try to print myChars then you can observe that it doesn't set an undefined value, rather the property is removed from the array. The newer versions of Chrome use `empty` instead of `undefined` to make the difference a bit clearer.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 8. What is the output of below code in latest Chrome

```javascript
var array1 = new Array(3);
console.log(array1);

var array2 = [];
array2[2] = 100;
console.log(array2);

var array3 = [, , ,];
console.log(array3);
```

- 1: [undefined × 3], [undefined × 2, 100], [undefined × 3]
- 2: [empty × 3], [empty × 2, 100], [empty × 3]
- 3: [null × 3], [null × 2, 100], [null × 3]
- 4: [], [100], []

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

The latest chrome versions display `sparse array`(they are filled with holes) using this empty x n notation. Whereas the older versions have undefined x n notation.
**Note:** The latest version of FF displays `n empty slots` notation.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 9. What is the output of below code

```javascript
const obj = {
  prop1: function () {
    return 0;
  },
  prop2() {
    return 1;
  },
  ["prop" + 3]() {
    return 2;
  },
};

console.log(obj.prop1());
console.log(obj.prop2());
console.log(obj.prop3());
```

- 1: 0, 1, 2
- 2: 0, { return 1 }, 2
- 3: 0, { return 1 }, { return 2 }
- 4: 0, 1, undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

ES6 provides method definitions and property shorthands for objects. So both prop2 and prop3 are treated as regular function values.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 10. What is the output of below code

```javascript
console.log(1 < 2 < 3);
console.log(3 > 2 > 1);
```

- 1: true, true
- 2: true, false
- 3: SyntaxError, SyntaxError,
- 4: false, false

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

The important point is that if the statement contains the same operators(e.g, < or >) then it can be evaluated from left to right.
The first statement follows the below order,

1. console.log(1 < 2 < 3);
2. console.log(true < 3);
3. console.log(1 < 3); // True converted as `1` during comparison
4. True

Whereas the second statement follows the below order,

1. console.log(3 > 2 > 1);
2. console.log(true > 1);
3. console.log(1 > 1); // False converted as `0` during comparison
4. False

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 11. What is the output of below code in non-strict mode

```javascript
function printNumbers(first, second, first) {
  console.log(first, second, first);
}
printNumbers(1, 2, 3);
```

- 1: 1, 2, 3
- 2: 3, 2, 3
- 3: SyntaxError: Duplicate parameter name not allowed in this context
- 4: 1, 2, 1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

In non-strict mode, the regular JavaScript functions allow duplicate named parameters. The above code snippet has duplicate parameters on 1st and 3rd parameters.
The value of the first parameter is mapped to the third argument which is passed to the function. Hence, the 3rd argument overrides the first parameter.

**Note:** In strict mode, duplicate parameters will throw a Syntax Error.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 12. What is the output of below code

```javascript
const printNumbersArrow = (first, second, first) => {
  console.log(first, second, first);
};
printNumbersArrow(1, 2, 3);
```

- 1: 1, 2, 3
- 2: 3, 2, 3
- 3: SyntaxError: Duplicate parameter name not allowed in this context
- 4: 1, 2, 1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

Unlike regular functions, the arrow functions doesn't not allow duplicate parameters in either strict or non-strict mode. So you can see `SyntaxError` in the console.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 13. What is the output of below code

```javascript
const arrowFunc = () => arguments.length;
console.log(arrowFunc(1, 2, 3));
```

- 1: ReferenceError: arguments is not defined
- 2: 3
- 3: undefined
- 4: null

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

Arrow functions do not have an `arguments, super, this, or new.target` bindings. So any reference to `arguments` variable tries to resolve to a binding in a lexically enclosing environment. In this case, the arguments variable is not defined outside of the arrow function. Hence, you will receive a reference error.

Where as the normal function provides the number of arguments passed to the function

```javascript
const func = function () {
  return arguments.length;
};
console.log(func(1, 2, 3));
```

But If you still want to use an arrow function then rest operator on arguments provides the expected arguments

```javascript
const arrowFunc = (...args) => args.length;
console.log(arrowFunc(1, 2, 3));
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 14. What is the output of below code

```javascript
console.log(String.prototype.trimLeft.name === "trimLeft");
console.log(String.prototype.trimLeft.name === "trimStart");
```

- 1: True, False
- 2: False, True

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

In order to be consistent with functions like `String.prototype.padStart`, the standard method name for trimming the whitespaces is considered as `trimStart`. Due to web web compatibility reasons, the old method name 'trimLeft' still acts as an alias for 'trimStart'. Hence, the prototype for 'trimLeft' is always 'trimStart'

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 15. What is the output of below code

```javascript
console.log(Math.max());
```

- 1: undefined
- 2: Infinity
- 3: 0
- 4: -Infinity

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

-Infinity is the initial comparant because almost every other value is bigger. So when no arguments are provided, -Infinity is going to be returned.
**Note:** Zero number of arguments is a valid case.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 16. What is the output of below code

```javascript
console.log(10 == [10]);
console.log(10 == [[[[[[[10]]]]]]]);
```

- 1: True, True
- 2: True, False
- 3: False, False
- 4: False, True

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

As per the comparison algorithm in the ECMAScript specification(ECMA-262), the above expression converted into JS as below

```javascript
10 === Number([10].valueOf().toString()); // 10
```

So it doesn't matter about number brackets([]) around the number, it is always converted to a number in the expression.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 17. What is the output of below code

```javascript
console.log(10 + "10");
console.log(10 - "10");
```

- 1: 20, 0
- 2: 1010, 0
- 3: 1010, 10-10
- 4: NaN, NaN

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

The concatenation operator(+) is applicable for both number and string types. So if any operand is string type then both operands concatenated as strings. Whereas subtract(-) operator tries to convert the operands as number type.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 18. What is the output of below code

```javascript
console.log([0] == false);
if ([0]) {
  console.log("I'm True");
} else {
  console.log("I'm False");
}
```

- 1: True, I'm True
- 2: True, I'm False
- 3: False, I'm True
- 4: False, I'm False

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

In comparison operators, the expression `[0]` converted to Number([0].valueOf().toString()) which is resolved to false. Whereas `[0]` just becomes a truthy value without any conversion because there is no comparison operator.

</p>
</details>

#### 19. What is the output of below code

```javascript
console.log([1, 2] + [3, 4]);
```

- 1: [1,2,3,4]
- 2: [1,2][3,4]
- 3: SyntaxError
- 4: 1,23,4

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

The + operator is not meant or defined for arrays. So it converts arrays into strings and concatenates them.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 20. What is the output of below code

```javascript
const numbers = new Set([1, 1, 2, 3, 4]);
console.log(numbers);

const browser = new Set("Firefox");
console.log(browser);
```

- 1: {1, 2, 3, 4}, {"F", "i", "r", "e", "f", "o", "x"}
- 2: {1, 2, 3, 4}, {"F", "i", "r", "e", "o", "x"}
- 3: [1, 2, 3, 4], ["F", "i", "r", "e", "o", "x"]
- 4: {1, 1, 2, 3, 4}, {"F", "i", "r", "e", "f", "o", "x"}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

Since `Set` object is a collection of unique values, it won't allow duplicate values in the collection. At the same time, it is case sensitive data structure.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 21. What is the output of below code

```javascript
console.log(NaN === NaN);
```

- 1: True
- 2: False

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

JavaScript follows IEEE 754 spec standards. As per this spec, NaNs are never equal for floating-point numbers.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 22. What is the output of below code

```javascript
let numbers = [1, 2, 3, 4, NaN];
console.log(numbers.indexOf(NaN));
```

- 1: 4
- 2: NaN
- 3: SyntaxError
- 4: -1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

The `indexOf` uses strict equality operator(===) internally and `NaN === NaN` evaluates to false. Since indexOf won't be able to find NaN inside an array, it returns -1 always.
But you can use `Array.prototype.findIndex` method to find out the index of NaN in an array or You can use `Array.prototype.includes` to check if NaN is present in an array or not.

```javascript
let numbers = [1, 2, 3, 4, NaN];
console.log(numbers.findIndex(Number.isNaN)); // 4

console.log(numbers.includes(NaN)); // true
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 23. What is the output of below code

```javascript
let [a, ...b, c] = [1, 2, 3, 4, 5];
console.log(a, b, c);
```

- 1: 1, [2, 3, 4, 5]
- 2: 1, {2, 3, 4, 5}
- 3: SyntaxError
- 4: 1, [2, 3, 4]

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

When using rest parameters, trailing commas are not allowed and will throw a SyntaxError.
If you remove the trailing comma and last element then it displays 1st answer

```javascript
let [a, ...b] = [1, 2, 3, 4, 5];
console.log(a, b); // 1, [2, 3, 4, 5]
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 25. What is the output of below code

```javascript
async function func() {
  return 10;
}
console.log(func());
```

- 1: Promise {\<fulfilled\>: 10}
- 2: 10
- 3: SyntaxError
- 4: Promise {\<rejected\>: 10}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

Async functions always return a promise. But even if the return value of an async function is not explicitly a promise, it will be implicitly wrapped in a promise. The above async function is equivalent to below expression,

```javascript
function func() {
  return Promise.resolve(10);
}
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 26. What is the output of below code

```javascript
async function func() {
  await 10;
}
console.log(func());
```

- 1: Promise {\<fulfilled\>: 10}
- 2: 10
- 3: SyntaxError
- 4: Promise {\<resolved\>: undefined}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

The await expression returns value 10 with promise resolution and the code after each await expression can be treated as existing in a `.then` callback. In this case, there is no return expression at the end of the function. Hence, the default return value of `undefined` is returned as the resolution of the promise. The above async function is equivalent to below expression,

```javascript
function func() {
  return Promise.resolve(10).then(() => undefined);
}
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 27. What is the output of below code

```javascript
function delay() {
  return new Promise(resolve => setTimeout(resolve, 2000));
}

async function delayedLog(item) {
  await delay();
  console.log(item);
}

async function processArray(array) {
  array.forEach(item => {
    await delayedLog(item);
  })
}

processArray([1, 2, 3, 4]);
```

- 1: SyntaxError
- 2: 1, 2, 3, 4
- 3: 4, 4, 4, 4
- 4: 4, 3, 2, 1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

Even though “processArray” is an async function, the anonymous function that we use for `forEach` is synchronous. If you use await inside a synchronous function then it throws a syntax error.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 28. What is the output of below code

```javascript
function delay() {
  return new Promise((resolve) => setTimeout(resolve, 2000));
}

async function delayedLog(item) {
  await delay();
  console.log(item);
}

async function process(array) {
  array.forEach(async (item) => {
    await delayedLog(item);
  });
  console.log("Process completed!");
}
process([1, 2, 3, 5]);
```

- 1: 1 2 3 5 and Process completed!
- 2: 5 5 5 5 and Process completed!
- 3: Process completed! and 5 5 5 5
- 4: Process completed! and 1 2 3 5

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

The forEach method will not wait until all items are finished but it just runs the tasks and goes next. Hence, the last statement is displayed first followed by a sequence of promise resolutions.

But you control the array sequence using for..of loop,

```javascript
async function processArray(array) {
  for (const item of array) {
    await delayedLog(item);
  }
  console.log("Process completed!");
}
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 29. What is the output of below code

```javascript
var set = new Set();
set.add("+0").add("-0").add(NaN).add(undefined).add(NaN);
console.log(set);
```

- 1: Set(4) {"+0", "-0", NaN, undefined}
- 2: Set(3) {"+0", NaN, undefined}
- 3: Set(5) {"+0", "-0", NaN, undefined, NaN}
- 4: Set(4) {"+0", NaN, undefined, NaN}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

Set has few exceptions from equality check,

1. All NaN values are equal
2. Both +0 and -0 considered as different values

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 30. What is the output of below code

```javascript
const sym1 = Symbol("one");
const sym2 = Symbol("one");

const sym3 = Symbol.for("two");
const sym4 = Symbol.for("two");

console.log(sym1 === sym2, sym3 === sym4);
```

- 1: true, true
- 2: true, false
- 3: false, true
- 4: false, false

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

Symbol follows below conventions,

1. Every symbol value returned from Symbol() is unique irrespective of the optional string.
2. `Symbol.for()` function creates a symbol in a global symbol registry list. But it doesn't necessarily create a new symbol on every call, it checks first if a symbol with the given key is already present in the registry and returns the symbol if it is found. Otherwise a new symbol created in the registry.

**Note:** The symbol description is just useful for debugging purposes.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 31. What is the output of below code

```javascript
const sym1 = new Symbol("one");
console.log(sym1);
```

- 1: SyntaxError
- 2: one
- 3: Symbol('one')
- 4: Symbol

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

`Symbol` is a just a standard function and not an object constructor(unlike other primitives new Boolean, new String and new Number). So if you try to call it with the new operator will result in a TypeError

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 32. What is the output of below code

```javascript
let myNumber = 100;
let myString = "100";

if (!typeof myNumber === "string") {
  console.log("It is not a string!");
} else {
  console.log("It is a string!");
}

if (!typeof myString === "number") {
  console.log("It is not a number!");
} else {
  console.log("It is a number!");
}
```

- 1: SyntaxError
- 2: It is not a string!, It is not a number!
- 3: It is not a string!, It is a number!
- 4: It is a string!, It is a number!

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

The return value of `typeof myNumber` or `typeof myString` is always a truthy value (either "number" or "string"). The ! operator operates on either `typeof myNumber` or `typeof myString`, converting them to boolean values. Since the value of both `!typeof myNumber` and `!typeof myString` is false, the if condition fails, and control goes to else block.

To make the ! operator operate on the equality expression, one needs to add parentheses:

```
if (!(typeof myNumber === "string"))
```

Or simply use the inequality operator:

```
if (typeof myNumber !== "string")
```

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 33. What is the output of below code

```javascript
console.log(
  JSON.stringify({ myArray: ["one", undefined, function () {}, Symbol("")] })
);
console.log(
  JSON.stringify({ [Symbol.for("one")]: "one" }, [Symbol.for("one")])
);
```

- 1: {"myArray":['one', undefined, {}, Symbol]}, {}
- 2: {"myArray":['one', null,null,null]}, {}
- 3: {"myArray":['one', null,null,null]}, "{ [Symbol.for('one')]: 'one' }, [Symbol.for('one')]"
- 4: {"myArray":['one', undefined, function(){}, Symbol('')]}, {}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

The symbols has below constraints,

1. The undefined, Functions, and Symbols are not valid JSON values. So those values are either omitted (in an object) or changed to null (in an array). Hence, it returns null values for the value array.
2. All Symbol-keyed properties will be completely ignored. Hence it returns an empty object({}).

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 34. What is the output of below code

```javascript
class A {
  constructor() {
    console.log(new.target.name);
  }
}

class B extends A {
  constructor() {
    super();
  }
}

new A();
new B();
```

- 1: A, A
- 2: A, B

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

Using constructors, `new.target` refers to the constructor (points to the class definition of class which is initialized) that was directly invoked by new. This also applies to the case if the constructor is in a parent class and was delegated from a child constructor.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 35. What is the output of below code

```javascript
const [x, ...y, z] = [1, 2, 3, 4];
console.log(x, y, z);
```

- 1: 1, [2, 3], 4
- 2: 1, [2, 3, 4], undefined
- 3: 1, [2], 3
- 4: SyntaxError

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

It throws a syntax error because the rest element should not have a trailing comma. You should always consider using a rest operator as the last element.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 36. What is the output of below code

```javascript
const { a: x = 10, b: y = 20 } = { a: 30 };

console.log(x);
console.log(y);
```

- 1: 30, 20
- 2: 10, 20
- 3: 10, undefined
- 4: 30, undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

The object property follows below rules,

1. The object properties can be retrieved and assigned to a variable with a different name
2. The property assigned a default value when the retrieved value is `undefined`

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 37. What is the output of below code

```javascript
function area({ length = 10, width = 20 }) {
  console.log(length * width);
}

area();
```

- 1: 200
- 2: Error
- 3: undefined
- 4: 0

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

If you leave out the right-hand side assignment for the destructuring object, the function will look for at least one argument to be supplied when invoked. Otherwise you will receive an error `Error: Cannot read property 'length' of undefined` as mentioned above.

You can avoid the error with either of the below changes,

1. **Pass at least an empty object:**

```javascript
function area({ length = 10, width = 20 }) {
  console.log(length * width);
}

area({});
```

2. **Assign default empty object:**

```javascript
function area({ length = 10, width = 20 } = {}) {
  console.log(length * width);
}

area();
```

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 38. What is the output of below code

```javascript
const props = [
  { id: 1, name: "John" },
  { id: 2, name: "Jack" },
  { id: 3, name: "Tom" },
];

const [, , { name }] = props;
console.log(name);
```

- 1: Tom
- 2: Error
- 3: undefined
- 4: John

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

It is possible to combine Array and Object destructuring. In this case, the third element in the array props accessed first followed by name property in the object.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 39. What is the output of below code

```javascript
function checkType(num = 1) {
  console.log(typeof num);
}

checkType();
checkType(undefined);
checkType("");
checkType(null);
```

- 1: number, undefined, string, object
- 2: undefined, undefined, string, object
- 3: number, number, string, object
- 4: number, number, number, number

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

If the function argument is set implicitly(not passing argument) or explicitly to undefined, the value of the argument is the default parameter. Whereas for other falsy values('' or null), the value of the argument is passed as a parameter.

Hence, the result of function calls categorized as below,

1. The first two function calls logs number type since the type of default value is number
2. The type of '' and null values are string and object type respectively.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 40. What is the output of below code

```javascript
function add(item, items = []) {
  items.push(item);
  return items;
}

console.log(add("Orange"));
console.log(add("Apple"));
```

- 1: ['Orange'], ['Orange', 'Apple']
- 2: ['Orange'], ['Apple']

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

Since the default argument is evaluated at call time, a new object is created each time the function is called. So in this case, the new array is created and an element pushed to the default empty array.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 41. What is the output of below code

```javascript
function greet(greeting, name, message = greeting + " " + name) {
  console.log([greeting, name, message]);
}

greet("Hello", "John");
greet("Hello", "John", "Good morning!");
```

- 1: SyntaxError
- 2: ['Hello', 'John', 'Hello John'], ['Hello', 'John', 'Good morning!']

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

Since parameters defined earlier are available to later default parameters, this code snippet doesn't throw any error.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 42. What is the output of below code

```javascript
function outer(f = inner()) {
  function inner() {
    return "Inner";
  }
}
outer();
```

- 1: ReferenceError
- 2: Inner

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

The functions and variables declared in the function body cannot be referred from default value parameter initializers. If you still try to access, it throws a run-time ReferenceError(i.e, `inner` is not defined).

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 43. What is the output of below code

```javascript
function myFun(x, y, ...manyMoreArgs) {
  console.log(manyMoreArgs);
}

myFun(1, 2, 3, 4, 5);
myFun(1, 2);
```

- 1: [3, 4, 5], undefined
- 2: SyntaxError
- 3: [3, 4, 5], []
- 4: [3, 4, 5], [undefined]

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

The rest parameter is used to hold the remaining parameters of a function and it becomes an empty array if the argument is not provided.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 44. What is the output of below code

```javascript
const obj = { key: "value" };
const array = [...obj];
console.log(array);
```

- 1: ['key', 'value']
- 2: TypeError
- 3: []
- 4: ['key']

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

Spread syntax can be applied only to iterable objects. By default, Objects are not iterable, but they become iterable when used in an Array, or with iterating functions such as `map(), reduce(), and assign()`. If you still try to do it, it still throws `TypeError: obj is not iterable`.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 45. What is the output of below code

```javascript
function* myGenFunc() {
  yield 1;
  yield 2;
  yield 3;
}
var myGenObj = new myGenFunc();
console.log(myGenObj.next().value);
```

- 1: 1
- 2: undefined
- 3: SyntaxError
- 4: TypeError

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

Generators are not constructible type. But if you still proceed to do, there will be an error saying "TypeError: myGenFunc is not a constructor"

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 46. What is the output of below code

```javascript
function* yieldAndReturn() {
  yield 1;
  return 2;
  yield 3;
}

var myGenObj = yieldAndReturn();
console.log(myGenObj.next());
console.log(myGenObj.next());
console.log(myGenObj.next());
```

- 1: { value: 1, done: false }, { value: 2, done: true }, { value: undefined, done: true }
- 2: { value: 1, done: false }, { value: 2, done: false }, { value: undefined, done: true }
- 3: { value: 1, done: false }, { value: 2, done: true }, { value: 3, done: true }
- 4: { value: 1, done: false }, { value: 2, done: false }, { value: 3, done: true }

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

A return statement in a generator function will make the generator finish. If a value is returned, it will be set as the value property of the object and done property to true. When a generator is finished, subsequent next() calls return an object of this form: `{value: undefined, done: true}`.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 47. What is the output of below code

```javascript
const myGenerator = (function* () {
  yield 1;
  yield 2;
  yield 3;
})();
for (const value of myGenerator) {
  console.log(value);
  break;
}

for (const value of myGenerator) {
  console.log(value);
}
```

- 1: 1,2,3 and 1,2,3
- 2: 1,2,3 and 4,5,6
- 3: 1 and 1
- 4: 1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

The generator should not be re-used once the iterator is closed. i.e, Upon exiting a loop(on completion or using break & return), the generator is closed and trying to iterate over it again does not yield any more results. Hence, the second loop doesn't print any value.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 48. What is the output of below code

```javascript
const num = 0o38;
console.log(num);
```

- 1: SyntaxError
- 2: 38

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

If you use an invalid number(outside of 0-7 range) in the octal literal, JavaScript will throw a SyntaxError. In ES5, it treats the octal literal as a decimal number.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 49. What is the output of below code

```javascript
const squareObj = new Square(10);
console.log(squareObj.area);

class Square {
  constructor(length) {
    this.length = length;
  }

  get area() {
    return this.length * this.length;
  }

  set area(value) {
    this.area = value;
  }
}
```

- 1: 100
- 2: ReferenceError

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

Unlike function declarations, class declarations are not hoisted. i.e, First You need to declare your class and then access it, otherwise it will throw a ReferenceError "Uncaught ReferenceError: Square is not defined".

**Note:** Class expressions also applies to the same hoisting restrictions of class declarations.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 50. What is the output of below code

```javascript
function Person() {}

Person.prototype.walk = function () {
  return this;
};

Person.run = function () {
  return this;
};

let user = new Person();
let walk = user.walk;
console.log(walk());

let run = Person.run;
console.log(run());
```

- 1: undefined, undefined
- 2: Person, Person
- 3: SyntaxError
- 4: Window, Window

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

When a regular or prototype method is called without a value for **this**, the methods return an initial this value if the value is not undefined. Otherwise global window object will be returned. In our case, the initial `this` value is undefined so both methods return window objects.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 51. What is the output of below code

```javascript
class Vehicle {
  constructor(name) {
    this.name = name;
  }

  start() {
    console.log(`${this.name} vehicle started`);
  }
}

class Car extends Vehicle {
  start() {
    console.log(`${this.name} car started`);
    super.start();
  }
}

const car = new Car("BMW");
console.log(car.start());
```

- 1: SyntaxError
- 2: BMW vehicle started, BMW car started
- 3: BMW car started, BMW vehicle started
- 4: BMW car started, BMW car started

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

The super keyword is used to call methods of a superclass. Unlike other languages the super invocation doesn't need to be a first statement. i.e, The statements will be executed in the same order of code.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 52. What is the output of below code

```javascript
const USER = { age: 30 };
USER.age = 25;
console.log(USER.age);
```

- 1: 30
- 2: 25
- 3: Uncaught TypeError
- 4: SyntaxError

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

Even though we used constant variables, the content of it is an object and the object's contents (e.g properties) can be altered. Hence, the change is going to be valid in this case.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 53. What is the output of below code

```javascript
console.log("🙂" === "🙂");
```

- 1: false
- 2: true

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

Emojis are unicodes and the unicode for smile symbol is "U+1F642". The unicode comparison of same emojies is equivalent to string comparison. Hence, the output is always true.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 54. What is the output of below code?

```javascript
console.log(typeof typeof typeof true);
```

- 1: string
- 2: boolean
- 3: NaN
- 4: number

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

The typeof operator on any primitive returns a string value. So even if you apply the chain of typeof operators on the return value, it is always string.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 55. What is the output of below code?

```javascript
let zero = new Number(0);

if (zero) {
  console.log("If");
} else {
  console.log("Else");
}
```

- 1: If
- 2: Else
- 3: NaN
- 4: SyntaxError

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

1. The type of operator on new Number always returns object. i.e, typeof new Number(0) --> object.
2. Objects are always truthy in if block

Hence the above code block always goes to if section.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 55. What is the output of below code in non strict mode?

```javascript
let msg = "Good morning!!";

msg.name = "John";

console.log(msg.name);
```

- 1: ""
- 2: Error
- 3: John
- 4: Undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

It returns undefined for non-strict mode and returns Error for strict mode. In non-strict mode, the wrapper object is going to be created and get the mentioned property. But the object get disappeared after accessing the property in next line.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 56. What is the output of below code?

```javascript
let count = 10;

(function innerFunc() {
  if (count === 10) {
    let count = 11;
    console.log(count);
  }
  console.log(count);
})();
```

- 1: 11, 10
- 2: 11, 11
- 3: 10, 11
- 4: 10, 10

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

11 and 10 is logged to the console.

The innerFunc is a closure which captures the count variable from the outerscope. i.e, 10. But the conditional has another local variable `count` which overwrites the ourter `count` variable. So the first console.log displays value 11.
Whereas the second console.log logs 10 by capturing the count variable from outerscope.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 57. What is the output of below code ?

- 1: console.log(true && 'hi');
- 2: console.log(true && 'hi' && 1);
- 3: console.log(true && '' && 0);

<details><summary><b>Answer</b></summary>

- 1: hi
- 2: 1
- 3: ''

Reason : The operator returns the value of the first falsy operand encountered when evaluating from left to right, or the value of the last operand if they are all truthy.

**Note:** Below these values are consider as falsy value

- 1: 0
- 2: ''
- 3: null
- 4: undefined
- 5: NAN

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 58. What is the output of below code ?

```javascript
let arr = [1, 2, 3];
let str = "1,2,3";

console.log(arr == str);
```

- 1: false
- 2: Error
- 3: true

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

Arrays have their own implementation of `toString` method that returns a comma-separated list of elements. So the above code snippet returns true. In order to avoid conversion of array type, we should use === for comparison.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 59. What is the output of below code?

```javascript
getMessage();

var getMessage = () => {
  console.log("Good morning");
};
```

- 1: Good morning
- 2: getMessage is not a function
- 3: getMessage is not defined
- 4: Undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

Hoisting will move variables and functions to be the top of scope. Even though getMessage is an arrow function the above function will considered as a variable due to it's variable declaration or assignment. So the variables will have undefined value in memory phase and throws an error '`getMessage` is not a function' at the code execution phase.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 60. What is the output of below code?

```javascript
let quickPromise = Promise.resolve();

quickPromise.then(() => console.log("promise finished"));

console.log("program finished");
```

- 1: program finished
- 2: Cannot predict the order
- 3: program finished, promise finished
- 4: promise finished, program finished

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

Even though a promise is resolved immediately, it won't be executed immediately because its **.then/catch/finally** handlers or callbacks(aka task) are pushed into the queue. Whenever the JavaScript engine becomes free from the current program, it pulls a task from the queue and executes it. This is the reason why last statement is printed first before the log of promise handler.

**Note:** We call the above queue as "MicroTask Queue"

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 61. What is the output of below code?

```javascript
console
  .log("First line")
  [("a", "b", "c")].forEach((element) => console.log(element));
console.log("Third line");
```

- 1: `First line`, then print `a, b, c` in a new line, and finally print `Third line` as next line
- 2: `First line`, then print `a, b, c` in a first line, and print `Third line` as next line
- 3: Missing semi-colon error
- 4: Cannot read properties of undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

When JavaScript encounters a line break without a semicolon, the JavaScript parser will automatically add a semicolon based on a set of rules called `Automatic Semicolon Insertion` which determines whether line break as end of statement or not to insert semicolon. But it does not assume a semicolon before square brackets [...]. So the first two lines considered as a single statement as below.

```javascript
console
  .log("First line")
  [("a", "b", "c")].forEach((element) => console.log(element));
```

Hence, there will be **cannot read properties of undefined** error while applying the array square bracket on log function.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 62. Write a function that returns a random HEX color

<details><summary><b>Solution 1 (Iterative generation)</b></summary>
<p>

```javascript
const HEX_ALPHABET = [
  "0",
  "1",
  "2",
  "3",
  "4",
  "5",
  "6",
  "7",
  "8",
  "9",
  "a",
  "b",
  "c",
  "d",
  "e",
  "f",
];
const HEX_PREFIX = "#";
const HEX_LENGTH = 6;

function generateRandomHex() {
  let randomHex = "";

  for (let i = 0; i < HEX_LENGTH; i++) {
    const randomIndex = Math.floor(Math.random() * HEX_ALPHABET.length);
    randomHex += HEX_ALPHABET[randomIndex];
  }

  return HEX_PREFIX + randomHex;
}
```

</p>

</details>

<details><summary><b>Solution 2 (One-liner)</b></summary>
<p>

```javascript
const HEX_PREFIX = "#";
const HEX_RADIX = 16;
const HEX_LENGTH = 6;

function generateRandomHex() {
  return (
    HEX_PREFIX +
    Math.floor(Math.random() * 0xffffff)
      .toString(HEX_RADIX)
      .padStart(HEX_LENGTH, "0")
  );
}
```

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 63. What is the output of below code?

```javascript
var of = ["of"];
for (var of of of) {
  console.log(of);
}
```

- 1: of
- 2: SyntaxError: Unexpected token of
- 3: SyntaxError: Identifier 'of' has already been declared
- 4: ReferenceError: of is not defined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

In JavaScript, `of` is not considered as a reserved keyword. So the variable declaration with `of` is accepted and prints the array value `of` using for..of loop.

But if you use reserved keyword such as `in` then there will be a syntax error saying `SyntaxError: Unexpected token in`,

```javascript
var in = ['in'];
for(var in in in) {
  console.log(in[in]);
}
```

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 64. What is the output of below code?

```javascript
const numbers = [11, 25, 31, 23, 33, 18, 200];
numbers.sort();
console.log(numbers);
```

- 1: [11, 18, 23, 25, 31, 33, 200]
- 2: [11, 18, 200, 23, 25, 31, 33]
- 3: [11, 25, 31, 23, 33, 18, 200]
- 4: Cannot sort numbers

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

By default, the sort method sorts elements alphabetically. This is because elemented converted to strings and strings compared in UTF-16 code units order. Hence, you will see the above numbers not sorted as expected. In order to sort numerically just supply a comparator function which handles numeric sorts.

```javascript
const numbers = [11, 25, 31, 23, 33, 18, 200];
numbers.sort((a, b) => a - b);
console.log(numbers);
```

**Note:** Sort() method changes the original array.

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 65. What is the output order of below code?

```javascript
setTimeout(() => {
  console.log("1");
}, 0);
Promise.resolve("hello").then(() => console.log("2"));
console.log("3");
```

- 1: 1, 2, 3
- 2: 1, 3, 2
- 3: 3, 1, 2
- 4: 3, 2, 1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

When the JavaScript engine parses the above code, the first two statements are asynchronous which will be executed later and third statement is synchronous statement which will be moved to callstack, executed and prints the number 3 in the console. Next, Promise is native in ES6 and it will be moved to Job queue which has high priority than callback queue in the execution order. At last, since setTimeout is part of WebAPI the callback function moved to callback queue and executed. Hence, you will see number 2 printed first followed by 1.

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 66. What is the output of below code?

```javascript
console.log(name);
console.log(message());
var name = "John";
(function message() {
  console.log("Hello John: Welcome");
});
```

- 1: John, Hello John: Welcome
- 2: undefined, Hello John, Welcome
- 3: Reference error: name is not defined, Reference error: message is not defined
- 4: undefined, Reference error: message is not defined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

IIFE(Immediately Invoked Function Expression) is just like any other function expression which won't be hoisted. Hence, there will be a reference error for message call.
The behavior would be the same with below function expression of message1,

```javascript
console.log(name);
console.log(message());
var name = 'John';
var message = function () {
   console.log('Hello John: Welcome');
});
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 67. What is the output of below code?

```javascript
message();

function message() {
  console.log("Hello");
}
function message() {
  console.log("Bye");
}
```

- 1: Reference error: message is not defined
- 2: Hello
- 3: Bye
- 4: Compile time error

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

As part of hoisting, initially JavaScript Engine or compiler will store first function in heap memory but later rewrite or replaces with redefined function content.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 68. What is the output of below code?

```javascript
var currentCity = "NewYork";

var changeCurrentCity = function () {
  console.log("Current City:", currentCity);
  var currentCity = "Singapore";
  console.log("Current City:", currentCity);
};

changeCurrentCity();
```

- 1: NewYork, Singapore
- 2: NewYork, NewYork
- 3: undefined, Singapore
- 4: Singapore, Singapore

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

Due to hositing feature, the variables declared with `var` will have `undefined` value in the creation phase so the outer variable `currentCity` will get same `undefined` value. But after few lines of code JavaScript engine found a new function call(`changeCurrentCity()`) to update the current city with `var` re-declaration. Since each function call will create a new execution context, the same variable will have `undefined` value before the declaration and new value(`Singapore`) after the declaration. Hence, the value `undefined` print first followed by new value `Singapore` in the execution phase.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 69. What is the output of below code in an order?

```javascript
function second() {
  var message;
  console.log(message);
}

function first() {
  var message = "first";
  second();
  console.log(message);
}

var message = "default";
first();
console.log(message);
```

- 1: undefined, first, default
- 2: default, default, default
- 3: first, first, default
- 4: undefined, undefined, undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

Each context(global or functional) has it's own variable environment and the callstack of variables in a LIFO order. So you can see the message variable value from second, first functions in an order followed by global context message variable value at the end.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 70. What is the output of below code?

```javascript
var expressionOne = function functionOne() {
  console.log("functionOne");
};
functionOne();
```

- 1: functionOne is not defined
- 2: functionOne
- 3: console.log("functionOne")
- 4: undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

The function call `functionOne` is not going to be part of scope chain and it has it's own execution context with the enclosed variable environment. i.e, It won't be accessed from global context. Hence, there will be an error while invoking the function as `functionOne is not defined`.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 71. What is the output of below code?

```javascript
const user = {
  name: "John",
  eat() {
    console.log(this);
    var eatFruit = function () {
      console.log(this);
    };
    eatFruit();
  },
};
user.eat();
```

- 1: {name: "John", eat: f}, {name: "John", eat: f}
- 2: Window {...}, Window {...}
- 3: {name: "John", eat: f}, undefined
- 4: {name: "John", eat: f}, Window {...}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

`this` keyword is dynamic scoped but not lexically scoped . In other words, it doesn't matter where `this` has been written but how it has been invoked really matter. In the above code snippet, the `user` object invokes `eat` function so `this` keyword refers to `user` object but `eatFruit` has been invoked by `eat` function and `this` will have default `Window` object.

The above pit fall fixed by three ways,

1. In ES6, the arrow function will make `this` keyword as lexically scoped. Since the surrounding object of `this` object is `user` object, the `eatFruit` function will contain `user` object for `this` object.

```javascript
const user = {
  name: "John",
  eat() {
    console.log(this);
    var eatFruit = () => {
      console.log(this);
    };
    eatFruit();
  },
};
user.eat();
```

The next two solutions have been used before ES6 introduced.

2.  It is possible create a reference of `this` into a separate variable and use that new variable inplace of `this` keyword inside `eatFruit` function. This is a common practice in jQuery and AngularJS before ES6 introduced.

```javascript
const user = {
  name: "John",
  eat() {
    console.log(this);
    var self = this;
    var eatFruit = () => {
      console.log(self);
    };
    eatFruit();
  },
};
user.eat();
```

3. The `eatFruit` function can bind explicitly with `this` keyword where it refers `Window` object.

```javascript
const user = {
  name: "John",
  eat() {
    console.log(this);
    var eatFruit = function () {
      console.log(this);
    };
    return eatFruit.bind(this);
  },
};
user.eat()();
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 72. What is the output of below code?

```javascript
let message = "Hello World!";
message[0] = "J";
console.log(message);

let name = "John";
name = name + " Smith";
console.log(name);
```

- 1: Jello World!, John Smith
- 2: Jello World!, John
- 3: Hello World!, John Smith
- 4: Hello World!, John

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

In JavaScript, primitives are immutable i.e. there is no way to change a primitive value once it gets created. So when you try to update the string's first character, there is no change in the string value and prints the same initial value `Hello World!`. Whereas in the later example, the concatenated value is re-assigned to the same variable which will result into creation of new memory block with the reference pointing to `John Smith` value and the old memory block value(`John`) will be garbage collected.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 73. What is the output of below code?

```javascript
let user1 = {
  name: "Jacob",
  age: 28,
};

let user2 = {
  name: "Jacob",
  age: 28,
};

console.log(user1 === user2);
```

- 1: True
- 2: False
- 3: Compile time error

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

In JavaScript, the variables such as objects, arrays and functions comes under pass by reference. When you try to compare two objects with same content, it is going to compare memory address or reference of those variables. These variables always create separate memory blocks hence the comparison is always going to return false value.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 74. What is the output of below code?

```javascript
function greeting() {
  setTimeout(function () {
    console.log(message);
  }, 5000);
  const message = "Hello, Good morning";
}
greeting();
```

- 1: Undefined
- 2: Reference error:
- 3: Hello, Good morning
- 4: null

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

The variable `message` is still treated as closure(since it has been used in inner function) eventhough it has been declared after setTimeout function. The function with in setTimeout function will be sent to WebAPI and the variable declaration executed with in 5 seconds with the assigned value. Hence, the text declared for the variable will be displayed.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 75. What is the output of below code?

```javascript
const a = new Number(10);
const b = 10;
console.log(a === b);
```

- 1: False
- 2: True

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

Eventhough both variables `a` and `b` refer a number value, the first declaration is based on constructor function and the type of the variable is going to be `object` type. Whereas the second declaration is primitive assignment with a number and the type is `number` type. Hence, the equality operator `===` will output `false` value.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 76. What is the type of below function?

```javascript
function add(a, b) {
  console.log("The input arguments are: ", a, b);
  return a + b;
}
```

- 1: Pure function
- 2: Impure function

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

Eventhough the above function returns the same result for the same arguments(input) that are passed in the function, the `console.log()` statement causes a function to have side effects because it affects the state of an external code. i.e, the `console` object's state and depends on it to perform the job. Hence, the above function considered as impure function.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 77. What is the output of below code?

```javascript
const promiseOne = new Promise((resolve, reject) => setTimeout(resolve, 4000));
const promiseTwo = new Promise((resolve, reject) => setTimeout(reject, 4000));

Promise.all([promiseOne, promiseTwo]).then((data) => console.log(data));
```

- 1: [{status: "fulfilled", value: undefined}, {status: "rejected", reason: undefined}]
- 2: [{status: "fulfilled", value: undefined}, Uncaught(in promise)]
- 3: Uncaught (in promise)
- 4: [Uncaught(in promise), Uncaught(in promise)]

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

The above promises settled at the same time but one of them resolved and other one rejected. When you use `.all` method on these promises, the result will be short circuted by throwing an error due to rejection in second promise. But If you use `.allSettled` method then result of both the promises will be returned irrespective of resolved or rejected promise status without throwing any error.

```javascript
Promise.allSettled([promiseOne, promiseTwo]).then((data) => console.log(data));
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 78. What is the output of below code?

```javascript
try {
  setTimeout(() => {
    console.log("try block");
    throw new Error(`An exception is thrown`);
  }, 1000);
} catch (err) {
  console.log("Error: ", err);
}
```

- 1: try block, Error: An exception is thrown
- 2: Error: An exception is thrown
- 3: try block, Uncaught Error: Exception is thrown
- 4: Uncaught Error: Exception is thrown

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

If you put `setTimeout` and `setInterval` methods inside the try clause and an exception is thrown, the catch clause will not catch any of them. This is because the try...catch statement works synchronously, and the function in the above code is executed asynchronously after a certain period of time. Hence, you will see runtime exception without catching the error. To resolve this issue, you have to put the try...catch block inside the function as below,

```javascript
setTimeout(() => {
  try {
    console.log("try block");
    throw new Error(`An exception is thrown`);
  } catch (err) {
    console.log("Error: ", err);
  }
}, 1000);
```

You can use `.catch()` function in promises to avoid these issues with asynchronous code.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 79. What is the output of below code?

```javascript
let a = 10;
if (true) {
  let a = 20;
  console.log(a, "inside");
}
console.log(a, "outside");
```

- 1: 20, "inside" and 20, "outside"
- 2: 20, "inside" and 10, "outside"
- 3: 10, "inside" and 10, "outside"
- 4: 10, "inside" and 20, "outside"

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

The variable "a" declared inside "if" has block scope and does not affect the value of the outer "a" variable.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 80. What is the output of below code?

```javascript
let arr = [1, 2, 3, 4, 5, -6, 7];
arr.length = 0;
console.log(arr);
```

- 1: 0
- 2: Undefined
- 3: null
- 4: [ ]

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

The length of the array 'arr' has been set to 0, so the array becomes empty.

</p>
</details>
---

**[⬆ Back to Top](#table-of-contents)**

#### 81. How do you verify two strings are anagrams or not?

An anagram is a word or phrase formed by rearranging all the letters of a different word or phrase exactly once. For example, the anagrams of "eat" word are "tea" and "ate".

You can split each word into characters, followed by sort action and later join them back. After that you can compare those two words to verify whether those two words are anagrams or not.

```javascript
function verifyAnagrams(word1, word2) {
  return word1.split("").sort().join("") === word2.split("").sort().join("");
}
console.log(verifyAnagrams("eat", "ate"));
```

**[⬆ Back to Top](#table-of-contents)**

#### 82. What is the output of below code?

```javascript
printHello();

printMessage();

function printHello() {
  console.log("Hello");

  function printMessage() {
    console.log("Good day");
  }
}
```

- 1: Hello, Good day
- 2: Reference Error: printHello is not defined, Reference Error: printMessage is not defined
- 3: Reference Error: printHello is not defined, Good day
- 4: Hello, Reference Error: printMessage is not defined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

The function `printHello` is hoisted to the top of the global scope and prints "Hello" to the console. Even `printMessage` function is hoisted, but it is lifted to the local scope(in "printHello") it was declared in. That is the reason you will endup with reference error for second function call.

But if the second function is invoked in the first function itself, there won't be any reference error.

```javascript
printHello();

function printHello() {
  printMessage();
  console.log("Hello");

  function printMessage() {
    console.log("Good day");
  }
}
```

</p>
</details>
---

**[⬆ Back to Top](#table-of-contents)**

#### 83. What is the time taken to execute below timeout callback?

```javascript
console.log("Start code");

setTimeout(function () {
  console.log("Callback code");
}, 5000);

console.log("After callback");

let startTime = new Date().getTime();
let endTime = startTime;

while (endTime <= startTime + 10000) {
  endTime = new Date().getTime();
}

console.log("End code");
```

- 1: > 10 sec
- 2: Immediately
- 3: < 10 sec
- 4: <= 5sec

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

Even though there is a timer of 5 seconds supplied to `setTimeout` callback, it won't get executed until the main thread is free and finished executing the remaining part of the code. In this example, the remaining code(while loop) takes 10seconds to finish it's execution. In the mean time, the callback will be stored in callback queue upon completion of its 5 seconds timer. After 10 seconds, the callback will be moved to callstack because the callstack is empty by poping out global execution context.

</p>
</details>

**[⬆ Back to Top](#table-of-contents)**

#### 84. What is the output of below code?

```javascript
let arr = ["wöchentlich", "Woche", "wäre", "Wann"];
console.log(arr.sort());
```

- 1: ['wöchentlich','Woche', 'wäre', 'Wann']
- 2: ['Wann', 'wäre', 'Woche', 'wöchentlich']
- 3: ['Wann', 'Woche', 'wäre', 'wöchentlich']
- 4: ['wäre', 'Wann', 'wöchentlich','Woche']

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

Javascript has a native method sort that allows sorting an array of elements in-place. It will treat each element as a string and sort it alphabetically. But if you try to sort an array of strings which has non-ASCII characters, you will receive a strange result. This is because characters with an accent have higher character codes.

In this case, the sort order of an array is ['Wann', 'Woche', 'wäre', 'wöchentlich'].

If you want to sort an array of string values which has non-ASCII characters in an ascending order, there are two possible options like **localeCompare** and **Intl.Collator** provided by ECMAScript Internationalization API.

**localeCompare:**

```javascript
let arr = ["wöchentlich", "Woche", "wäre", "Wann"];
console.log(arr.sort((a, b) => a.localeCompare(b))); //['Wann', 'wäre', 'Woche', 'wöchentlich']
```

**Intl.Collator:**

```javascript
let arr = ["wöchentlich", "Woche", "wäre", "Wann"];
console.log(arr.sort(Intl.Collator().compare)); //['Wann', 'wäre', 'Woche', 'wöchentlich']
```

</p>
</details>

**[⬆ Back to Top](#table-of-contents)**

#### 85. What is the output of below code?

```javascript
function func(a, b = 2) {
  console.log(arguments.length);
}

func(undefined);
func();
```

- 1: 1, 0
- 2: 0, 0
- 3: 0, 1
- 4: 1, 1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

If a function is called with `undefined`, the `undefined` value is treated as a parameter. But if the function is not passed with any parameters, the `arguments` object doesn't include any argument eventhough the function has default function parameter. Hence, the function invocation with `undefined` has one argument and function call without any arguments has 0 arguments.

</p>
</details>

**[⬆ Back to Top](#table-of-contents)**

#### 86. What is the output of below code?

```javascript
function func(a, b = 2) {
  console.log(arguments.length);
}

func(undefined);
func();
```

- 1: 1, 0
- 2: 0, 0
- 3: 0, 1
- 4: 1, 1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

If a function is called with `undefined`, the `undefined` value is treated as a parameter. But if the function is not passed with any parameters, the `arguments` object doesn't include any argument eventhough the function has default function parameter. Hence, the function invocation with `undefined` has one argument and function call without any arguments has 0 arguments.

</p>
</details>

**[⬆ Back to Top](#table-of-contents)**

## Disclaimer

The questions provided in this repository are the summary of frequently asked questions across numerous companies. We cannot guarantee that these questions will actually be asked during your interview process, nor should you focus on memorizing all of them. The primary purpose is for you to get a sense of what some companies might ask — do not get discouraged if you don't know the answer to all of them ⁠— that is ok!

Good luck with your interview 😊

---
