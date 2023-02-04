# Javascript Interview preparation

Table of Contents
=================

* [Javascript Interview preparation](#javascript-interview-preparation)
* [Table of Contents](#table-of-contents)
   * [Javascript Concepts](#javascript-concepts)
      * [Variable, Scope, Hoisting](#variable-scope-hoisting)
      * [this](#this)
      * [Patterns](#patterns)
      * [Prototype](#prototype)
      * [Functions](#functions)
      * [Closure](#closure)
      * [Iterators](#iterators)
      * [Currying](#currying)
      * [Promises](#promises)
      * [Es6+](#es6)
      * [Array](#array)
      * [Event Loop](#event-loop)
      * [Objects](#objects)
      * [String](#string)
      * [Date and time](#date-and-time)
      * [Regex](#regex)
      * [Error Handling](#error-handling)
   * [Javascript Style Guides](#javascript-style-guides)
   * [Performance/Code Optimization](#performancecode-optimization)
   * [Javascript Interview Questions](#javascript-interview-questions)
   * [Tips and Tricks](#tips-and-tricks)
   * [Javascript Cheatsheet](#javascript-cheatsheet)
   * [Javascript News Letters](#javascript-news-letters)
   * [Developers to follow](#developers-to-follow)
   * [Javascript Algorithm](#javascript-algorithm)
   * [Learn Javascript](#learn-javascript)
   * [Javascript Books](#javascript-books)
   * [General](#general)
   * [Best Practices](#best-practices)
   * [Javascript Projects](#javascript-projects)
   * [Youtube channels](#youtube-channels)
   * [Javascipt vs Typescript](#javascipt-vs-typescript)

## `Javascript Concepts`
- ### Variable, Scope, Hoisting
    - [https://livecodestream.dev/post/understanding-variables-scope-and-hoisting-in-javascript/](https://livecodestream.dev/post/understanding-variables-scope-and-hoisting-in-javascript/)<br/>
    - [https://www.freecodecamp.org/news/javascript-lexical-scope-tutorial/](https://www.freecodecamp.org/news/javascript-lexical-scope-tutorial/)<br/>
    - [https://slashism.com/variable-scope-in-javascript](https://slashism.com/variable-scope-in-javascript)<br>
    - [https://wasefs.medium.com/hoisting-in-javascript-javascript-interview-series-53f9faa16835](https://wasefs.medium.com/hoisting-in-javascript-javascript-interview-series-53f9faa16835)<br>
    - [https://dev.to/pat_the99/javascript-hoisting-450l](https://dev.to/pat_the99/javascript-hoisting-450l)<br>
    - [https://kpealecodes.hashnode.dev/scoping-and-hoisting-in-javascript](https://kpealecodes.hashnode.dev/scoping-and-hoisting-in-javascript)<br>
    - [https://slashism.com/variable-scope-in-javascript](https://slashism.com/variable-scope-in-javascript)<br>
    - [https://developer.mozilla.org/en-US/docs/Glossary/Primitive#Another_Example_Step-by-step](https://developer.mozilla.org/en-US/docs/Glossary/Primitive#Another_Example_Step-by-step)<br>
    - [https://livecodestream.dev/post/2020-07-25-understanding-variables-scope-and-hoisting-in-javascript/](https://livecodestream.dev/post/2020-07-25-understanding-variables-scope-and-hoisting-in-javascript/)<br>
    - [https://dev.to/sandy8111112004/javascript-introduction-to-scope-function-scope-block-scope-d11](https://dev.to/sandy8111112004/javascript-introduction-to-scope-function-scope-block-scope-d11)<br>
    - [https://devdojo.com/imkarthikeyans/quick-guide-to-closures-in-javascript](https://devdojo.com/imkarthikeyans/quick-guide-to-closures-in-javascript)<br>
    - [https://www.freecodecamp.org/news/what-is-hoisting-in-javascript/](https://www.freecodecamp.org/news/what-is-hoisting-in-javascript/)<br>
    - [https://peculiar-erhis.hashnode.dev/global-variables-the-potential-landmine-lurking-in-your-javascript-codebase](https://peculiar-erhis.hashnode.dev/global-variables-the-potential-landmine-lurking-in-your-javascript-codebase)<br>
    - [https://devdojo.com/rahulism/symbol-in-javascript-a-primitive-data-type](https://devdojo.com/rahulism/symbol-in-javascript-a-primitive-data-type)<br>
    - [https://dev.to/jpomykala/number-formatting-in-javascript-1mc](https://dev.to/jpomykala/number-formatting-in-javascript-1mc)<br>
    - [https://javascript.plainenglish.io/difference-between-let-var-in-javascript-2497ec45641b](https://javascript.plainenglish.io/difference-between-let-var-in-javascript-2497ec45641b)<br>
    - [https://zahab.tech/learn-javascript-part1#ckxpjc4k0002te3s19v7b56i4](https://zahab.tech/learn-javascript-part1#ckxpjc4k0002te3s19v7b56i4)<br>
    - [https://javascript.plainenglish.io/a-javascript-crash-course-data-types-var-let-and-const-a8f4322284b2](https://javascript.plainenglish.io/a-javascript-crash-course-data-types-var-let-and-const-a8f4322284b2)<br>
    - [https://javascript.plainenglish.io/hoisting-in-javascript-a0320bb42921](https://javascript.plainenglish.io/hoisting-in-javascript-a0320bb42921)<br>
    - [https://www.freecodecamp.org/news/var-let-and-const-whats-the-difference/](https://www.freecodecamp.org/news/var-let-and-const-whats-the-difference/)<br>
    - [https://www.syncfusion.com/blogs/post/10-javascript-naming-conventions-every-developer-should-know.aspx](https://www.syncfusion.com/blogs/post/10-javascript-naming-conventions-every-developer-should-know.aspx)<br>
    - [https://javascript.plainenglish.io/why-is-javascripts-parseint-0-0000005-5-eb9e2432f1b0](https://javascript.plainenglish.io/why-is-javascripts-parseint-0-0000005-5-eb9e2432f1b0)<br>
    - [https://bytecodepandit.medium.com/scopes-in-javascript-89d1f8b00643](https://bytecodepandit.medium.com/scopes-in-javascript-89d1f8b00643)<br>
    - [https://javascript.plainenglish.io/javascript-concepts-every-programmer-should-know-d04731fe7a7c](https://javascript.plainenglish.io/javascript-concepts-every-programmer-should-know-d04731fe7a7c)<br>
    - [https://iamclement.hashnode.dev/javascript-operator](https://iamclement.hashnode.dev/javascript-operator)<br>
    - [https://blog.openreplay.com/javascript-type-conversions-explained](https://blog.openreplay.com/javascript-type-conversions-explained)<br>
    - [https://dev.to/alexomeyer/8-must-know-tips-for-writing-clean-code-with-javascript-i4](https://dev.to/alexomeyer/8-must-know-tips-for-writing-clean-code-with-javascript-i4)<br>
    - [https://www.syncfusion.com/blogs/post/null-vs-undefined-in-javascript.aspx](https://www.syncfusion.com/blogs/post/null-vs-undefined-in-javascript.aspx)<br>
    - [https://www.freecodecamp.org/news/javascript-type-checking-how-to-check-type-in-js-with-typeof/](https://www.freecodecamp.org/news/javascript-type-checking-how-to-check-type-in-js-with-typeof/)<br>


- ### this
    - [https://ui.dev/this-keyword-call-apply-bind-javascript/](https://ui.dev/this-keyword-call-apply-bind-javascript/)<br/>
    - [https://livecodestream.dev/post/understanding-this-keyword-in-javascript/](https://livecodestream.dev/post/understanding-this-keyword-in-javascript/)<br/>
    - [https://dev.to/polymathsomnath/master-this-in-javascript-1bk](https://dev.to/polymathsomnath/master-this-in-javascript-1bk)<br>
    - [https://medium.com/swlh/whats-this-in-javascript-870918e833b8](https://medium.com/swlh/whats-this-in-javascript-870918e833b8)<br>
    - [https://rajatexplains.hashnode.dev/this-in-javascript](https://rajatexplains.hashnode.dev/this-in-javascript)<br>
    - [https://medium.com/swlh/understanding-this-in-javascript-166164e7fa2b](https://medium.com/swlh/understanding-this-in-javascript-166164e7fa2b)<br>
    - [https://dev.to/denisveleaev/6-simple-rules-to-fully-understand-this-keyword-in-javascript-1kmk](https://dev.to/denisveleaev/6-simple-rules-to-fully-understand-this-keyword-in-javascript-1kmk)<br>
    - [https://medium.com/free-code-camp/react-binding-patterns-5-approaches-for-handling-this-92c651b5af56#.53op90a6w](https://medium.com/free-code-camp/react-binding-patterns-5-approaches-for-handling-this-92c651b5af56#.53op90a6w)<br>
    - [https://enlear.academy/this-keyword-in-javascript-8979fa01f4a3](https://enlear.academy/this-keyword-in-javascript-8979fa01f4a3)<br>
    - [https://blog.tusharcodes.tech/5-rules-to-master-this-in-javascript](https://blog.tusharcodes.tech/5-rules-to-master-this-in-javascript)<br>
    - [https://medium.com/@rifat.kazak/what-is-this-keyword-in-javascript-967d0633930a](https://medium.com/@rifat.kazak/what-is-this-keyword-in-javascript-967d0633930a)<br/>
    - [https://www.freecodecamp.org/news/the-this-keyword-in-javascript/](https://www.freecodecamp.org/news/the-this-keyword-in-javascript/)<br>

- ### Patterns
    - [https://hemdan.hashnode.dev/javascript-patterns-ch2-or-part-1-essentials](https://hemdan.hashnode.dev/javascript-patterns-ch2-or-part-1-essentials)<br>
    - [https://medium.com/swlh/js-interview-help-prototype-class-es6-iife-scope-closures-module-pattern-fd67c68aacb8](https://medium.com/swlh/js-interview-help-prototype-class-es6-iife-scope-closures-module-pattern-fd67c68aacb8)<br/>
    - [https://medium.com/javascript-in-plain-english/basic-middleware-pattern-in-javascript-ef8756a75cb1](https://medium.com/javascript-in-plain-english/basic-middleware-pattern-in-javascript-ef8756a75cb1)<br>
    - [https://levelup.gitconnected.com/design-patterns-in-modern-javascript-development-ec84d8be06ca?gi=6e6506fac97e](https://levelup.gitconnected.com/design-patterns-in-modern-javascript-development-ec84d8be06ca?gi=6e6506fac97e)<br>
    - [https://devdojo.com/rahulism/module-pattern-in-javascripit-oop-quickie](https://devdojo.com/rahulism/module-pattern-in-javascripit-oop-quickie)<br>
    - [https://evinsellin.medium.com/chaotic-javascript-patterns-1025a8f077e6](https://evinsellin.medium.com/chaotic-javascript-patterns-1025a8f077e6)<br>
    - [https://devdojo.com/rahulism/decorators-and-object-creation-pattern-in-javascript](https://devdojo.com/rahulism/decorators-and-object-creation-pattern-in-javascript)<br>
    - [https://dev.to/dhiwise/advanced-javascript-design-patterns-4k8l](https://dev.to/dhiwise/advanced-javascript-design-patterns-4k8l)<br>
    - [https://www.thisdot.co/blog/clean-up-your-code-with-design-patterns-in-javascript](https://www.thisdot.co/blog/clean-up-your-code-with-design-patterns-in-javascript)<br>
    - [https://dev.to/dhiwise/advanced-javascript-design-patterns-4k8l?ck_subscriber_id=1519802657](https://dev.to/dhiwise/advanced-javascript-design-patterns-4k8l?ck_subscriber_id=1519802657)<br>
    - [https://github.com/leonardomso/33-js-concepts#31-design-patterns](https://github.com/leonardomso/33-js-concepts#31-design-patterns)<br>
    - [https://hemdan.hashnode.dev/javascript-patterns-ch1-introduction](https://hemdan.hashnode.dev/javascript-patterns-ch1-introduction)<br>
    - [https://hackernoon.com/9-javascript-design-patters-you-will-love](https://hackernoon.com/9-javascript-design-patters-you-will-love)<br>
    - [https://levelup.gitconnected.com/whats-hof-in-javascript-9fb68a9c3f6f](https://levelup.gitconnected.com/whats-hof-in-javascript-9fb68a9c3f6f)<br>
    - [https://www.freecodecamp.org/news/javascript-design-patterns-explained/](https://www.freecodecamp.org/news/javascript-design-patterns-explained/)<br>
    - [https://blog.upperdine.dev/patterns-that-every-developer-should-know](https://blog.upperdine.dev/patterns-that-every-developer-should-know)<br>
    - [https://javascriptpatterns.vercel.app/patterns](https://javascriptpatterns.vercel.app/patterns)<br>

- ### Prototype
    - [https://javascript.plainenglish.io/prototype-this-stranger-7a444098cdd4](https://javascript.plainenglish.io/prototype-this-stranger-7a444098cdd4)<br>
    - [https://blog.youteee.codes/introduction-to-javascript-prototypes](https://blog.youteee.codes/introduction-to-javascript-prototypes)<br>
    - [https://www.freecodecamp.org/news/all-you-need-to-know-to-understand-javascripts-prototype-a2bff2d28f03/](https://www.freecodecamp.org/news/all-you-need-to-know-to-understand-javascripts-prototype-a2bff2d28f03/)<br>
    - [https://bytecodepandit.medium.com/prototype-inheritance-in-javascript-866933b86714](https://bytecodepandit.medium.com/prototype-inheritance-in-javascript-866933b86714)<br>
    - [https://javascript.plainenglish.io/javascript-prototypes-in-plain-english-305781fbd979](https://javascript.plainenglish.io/javascript-prototypes-in-plain-english-305781fbd979)<br>
    - [https://levelup.gitconnected.com/javascripts-proto-vs-prototype-a21ec7f25bc1](https://levelup.gitconnected.com/javascripts-proto-vs-prototype-a21ec7f25bc1)<br>
    - [https://medium.com/@farazahmad0516/basic-javascript-javascript-for-beginners-part-1-1bbaff7b3124(https://medium.com/@farazahmad0516/basic-javascript-javascript-for-beginners-part-1-1bbaff7b3124)<br>
    - [https://dev.to/smpnjn/javascript-shallow-copy-what-is-a-shallow-copy-1pc5](https://dev.to/smpnjn/javascript-shallow-copy-what-is-a-shallow-copy-1pc5)<br>

- ### Functions
    - [https://blog.bitsrc.io/understanding-javascript-iifes-like-a-boss-b84b39663a37](https://blog.bitsrc.io/understanding-javascript-iifes-like-a-boss-b84b39663a37)<br/>
    - [https://api.daily.dev/r/Wxk7uYQ2p](https://api.daily.dev/r/Wxk7uYQ2p)<br >
    - [https://devdojo.com/rahulism/what-is-memoization-in-javascript](https://devdojo.com/rahulism/what-is-memoization-in-javascript)<br>
    - [https://yuricodesbot.hashnode.dev/understanding-functional-programming-in-javascript](https://yuricodesbot.hashnode.dev/understanding-functional-programming-in-javascript)<br>
    - [https://dev.to/thedailytechtalk/top-10-must-know-javascript-functions-1ipm](https://dev.to/thedailytechtalk/top-10-must-know-javascript-functions-1ipm)<br>
    - [https://medium.com/javascript-in-plain-english/javascript-interview-questions-functions-5a3081c1f3f5](https://medium.com/javascript-in-plain-english/javascript-interview-questions-functions-5a3081c1f3f5)<br>
    - [https://dev.to/mpodlasin/functional-programming-in-js-part-i-composition-currying-lodash-and-ramda-1ohb](https://dev.to/mpodlasin/functional-programming-in-js-part-i-composition-currying-lodash-and-ramda-1ohb)<br>
    - [https://mohit-codes.hashnode.dev/differences-between-arrow-function-and-regular-function-in-javascript](https://mohit-codes.hashnode.dev/differences-between-arrow-function-and-regular-function-in-javascript)<br>
    - [https://dev.to/coderslang/javascript-interview-question-46-length-of-js-functions-494f](https://dev.to/coderslang/javascript-interview-question-46-length-of-js-functions-494f)<br>
    - [https://blog.logrocket.com/understanding-javascript-currying/](https://blog.logrocket.com/understanding-javascript-currying/)<br>
    - [https://enlear.academy/replace-filter-map-sort-whatever-with-array-reduce-2bc3342f474d](https://enlear.academy/replace-filter-map-sort-whatever-with-array-reduce-2bc3342f474d)<br>
    - [https://www.freecodecamp.org/news/javascript-array-filter-tutorial-how-to-iterate-through-elements-in-an-array/](https://www.freecodecamp.org/news/javascript-array-filter-tutorial-how-to-iterate-through-elements-in-an-array/)<br>
    - [https://www.ma-no.org/en/programming/javascript/difference-between-arrow-and-normal-functions-in-javascript](https://www.ma-no.org/en/programming/javascript/difference-between-arrow-and-normal-functions-in-javascript)<br>
    - [https://dev.to/aravsanj/everything-you-need-to-know-about-javascript-functions-cmn](https://dev.to/aravsanj/everything-you-need-to-know-about-javascript-functions-cmn)<br>
    - [https://itnext.io/write-better-javascript-function-composition-with-pipe-and-compose-93cc39ab16ee](https://itnext.io/write-better-javascript-function-composition-with-pipe-and-compose-93cc39ab16ee)<br>
    - [https://dev.to/abhishek_rath/functions-in-javascript-56if](https://dev.to/abhishek_rath/functions-in-javascript-56if)<br>
    - [https://dev.to/trezeguit/functional-programming-with-js-1bgd](https://dev.to/trezeguit/functional-programming-with-js-1bgd)<br>
    - [https://javascript.plainenglish.io/how-to-write-clean-javascript-code-with-functional-programming-54fd60a56074](https://javascript.plainenglish.io/how-to-write-clean-javascript-code-with-functional-programming-54fd60a56074)<br>
    - [https://dev.to/j471n/some-javascript-methods-you-should-know-i15](https://dev.to/j471n/some-javascript-methods-you-should-know-i15)<br>
    - [https://enlear.academy/pure-vs-impure-function-395df7ce6acc](https://enlear.academy/pure-vs-impure-function-395df7ce6acc)<br>
    - [https://devdojo.com/rahulism/memoization-in-javascript-shorts](https://devdojo.com/rahulism/memoization-in-javascript-shorts)<br>
    - [https://dev.to/anishkumar/memoizing-fetch-api-calls-in-javascript-1d16](https://dev.to/anishkumar/memoizing-fetch-api-calls-in-javascript-1d16)<br>
    - [https://enlear.academy/javascript-function-types-8bde6a385b3e](https://enlear.academy/javascript-function-types-8bde6a385b3e)<br>
    - [https://devdojo.com/teri/what-is-memoization-in-javascript](https://devdojo.com/teri/what-is-memoization-in-javascript)<br>
    - [https://dev.to/rajshreevats/functions-in-js-before-learning-react-472b](https://dev.to/rajshreevats/functions-in-js-before-learning-react-472b)<br>
    - [https://dev.to/bamartindev/higher-order-functions-functional-composition-c7p](https://dev.to/bamartindev/higher-order-functions-functional-composition-c7p)<br>
    - [https://brayanarrieta.hashnode.dev/why-is-javascript-debounce-important-for-our-web-applications](https://brayanarrieta.hashnode.dev/why-is-javascript-debounce-important-for-our-web-applications)<br>
    - [https://rehansattar.dev/functional-programming-introduction](https://rehansattar.dev/functional-programming-introduction)<br>
    - [https://blog.greenroots.info/what-are-pure-functions-and-side-effects-in-javascript](https://blog.greenroots.info/what-are-pure-functions-and-side-effects-in-javascript)<br>
    - [https://blog.greenroots.info/higher-order-functions-in-javascript](https://blog.greenroots.info/higher-order-functions-in-javascript)<br>
    - [https://www.syncfusion.com/blogs/post/pure-and-impure-functions-in-javascript-a-complete-guide.aspx](https://www.syncfusion.com/blogs/post/pure-and-impure-functions-in-javascript-a-complete-guide.aspx)<br>
    - [https://dev.to/asapsonter/important-javascript-functions-you-have-to-know-to-be-a-better-developer-2if8](https://dev.to/asapsonter/important-javascript-functions-you-have-to-know-to-be-a-better-developer-2if8)<br>
    - [https://www.syncfusion.com/blogs/post/javascript-higher-order-functions-a-complete-guide.aspx](https://www.syncfusion.com/blogs/post/javascript-higher-order-functions-a-complete-guide.aspx)<br>
    - [https://hackernoon.com/understanding-first-class-and-higher-order-functions?source=rss](https://hackernoon.com/understanding-first-class-and-higher-order-functions?source=rss)<br>
    - [https://itnext.io/javascript-memory-management-how-to-avoid-common-memory-leaks-and-improve-performance-c018dbbca954](https://itnext.io/javascript-memory-management-how-to-avoid-common-memory-leaks-and-improve-performance-c018dbbca954)<br>

- ### Closure
    - [https://medium.com/geekculture/understanding-the-core-concept-of-javascript-closure-49e3517e49a5](https://medium.com/geekculture/understanding-the-core-concept-of-javascript-closure-49e3517e49a5)<br/>
    - [https://medium.com/geekculture/understanding-the-core-concept-of-javascript-closure-49e3517e49a5](https://medium.com/geekculture/understanding-the-core-concept-of-javascript-closure-49e3517e49a5)<br>
    - [https://medium.com/javascript-in-plain-english/closures-and-lexical-scoping-in-javascript-9ebe8d353662](https://medium.com/javascript-in-plain-english/closures-and-lexical-scoping-in-javascript-9ebe8d353662)<br>
    - [https://rajatexplains.hashnode.dev/understanding-closures-1](https://rajatexplains.hashnode.dev/understanding-closures-1)<br>
    - [https://www.freecodecamp.org/news/closures-in-javascript/](https://www.freecodecamp.org/news/closures-in-javascript/)<br>
    - [https://toaderdaniel.hashnode.dev/javascript-scopes-and-closures](https://toaderdaniel.hashnode.dev/javascript-scopes-and-closures)<br>
    - [https://javascript.plainenglish.io/closure-in-javascript-3f291eeb8dff](https://javascript.plainenglish.io/closure-in-javascript-3f291eeb8dff)<br>
    - [https://levelup.gitconnected.com/javascript-closures-eb6961375bbd](https://levelup.gitconnected.com/javascript-closures-eb6961375bbd)<br>
    - [https://javascript.plainenglish.io/how-to-use-javascript-closures-in-5-minutes-a28deddd3920](https://javascript.plainenglish.io/how-to-use-javascript-closures-in-5-minutes-a28deddd3920)<br>
    - [https://dev.to/elijahtrillionz/learn-javascript-closures-in-7-mins-324n?signin=true](https://dev.to/elijahtrillionz/learn-javascript-closures-in-7-mins-324n?signin=true)<br>
    - [https://flaviocopes.com/javascript-closures/](https://flaviocopes.com/javascript-closures/)<br>
    - [https://www.freecodecamp.org/news/javascript-closures-explained-with-example/](https://www.freecodecamp.org/news/javascript-closures-explained-with-example/)<br>
    - [https://webdriphashnode.hashnode.dev/hoisting-in-javascript-explained-visually](https://webdriphashnode.hashnode.dev/hoisting-in-javascript-explained-visually)<br>
    - [https://levelup.gitconnected.com/5-advanced-javascript-concepts-that-will-make-you-a-better-developer-5d04292107a1](https://levelup.gitconnected.com/5-advanced-javascript-concepts-that-will-make-you-a-better-developer-5d04292107a1)<br>

- ### Iterators
    - [https://madasamy.medium.com/explanation-about-iterators-and-generators-in-javascript-es6-f7e669cbe96e](https://madasamy.medium.com/explanation-about-iterators-and-generators-in-javascript-es6-f7e669cbe96e)<br>
    - [https://codeburst.io/a-simple-guide-to-es6-iterators-in-javascript-with-examples-189d052c3d8e](https://codeburst.io/a-simple-guide-to-es6-iterators-in-javascript-with-examples-189d052c3d8e)<br>
    - [https://blog.openreplay.com/deep-dive-into-javascript-s-iterators-iterables-and-generators](https://blog.openreplay.com/deep-dive-into-javascript-s-iterators-iterables-and-generators)<br>


- ### Currying
    - [https://dev.to/kozlovzxc/js-interview-in-2-minutes-currying-2hko](https://dev.to/kozlovzxc/js-interview-in-2-minutes-currying-2hko)<br/>
    - [https://dev.to/suprabhasupi/currying-in-javascript-1k3l](https://dev.to/suprabhasupi/currying-in-javascript-1k3l)<br/>
    - [https://daily.dev/posts/what-is-currying-in-javascript](https://daily.dev/posts/what-is-currying-in-javascript)<br>
    - [https://dev.to/afrazchelsea/function-currying-in-javascript-3h3g](https://dev.to/afrazchelsea/function-currying-in-javascript-3h3g)<br>
    - [https://code.tutsplus.com/tutorials/understanding-function-currying-in-javascript-and-when-to-use-it--cms-37867](https://code.tutsplus.com/tutorials/understanding-function-currying-in-javascript-and-when-to-use-it--cms-37867)<br>
    - [https://www.freecodecamp.org/news/how-to-use-currying-and-composition-in-javascript/](https://www.freecodecamp.org/news/how-to-use-currying-and-composition-in-javascript/)<br>
    - [https://javascript.plainenglish.io/javascript-currying-practical-example-512cf1099e81](https://javascript.plainenglish.io/javascript-currying-practical-example-512cf1099e81)<br>
    - [https://www.freecodecamp.org/news/how-to-use-currying-and-composition-in-javascript/](https://www.freecodecamp.org/news/how-to-use-currying-and-composition-in-javascript/)<br>
    - [https://javascript.plainenglish.io/javascript-currying-practical-example-512cf1099e81](https://javascript.plainenglish.io/javascript-currying-practical-example-512cf1099e81)<br>
    - [https://devdojo.com/rahulism/currying-in-js-shorts](https://devdojo.com/rahulism/currying-in-js-shorts)<br>
    - [https://javascript.plainenglish.io/enhance-react-onclick-handlers-with-currying-9c3c9ca82df3](https://javascript.plainenglish.io/enhance-react-onclick-handlers-with-currying-9c3c9ca82df3)<br>


- ### Promises
    - [https://towardsdev.com/promises-in-javascript-285f523c3e8d](https://towardsdev.com/promises-in-javascript-285f523c3e8d)<br/>
    - [https://javascript.plainenglish.io/what-is-the-importance-of-using-async-await-17b95870a05f](https://javascript.plainenglish.io/what-is-the-importance-of-using-async-await-17b95870a05f)<br/>
    - [https://dmitripavlutin.com/what-is-javascript-promise/](https://dmitripavlutin.com/what-is-javascript-promise/)<br>
    - [https://dmitripavlutin.com/javascript-promises-then-vs-then-catch/](https://dmitripavlutin.com/javascript-promises-then-vs-then-catch/)<br>
    - [https://enlear.academy/what-is-asynchronous-javascript-310426783ef1](https://enlear.academy/what-is-asynchronous-javascript-310426783ef1)<br>
    - [https://saiteja0413.hashnode.dev/beginners-guide-to-javascripts-asyncawait](https://saiteja0413.hashnode.dev/beginners-guide-to-javascripts-asyncawait)<br>
    - [https://www.freecodecamp.org/news/how-to-deal-with-nested-callbacks-and-avoid-callback-hell-1bc8dc4a2012/](https://www.freecodecamp.org/news/how-to-deal-with-nested-callbacks-and-avoid-callback-hell-1bc8dc4a2012/)<br>
    - [https://blog.openreplay.com/the-ultimate-guide-to-fixing-javascript-performance-problems-in-browser-devtools](https://blog.openreplay.com/the-ultimate-guide-to-fixing-javascript-performance-problems-in-browser-devtools)<br>
    - [https://maximorlov.com/visual-guide-refactoring-callback-functions/](https://maximorlov.com/visual-guide-refactoring-callback-functions/)<br>
    - [https://codeburst.io/javascript-interview-questions-promises-1ab2fb7f0467](https://codeburst.io/javascript-interview-questions-promises-1ab2fb7f0467)<br>
    - [https://blog.madza.dev/24-modern-es6-code-snippets-to-solve-practical-js-problems](https://blog.madza.dev/24-modern-es6-code-snippets-to-solve-practical-js-problems)<br>
    - [https://humanwhocodes.com/blog/2020/10/creating-javascript-promise-from-scratch-promise-resolve-reject/](https://humanwhocodes.com/blog/2020/10/creating-javascript-promise-from-scratch-promise-resolve-reject/)<br>
    - [https://blog.bitsrc.io/journey-from-callbacks-to-promises-to-async-await-6fcd7f7fa3c5](https://blog.bitsrc.io/journey-from-callbacks-to-promises-to-async-await-6fcd7f7fa3c5)<br>
    - [https://blog.rohilpinto.com/javascript-call-stack-explained](https://blog.rohilpinto.com/javascript-call-stack-explained)<br>
    - [https://dev.to/ryanameri/mastering-hard-parts-of-javascript-callbacks-i-3aj0](https://dev.to/ryanameri/mastering-hard-parts-of-javascript-callbacks-i-3aj0)<br>
    - [https://adrianmejia.com/promises-tutorial-concurrency-in-javascript-node/](https://adrianmejia.com/promises-tutorial-concurrency-in-javascript-node/)<br>
    - [https://dev.to/swarnaliroy94/javascript-concept-of-promise-3ijb](https://dev.to/swarnaliroy94/javascript-concept-of-promise-3ijb)<br>
    - [https://enlear.academy/what-is-asynchronous-javascript-310426783ef1](https://enlear.academy/what-is-asynchronous-javascript-310426783ef1)<br>
    - [https://www.freecodecamp.org/news/what-is-promise-in-javascript-for-beginners/](https://www.freecodecamp.org/news/what-is-promise-in-javascript-for-beginners/)<br>
    - [https://www.freecodecamp.org/news/async-await-javascript-tutorial-explained-by-making-pizza/](https://www.freecodecamp.org/news/async-await-javascript-tutorial-explained-by-making-pizza/)<br>
    - [https://www.freecodecamp.org/news/synchronous-vs-asynchronous-in-javascript/](https://www.freecodecamp.org/news/synchronous-vs-asynchronous-in-javascript/)<br>
    - [https://dev.to/jrdev_/how-to-display-the-progress-of-promises-in-javascript-lh0](https://dev.to/jrdev_/how-to-display-the-progress-of-promises-in-javascript-lh0)<br>
    - [https://saharanitaa.hashnode.dev/introduction-to-promises-and-async-and-await-promises-in-javascript](https://saharanitaa.hashnode.dev/introduction-to-promises-and-async-and-await-promises-in-javascript)<br>
    - [https://javascript.plainenglish.io/demystifying-javascript-arrow-functions-7b2a0908a2b3](https://javascript.plainenglish.io/demystifying-javascript-arrow-functions-7b2a0908a2b3)<br>
    - [https://dev.to/shadid12/how-to-use-async-await-inside-loops-in-javascript-4dlg](https://dev.to/shadid12/how-to-use-async-await-inside-loops-in-javascript-4dlg)<br>
    - [https://dev.to/santan47/promise-async-await-in-javascript-mlb](https://dev.to/santan47/promise-async-await-in-javascript-mlb)<br>
    - [https://www.simplilearn.com/tutorials/javascript-tutorial/javascript-promise](https://www.simplilearn.com/tutorials/javascript-tutorial/javascript-promise)<br>
    - [https://dev.to/ditdot/quiz-how-well-do-you-understand-asynchronous-javascript-5e4j](https://dev.to/ditdot/quiz-how-well-do-you-understand-asynchronous-javascript-5e4j)<br>
    - [https://blog.greenroots.info/common-mistakes-in-using-javascript-promises](https://blog.greenroots.info/common-mistakes-in-using-javascript-promises)<br>
    - [https://itnext.io/the-evolution-of-asynchronous-patterns-in-javascript-64efc8938b16](https://itnext.io/the-evolution-of-asynchronous-patterns-in-javascript-64efc8938b16)<br>
    - [https://devdojo.com/rahulism/javascript-promises-all-you-need-to-know-about](https://devdojo.com/rahulism/javascript-promises-all-you-need-to-know-about)<br>
    - [https://sayitaditya.hashnode.dev/this-in-javascript-part-one](https://sayitaditya.hashnode.dev/this-in-javascript-part-one)<br>
    - [https://blog.greenroots.info/javascript-async-and-await-in-plain-english-please](https://blog.greenroots.info/javascript-async-and-await-in-plain-english-please)<br>
    - [https://www.freecodecamp.org/news/nodejs-eventloop-tutorial/](https://www.freecodecamp.org/news/nodejs-eventloop-tutorial/)<br>
    - [https://javascript.plainenglish.io/how-to-set-javascript-promise-timeout-7d51c87bc38e](https://javascript.plainenglish.io/how-to-set-javascript-promise-timeout-7d51c87bc38e)<br>
    - [https://devdojo.com/imkarthikeyans/javascript-call-stack-event-loop-and-callback-queue](https://devdojo.com/imkarthikeyans/javascript-call-stack-event-loop-and-callback-queue)<br>
    - [https://afunni.hashnode.dev/a-meeting-with-asynchronous-javascript-promises-and-fetch-requests](https://afunni.hashnode.dev/a-meeting-with-asynchronous-javascript-promises-and-fetch-requests)<br>
    - [https://blog.bitsrc.io/5-common-mistakes-in-using-promises-bfcc4d62657f](https://blog.bitsrc.io/5-common-mistakes-in-using-promises-bfcc4d62657f)<br>
    - [https://javascript.plainenglish.io/what-is-javascript-promise-7b5e03d06bdf](https://javascript.plainenglish.io/what-is-javascript-promise-7b5e03d06bdf)<br>
    - [https://www.freecodecamp.org/news/asynchronous-javascript-explained/](https://www.freecodecamp.org/news/asynchronous-javascript-explained/)<br>
    - [https://dev.to/klc/understanding-javascript-promises-1hp1](https://dev.to/klc/understanding-javascript-promises-1hp1)<br>
    - [https://dev.to/veronikasimic_56/the-ultimate-guide-to-asnyc-javascript-3lg5](https://dev.to/veronikasimic_56/the-ultimate-guide-to-asnyc-javascript-3lg5)<br>
    - [https://www.freecodecamp.org/news/asynchronous-programming-in-javascript/](https://www.freecodecamp.org/news/asynchronous-programming-in-javascript/)<br>
    - [https://betterprogramming.pub/understanding-the-javascript-call-stack-through-illustrations-66156222ff86](https://betterprogramming.pub/understanding-the-javascript-call-stack-through-illustrations-66156222ff86)<br>


- ### Es6+
    - [https://madzadev.medium.com/24-modern-es6-code-snippets-to-solve-practical-js-problems-3609f301859e](https://madzadev.medium.com/24-modern-es6-code-snippets-to-solve-practical-js-problems-3609f301859e)<br/>
    - [https://ponyfoo.com/articles/es6](https://ponyfoo.com/articles/es6)<br/>
    - [https://mezgitci9.medium.com/java-script-es6-f6f4219847dd](https://mezgitci9.medium.com/java-script-es6-f6f4219847dd)<br>
    - [https://madasamy.medium.com/javascript-brief-history-and-ecmascript-es6-es7-es8-features-673973394df4](https://madasamy.medium.com/javascript-brief-history-and-ecmascript-es6-es7-es8-features-673973394df4)<br>
    - [https://alimammiya.hashnode.dev/upcoming-interesting-javascript-es2021-es12-features-to-look-for-1](https://alimammiya.hashnode.dev/upcoming-interesting-javascript-es2021-es12-features-to-look-for-1)<br>
    - [https://jayakiran.hashnode.dev/modern-javascript](https://jayakiran.hashnode.dev/modern-javascript)<br>
    - [https://medium.com/nerd-for-tech/understanding-javascript-es6-classes-dbce09c0b903](https://medium.com/nerd-for-tech/understanding-javascript-es6-classes-dbce09c0b903)<br>
    - [https://alimammiya.hashnode.dev/8-useful-javascript-es2019-features-to-know-about-1](https://alimammiya.hashnode.dev/8-useful-javascript-es2019-features-to-know-about-1)<br>
    - [https://shineve.hashnode.dev/new-javascript-features-in-es6-es12](https://shineve.hashnode.dev/new-javascript-features-in-es6-es12)<br>
    - [https://madzadev.medium.com/24-modern-es6-code-snippets-to-solve-practical-js-problems-3609f301859e](https://madzadev.medium.com/24-modern-es6-code-snippets-to-solve-practical-js-problems-3609f301859e)<br>
    - [https://ponyfoo.com/articles/search/es6](https://ponyfoo.com/articles/search/es6https://ponyfoo.com/articles/es6)<br>
    - [https://madza.hashnode.dev/24-modern-es6-code-snippets-to-solve-practical-js-problems](https://madza.hashnode.dev/24-modern-es6-code-snippets-to-solve-practical-js-problems)<br>
    - [https://blog.greenroots.info/explain-me-like-i-am-five-what-are-es6-symbols-ckeuz5sb8001qafs14of305dw](https://blog.greenroots.info/explain-me-like-i-am-five-what-are-es6-symbols-ckeuz5sb8001qafs14of305dw)<br>
    - [https://blog.michaelkaren.dev/javascript-spread-vs-rest](https://blog.michaelkaren.dev/javascript-spread-vs-rest)<br>
    - [https://medium.com/javascript-in-plain-english/new-javascript-features-in-es2020-c2d76acf9c5a](https://medium.com/javascript-in-plain-english/new-javascript-features-in-es2020-c2d76acf9c5a)<br>
    - [https://blog.bitsrc.io/mastering-javascript-es6-symbols-6453da3bd46c](https://blog.bitsrc.io/mastering-javascript-es6-symbols-6453da3bd46c)<br>
    - [https://blog.skay.dev/es6-understanding-destructuring](https://blog.skay.dev/es6-understanding-destructuring)<br>
    - [https://medium.com/@etherealm/named-export-vs-default-export-in-es6-affb483a0910](https://medium.com/@etherealm/named-export-vs-default-export-in-es6-affb483a0910)<br>
    - [https://medium.com/javascript-in-plain-english/5-simple-tips-to-write-better-arrow-functions-a55f40f63d58](https://medium.com/javascript-in-plain-english/5-simple-tips-to-write-better-arrow-functions-a55f40f63d58)<br>
    - [https://blog.saeloun.com/2021/08/26/es2021-replaceall-numeric-separator](https://blog.saeloun.com/2021/08/26/es2021-replaceall-numeric-separator)<br>
    - [https://devdojo.com/shreya/es6-handbook#arrow-functions](https://devdojo.com/shreya/es6-handbook#arrow-functions)<br>
    - [https://dev.to/justmyrealname/javascript-from-es6-to-today-c42](https://dev.to/justmyrealname/javascript-from-es6-to-today-c42)<br>
    - [https://dev.to/thatanjan/everything-you-need-to-know-about-javascript-destructuring-30e5](https://dev.to/thatanjan/everything-you-need-to-know-about-javascript-destructuring-30e5)<br>
    - [https://faheemkhan97.hashnode.dev/es6-a-guide-you-must-go-through-before-learning-react](https://faheemkhan97.hashnode.dev/es6-a-guide-you-must-go-through-before-learning-react)<br>
    - [https://dev.to/stefanwrightcodes/es6-a-beginners-guide-following-my-own-learning-4e05](https://dev.to/stefanwrightcodes/es6-a-beginners-guide-following-my-own-learning-4e05)<br>
    - [https://levelup.gitconnected.com/top-5-javascript-es12-features-you-should-start-using-now-b16a8b5353b1](https://levelup.gitconnected.com/top-5-javascript-es12-features-you-should-start-using-now-b16a8b5353b1)<br>
    - [https://www.positronx.io/javascript-ecmascript-quick-sort-algorithm-tutorial/](https://www.positronx.io/javascript-ecmascript-quick-sort-algorithm-tutorial/)<br>
    - [https://p42.ai/blog/2021-12-31/es2022-preview-10-exciting-javascript-language-features-from-2021](https://p42.ai/blog/2021-12-31/es2022-preview-10-exciting-javascript-language-features-from-2021)<br>
    - [https://dev.to/wordssaysalot/es6-way-of-coding-javascript-2kl2](https://dev.to/wordssaysalot/es6-way-of-coding-javascript-2kl2)<br>
    - [https://wordssaysalot.hashnode.dev/es6-way-of-coding-javascript](https://wordssaysalot.hashnode.dev/es6-way-of-coding-javascript)<br>
    - [https://wordssaysalot.hashnode.dev/es6-way-of-coding-javascript#ckxpje048002xe3s15ruw3t80](https://wordssaysalot.hashnode.dev/es6-way-of-coding-javascript#ckxpje048002xe3s15ruw3t80)<br>
    - [https://www.30secondsofcode.org/articles/s/js-async-defer](https://www.30secondsofcode.org/articles/s/js-async-defer)<br>
    - [https://medium.com/@bluetch/javascript-es6-es7-es8-es9-es10-es11-and-es12-519d8be7d48c](https://medium.com/@bluetch/javascript-es6-es7-es8-es9-es10-es11-and-es12-519d8be7d48c)<br>
    - [https://dev.to/naubit/5-advanced-es6-features-every-javascript-developer-should-master-3mkn](https://dev.to/naubit/5-advanced-es6-features-every-javascript-developer-should-master-3mkn)<br>


- ### Array
    - [https://www.freecodecamp.org/news/array-map-tutorial/](https://www.freecodecamp.org/news/array-map-tutorial/)<br/>
    - [https://dev.to/antoomartini/4-ways-to-convert-a-string-to-an-array-in-javascript-i97](https://dev.to/antoomartini/4-ways-to-convert-a-string-to-an-array-in-javascript-i97)<br/>
    - [https://www.freecodecamp.org/news/the-javascript-array-handbook/](https://www.freecodecamp.org/news/the-javascript-array-handbook/)<br>
    - [https://blog.greenroots.info/everything-you-need-to-know-about-javascript-set](https://blog.greenroots.info/everything-you-need-to-know-about-javascript-set)<br>
    - [https://faheemkhan97.hashnode.dev/arraylength-i-bet-youre-missing-something-about-it](https://faheemkhan97.hashnode.dev/arraylength-i-bet-youre-missing-something-about-it)<br>
    - [https://iampalash.hashnode.dev/top-7-javascript-array-sort-method-use-cases](https://iampalash.hashnode.dev/top-7-javascript-array-sort-method-use-cases)<br>
    - [https://amantyagi.hashnode.dev/javascript-array-methods](https://amantyagi.hashnode.dev/javascript-array-methods)<br>
    - [https://blog.bitsrc.io/8-methods-to-search-javascript-arrays-fadbce8bea51](https://blog.bitsrc.io/8-methods-to-search-javascript-arrays-fadbce8bea51)<br>
    - [https://www.w3resource.com/javascript-exercises/javascript-array-exercises.php](https://www.w3resource.com/javascript-exercises/javascript-array-exercises.php)<br>
    - [https://javascript.info/array-methods](https://javascript.info/array-methods)<br>
    - [https://dev.to/aashrithashiva29/possible-ways-of-iterating-arrays-in-javascript-1cgo](https://dev.to/aashrithashiva29/possible-ways-of-iterating-arrays-in-javascript-1cgo)<br>
    - [https://thenextweb.com/syndication/2020/07/02/15-useful-methods-to-get-the-most-out-of-javascript-arrays/](https://thenextweb.com/syndication/2020/07/02/15-useful-methods-to-get-the-most-out-of-javascript-arrays/)<br>
    - [https://dev.to/samanthaming/6-use-cases-of-spread-with-array-in-javascript-2n53](https://dev.to/samanthaming/6-use-cases-of-spread-with-array-in-javascript-2n53)<br>
    - [https://www.freecodecamp.org/news/javascript-array-foreach-tutorial-how-to-iterate-through-elements-in-an-array-with-map/](https://www.freecodecamp.org/news/javascript-array-foreach-tutorial-how-to-iterate-through-elements-in-an-array-with-map/)<br>
    - [https://dev.to/insha/javascript-array-and-its-methods-432k](https://dev.to/insha/javascript-array-and-its-methods-432k)<br>
    - [https://enlear.academy/how-to-write-better-javascript-code-with-foreach-and-reduce-415a1d58195](https://enlear.academy/how-to-write-better-javascript-code-with-foreach-and-reduce-415a1d58195)<br>
    - [https://www.sitepoint.com/javascript-for-in-loop-basics/](https://www.sitepoint.com/javascript-for-in-loop-basics/)<br>
    - [https://javascript.plainenglish.io/lets-deduce-the-reduce-method-in-javascript-bdc828f368a2](https://javascript.plainenglish.io/lets-deduce-the-reduce-method-in-javascript-bdc828f368a2)<br>
    - [https://dmitripavlutin.com/javascript-sparse-dense-arrays/](https://dmitripavlutin.com/javascript-sparse-dense-arrays/)<br>
    - [https://thecodingcompany.hashnode.dev/15-useful-javascript-array-methods-you-might-not-be-using](https://thecodingcompany.hashnode.dev/15-useful-javascript-array-methods-you-might-not-be-using)<br>
    - [https://www.ma-no.org/en/programming/javascript/how-to-reverse-an-array-in-javascript](https://www.ma-no.org/en/programming/javascript/how-to-reverse-an-array-in-javascript)<br>
    - [https://www.freecodecamp.org/news/javascript-destructuring-and-spread-operator-explained/](https://www.freecodecamp.org/news/javascript-destructuring-and-spread-operator-explained/)<br>
    - [https://devdojo.com/nisargkapkar/eli5-javascript-the-spread-operator](https://devdojo.com/nisargkapkar/eli5-javascript-the-spread-operator)<br>
    - [https://dmitripavlutin.com/remove-object-property-javascript/](https://dmitripavlutin.com/remove-object-property-javascript/)<br>
    - [https://javascript.plainenglish.io/what-are-javascript-arrays-20a45a108ad1](https://javascript.plainenglish.io/what-are-javascript-arrays-20a45a108ad1)<br>
    - [https://devdojo.com/rahulism/map-in-js-shorts](https://devdojo.com/rahulism/map-in-js-shorts)<br>
    - [https://sumudusiriwardana.hashnode.dev/javascript-arrays-explain-like-im-five](https://sumudusiriwardana.hashnode.dev/javascript-arrays-explain-like-im-five)<br>
    - [https://harshsinghatz.hashnode.dev/map-filter-and-reduce-in-javascript-under-5-minutes](https://harshsinghatz.hashnode.dev/map-filter-and-reduce-in-javascript-under-5-minutes)<br>
    - [https://dev.to/mahamatmans/array-cheatsheet-javascript-3mci](https://dev.to/mahamatmans/array-cheatsheet-javascript-3mci)<br>
    - [https://turriate.com/articles/modern-javascript-everything-you-missed-over-10-years?ck_subscriber_id=1519802657#array-functions](https://turriate.com/articles/modern-javascript-everything-you-missed-over-10-years?ck_subscriber_id=1519802657#array-functions)<br>
    - [https://www.javascripttutorial.net/javascript-array-sort/](https://www.javascripttutorial.net/javascript-array-sort/)<br>
    - []()<br>


- ### Event Loop
    - [https://ayushv.medium.com/event-loop-in-javascript-672c07618dc9](https://ayushv.medium.com/event-loop-in-javascript-672c07618dc9)<br>
    - [https://towardsdev.com/event-loop-in-javascript-672c07618dc9](https://towardsdev.com/event-loop-in-javascript-672c07618dc9)<br>
    - [https://medium.com/@ricardoreis_22930/event-loop-javascript-4376600e5603](https://medium.com/@ricardoreis_22930/event-loop-javascript-4376600e5603)<br>
    - [https://blog.skay.dev/javascript-event-loop-explained](https://blog.skay.dev/javascript-event-loop-explained)<br>
    - [https://dmitripavlutin.com/javascript-event-delegation/?utm_campaign=a-simple-explanation-of-event-delegation](https://dmitripavlutin.com/javascript-event-delegation/?utm_campaign=a-simple-explanation-of-event-delegation)<br>
    - [https://blog.bitsrc.io/event-bubbling-and-capturing-in-javascript-6bc908321b22](https://blog.bitsrc.io/event-bubbling-and-capturing-in-javascript-6bc908321b22)<br>
    - [https://web.dev/eventing-deepdive/](https://web.dev/eventing-deepdive/)<br>
    - [https://bytecodepandit.medium.com/5-min-to-understand-event-loop-in-javascript-ead521e88260](https://bytecodepandit.medium.com/5-min-to-understand-event-loop-in-javascript-ead521e88260)<br>
    - [https://javascript.plainenglish.io/event-loop-in-javascript-how-javascript-works-51c7bd73f07](https://javascript.plainenglish.io/event-loop-in-javascript-how-javascript-works-51c7bd73f07)<br>
    - [https://dev.to/lydiahallie/javascript-visualized-event-loop-3dif](https://dev.to/lydiahallie/javascript-visualized-event-loop-3dif)<br>
    - [https://devdojo.com/posandu/16-javascript-snippets-to-save-your-time](https://devdojo.com/posandu/16-javascript-snippets-to-save-your-time)<br>
    - [https://www.freecodecamp.org/news/event-bubbling-in-javascript/](https://www.freecodecamp.org/news/event-bubbling-in-javascript/)<br>
    - [https://dev.to/nodedoctors/an-animated-guide-to-nodejs-event-loop-3g62](https://dev.to/nodedoctors/an-animated-guide-to-nodejs-event-loop-3g62)<br>
    - [https://dev.to/rammcodes/i-created-an-animation-in-5-hours-to-understand-the-event-loop-in-javascript-1idi](https://dev.to/rammcodes/i-created-an-animation-in-5-hours-to-understand-the-event-loop-in-javascript-1idi)<br>

- ### Objects
    - [https://livecodestream.dev/post/everything-you-should-know-about-javascript-dictionaries/](https://livecodestream.dev/post/everything-you-should-know-about-javascript-dictionaries/)<br/>
    - [https://towardsdev.com/object-oriented-programming-oop-in-javascript-b7f2bbde1230?gi=6355f0d7bfa0](https://towardsdev.com/object-oriented-programming-oop-in-javascript-b7f2bbde1230?gi=6355f0d7bfa0)<br>
    - [https://towardsdev.com/object-oriented-programming-oop-in-javascript-b7f2bbde1230](https://towardsdev.com/object-oriented-programming-oop-in-javascript-b7f2bbde1230)<br>
    - [https://javascript.plainenglish.io/copies-of-javascript-shallow-and-deep-copy-ac7f8dcd1dd0](https://javascript.plainenglish.io/copies-of-javascript-shallow-and-deep-copy-ac7f8dcd1dd0)<br>
    - [https://javascript.plainenglish.io/object-oriented-javascript-3f74e02a436f](https://javascript.plainenglish.io/object-oriented-javascript-3f74e02a436f)<br>
    - [https://cosmocode.io/how-to-implement-abstraction-in-javascript-javascript-object-oriented-programming/](https://cosmocode.io/how-to-implement-abstraction-in-javascript-javascript-object-oriented-programming/)<br>
    - [https://javascript.plainenglish.io/what-is-proto-b15f16e10b72](https://javascript.plainenglish.io/what-is-proto-b15f16e10b72)<br>
    - [https://javascript.plainenglish.io/proto-vs-prototype-in-js-140b9b9c8cd5](https://javascript.plainenglish.io/proto-vs-prototype-in-js-140b9b9c8cd5)<br>
    - [https://javascript.plainenglish.io/javascript-paas-by-value-vs-reference-b1667016e4a3](https://javascript.plainenglish.io/javascript-paas-by-value-vs-reference-b1667016e4a3)<br>
    - [https://favouritejome.hashnode.dev/class-prototype-and-oop-concept-explained](https://favouritejome.hashnode.dev/class-prototype-and-oop-concept-explained)<br>
    - [https://css-tricks.com/the-flavors-of-object-oriented-programming-in-javascript/](https://css-tricks.com/the-flavors-of-object-oriented-programming-in-javascript/)<br>
    - [https://blog.oshogunle.com/how-to-use-oop-in-javascript-ckemxzcw804ow8cs122ikhob0](https://blog.oshogunle.com/how-to-use-oop-in-javascript-ckemxzcw804ow8cs122ikhob0)<br>
    - [https://h.daily-dev-tips.com/javascript-optional-chaining-to-the-rescue](https://h.daily-dev-tips.com/javascript-optional-chaining-to-the-rescue)<br>
    - [https://devdojo.com/rahulism/classes-in-javascript-short-yet-smart-guide](https://devdojo.com/rahulism/classes-in-javascript-short-yet-smart-guide)<br>
    - [https://dev.to/jrmatanda/master-objects-in-js-part-1-41hk](https://dev.to/jrmatanda/master-objects-in-js-part-1-41hk)<br>
    - [https://suprabhasupi.hashnode.dev/object-equality-in-javascript](https://suprabhasupi.hashnode.dev/object-equality-in-javascript)<br>
    - [https://dev.to/antoomartini/differences-between-object-freeze-and-object-seal-in-javascript-n11](https://dev.to/antoomartini/differences-between-object-freeze-and-object-seal-in-javascript-n11)<br>
    - [https://nehalmahida.hashnode.dev/oops-in-javascript-with-easy-to-understand-examples](https://nehalmahida.hashnode.dev/oops-in-javascript-with-easy-to-understand-examples)<br>
    - [https://www.freecodecamp.org/news/javascript-classes-how-they-work-with-use-case/](https://www.freecodecamp.org/news/javascript-classes-how-they-work-with-use-case/)<br>
    - [https://devdojo.com/rahulism/shallow-copy-and-deep-copy-in-js](https://devdojo.com/rahulism/shallow-copy-and-deep-copy-in-js)<br>
    - [https://www.freecodecamp.org/news/object-oriented-javascript-for-beginners/](https://www.freecodecamp.org/news/object-oriented-javascript-for-beginners/)<br>
    - [https://www.freecodecamp.org/news/understand-call-apply-and-bind-in-javascript-with-examples/](https://www.freecodecamp.org/news/understand-call-apply-and-bind-in-javascript-with-examples/)<br>
    - [https://dev.to/swastikyadav/understand-call-apply-and-bind-functions-in-javascript-like-never-before-575e](https://dev.to/swastikyadav/understand-call-apply-and-bind-functions-in-javascript-like-never-before-575e)<br>

- ### String
    - [https://dev.to/satishnaikawadi2001/15-very-important-javascript-string-methods-every-developer-should-know-1apb](https://dev.to/satishnaikawadi2001/15-very-important-javascript-string-methods-every-developer-should-know-1apb)<br>
    - [https://dmitripavlutin.com/javascript-string-trim/](https://dmitripavlutin.com/javascript-string-trim/)<br>
    - [https://www.freecodecamp.org/news/efficient-string-building-in-javascript/](https://www.freecodecamp.org/news/efficient-string-building-in-javascript/)<br>
    - [https://www.freecodecamp.org/news/javascript-string-to-boolean/](https://www.freecodecamp.org/news/javascript-string-to-boolean/)<br>
- ### Date and time
    - [https://www.freecodecamp.org/news/how-to-build-a-chess-clock-with-javascript-and-setinterval/](https://www.freecodecamp.org/news/how-to-build-a-chess-clock-with-javascript-and-setinterval/)<br>
    - [https://dev.to/debs_obrien/formatting-a-date-in-javascript-ebd](https://dev.to/debs_obrien/formatting-a-date-in-javascript-ebd)<br>
    - [https://blog.bitsrc.io/how-to-handle-time-zones-in-javascript-b135a7931453](https://blog.bitsrc.io/how-to-handle-time-zones-in-javascript-b135a7931453)<br>
    - [https://dev.to/javascriptacademy/create-a-digital-clock-using-javascript-12d3](https://dev.to/javascriptacademy/create-a-digital-clock-using-javascript-12d3)<br>
    - [https://enlear.academy/how-to-create-an-analog-clock-with-javascript-css-d03c273abef5](https://enlear.academy/how-to-create-an-analog-clock-with-javascript-css-d03c273abef5)<br>

- ### Regex
    - [https://yuricodesbot.hashnode.dev/ultimate-guide-to-regular-expressions-regex-on-javascript](https://yuricodesbot.hashnode.dev/ultimate-guide-to-regular-expressions-regex-on-javascript)<br/>
    - [https://dev.to/shreyazz/regex-101-2m7m](https://dev.to/shreyazz/regex-101-2m7m)<br>
    - [https://javascript.plainenglish.io/seriously-javascript-regex-quantifiers-in-under-10-mins-f281146bfea2](https://javascript.plainenglish.io/seriously-javascript-regex-quantifiers-in-under-10-mins-f281146bfea2)<br>
    - [https://towardsdatascience.com/an-introduction-to-regular-expressions-5dd762afc5e4](https://towardsdatascience.com/an-introduction-to-regular-expressions-5dd762afc5e4)<br>
    - [https://amara.hashnode.dev/regular-expressions-in-javascript](https://amara.hashnode.dev/regular-expressions-in-javascript)<br>
    - [https://fireship.io/lessons/regex-cheat-sheet-js/](https://fireship.io/lessons/regex-cheat-sheet-js/)<br>
    - [https://blog.bitsrc.io/threats-of-using-regular-expressions-in-javascript-28ddccf5224c](https://blog.bitsrc.io/threats-of-using-regular-expressions-in-javascript-28ddccf5224c)<br>
    - [https://dev.to/jaspalsingh1998/regex-in-javascript-with-a-cool-project-2e6m](https://dev.to/jaspalsingh1998/regex-in-javascript-with-a-cool-project-2e6m)<br>
    - [https://dev.to/coderpad/the-complete-guide-to-regular-expressions-regex-1m6](https://dev.to/coderpad/the-complete-guide-to-regular-expressions-regex-1m6)<br>
    - [https://dev.to/coderpad/the-complete-guide-to-regular-expressions-regex-1m6](https://dev.to/coderpad/the-complete-guide-to-regular-expressions-regex-1m6)<br>

- ### Error Handling
    - [https://sruthicodes.hashnode.dev/all-about-errors-in-javascript](https://sruthicodes.hashnode.dev/all-about-errors-in-javascript)<br>
    - [https://blog.bitsrc.io/javascript-exception-handling-patterns-best-practices-f7d6fcab735d](https://blog.bitsrc.io/javascript-exception-handling-patterns-best-practices-f7d6fcab735d)<br>
    - [https://javascript.plainenglish.io/debug-faster-in-javascript-26d2ad3942d9](https://javascript.plainenglish.io/debug-faster-in-javascript-26d2ad3942d9)<br>
    - [https://dev.to/coderpad/the-complete-guide-to-regular-expressions-regex-1m6](https://dev.to/coderpad/the-complete-guide-to-regular-expressions-regex-1m6)<br>
    - [https://bhaktee.hashnode.dev/types-of-errors-in-javascript](https://bhaktee.hashnode.dev/types-of-errors-in-javascript)<br>

## `Javascript Style Guides`
- [https://enlear.academy/5-best-javascript-style-guides-640485e7b630](https://enlear.academy/5-best-javascript-style-guides-640485e7b630)<br/>
- [https://enlear.academy/how-to-set-up-airbnb-style-guide-82413ea6c5f2](https://enlear.academy/how-to-set-up-airbnb-style-guide-82413ea6c5f2)<br/>

## `Performance/Code Optimization`
- [https://blog.bitsrc.io/14-javascript-code-optimization-tips-for-front-end-developers-f878e4ea2314](https://blog.bitsrc.io/14-javascript-code-optimization-tips-for-front-end-developers-f878e4ea2314)<br/>
- [https://blog.bitsrc.io/using-web-workers-to-speed-up-javascript-applications-5c567f209bdb](https://blog.bitsrc.io/using-web-workers-to-speed-up-javascript-applications-5c567f209bdb)<br>
- [https://www.geeksforgeeks.org/7-tips-to-improve-javascript-performance/](https://www.geeksforgeeks.org/7-tips-to-improve-javascript-performance/)<br>
- [https://blog.bitsrc.io/measuring-performance-of-different-javascript-loop-types-c0e9b1d193ed](https://blog.bitsrc.io/measuring-performance-of-different-javascript-loop-types-c0e9b1d193ed)<br>
- [https://blog.bitsrc.io/9-best-practices-for-optimizing-frontend-loading-time-763211621061](https://blog.bitsrc.io/9-best-practices-for-optimizing-frontend-loading-time-763211621061)<br>


## `Javascript Interview Questions`
- [https://dev.to/capscode/500-javascript-question-answers-with-explanation-29im](https://dev.to/capscode/500-javascript-question-answers-with-explanation-29im)<br/>
- [https://github.com/ganqqwerty/123-Essential-JavaScript-Interview-Questions](https://github.com/ganqqwerty/123-Essential-JavaScript-Interview-Questions)<br/>
- [https://hemant.hashnode.dev/60-javascript-interview-questions](https://hemant.hashnode.dev/60-javascript-interview-questions)<br/>
- [https://codelifefitness.hashnode.dev/12-common-javascript-questions-i-used-to-ask-in-interview](https://codelifefitness.hashnode.dev/12-common-javascript-questions-i-used-to-ask-in-interview)<br/>
- [https://www.tutsmake.com/javascript-es6-interview-question-and-answer/](https://www.tutsmake.com/javascript-es6-interview-question-and-answer/)<br/>
- [https://www.geeksforgeeks.org/10-most-asked-es6-interview-questions-answers-for-developers/](https://www.geeksforgeeks.org/10-most-asked-es6-interview-questions-answers-for-developers/)<br/>
- [https://alimammiya.hashnode.dev/100-most-asked-javascript-interview-questions-and-answers-part-1](https://alimammiya.hashnode.dev/100-most-asked-javascript-interview-questions-and-answers-part-1)<br>
- [https://www.interviewbit.com/javascript-interview-questions/](https://www.interviewbit.com/javascript-interview-questions/)<br>
- [https://dev.to/angelomiranda/top-10-javascript-interview-questions-and-answers-you-should-know-junior-and-senior-3943](https://dev.to/angelomiranda/top-10-javascript-interview-questions-and-answers-you-should-know-junior-and-senior-3943)<br>
- [https://medium.com/javascript-in-plain-english/5-frontend-interview-questions-to-help-you-master-asynchronous-javascript-3339d0f89fdc](https://medium.com/javascript-in-plain-english/5-frontend-interview-questions-to-help-you-master-asynchronous-javascript-3339d0f89fdc)<br>
- [https://medium.com/swlh/javascript-practice-interview-af1e140eede0](https://medium.com/swlh/javascript-practice-interview-af1e140eede0)<br>
- [https://medium.com/javascript-in-plain-english/10-javascript-interview-question-c050a357161c](https://medium.com/javascript-in-plain-english/10-javascript-interview-question-c050a357161c)<br>
- [https://thedevpost.com/blog/10-most-asked-questions-about-javascript/](https://thedevpost.com/blog/10-most-asked-questions-about-javascript/)<br>
- [https://dev.to/nas5w/10-javascript-quiz-questions-and-answers-to-sharpen-your-skills-255m](https://dev.to/nas5w/10-javascript-quiz-questions-and-answers-to-sharpen-your-skills-255m)<br>
- [https://levelup.gitconnected.com/javascript-interview-questions-basic-dom-and-events-7925ce8602ef?source=email-7d5393e25aca-1600898631194-digest.reader------0-59------------------8be1a484_5a7d_41b3_8ac9_410210586401-1-f68eeeb0_1b52_418b_a7c5_14c9775bf642----](https://levelup.gitconnected.com/javascript-interview-questions-basic-dom-and-events-7925ce8602ef?source=email-7d5393e25aca-1600898631194-digest.reader------0-59------------------8be1a484_5a7d_41b3_8ac9_410210586401-1-f68eeeb0_1b52_418b_a7c5_14c9775bf642----)<br>
- [https://hackernoon.com/10-essential-javascript-questions-zf1t3ueo](https://hackernoon.com/10-essential-javascript-questions-zf1t3ueo)<br>
- [https://dev.to/dverybest/basic-javascript-interview-questions-3491](https://dev.to/dverybest/basic-javascript-interview-questions-3491)<br>
- [https://medium.com/the-clever-dev/50-difficult-javascript-interview-questions-88e6e92367e7](https://medium.com/the-clever-dev/50-difficult-javascript-interview-questions-88e6e92367e7)<br>
- [https://javascript.plainenglish.io/50-javascript-best-practice-rules-to-write-better-code-86ce731311d7](https://javascript.plainenglish.io/50-javascript-best-practice-rules-to-write-better-code-86ce731311d7)<br>
- [https://dev.to/macmacky/70-javascript-interview-questions-5gfi](https://dev.to/macmacky/70-javascript-interview-questions-5gfi)<br>
- [https://engineeringinterviewquestions.com/javascript-interview-questions-and-answers/](https://engineeringinterviewquestions.com/javascript-interview-questions-and-answers/)<br>
- [https://www.edureka.co/blog/interview-questions/javascript-interview-questions/](https://www.edureka.co/blog/interview-questions/javascript-interview-questions/)<br>
- [https://www.telerik.com/blogs/how-to-prepare-javascript-interview](https://www.telerik.com/blogs/how-to-prepare-javascript-interview)<br>
- [https://www.softwaretestinghelp.com/javascript-interview-questions/](https://www.softwaretestinghelp.com/javascript-interview-questions/)<br>
- [https://javascript.plainenglish.io/6-interview-questions-that-combine-promise-and-settimeout-34c430fc297e](https://javascript.plainenglish.io/6-interview-questions-that-combine-promise-and-settimeout-34c430fc297e)<br>
- [https://codeburst.io/60-javascript-tutorials-walkthroughs-cb315cc1947e](https://codeburst.io/60-javascript-tutorials-walkthroughs-cb315cc1947e)<br>
- [https://dev.to/sadanandpai/2022-frontend-development-interview-checklist-roadmap-343j](https://dev.to/sadanandpai/2022-frontend-development-interview-checklist-roadmap-343j)<br>
- [https://snipcart.com/blog/javascript-practice-exercises](https://snipcart.com/blog/javascript-practice-exercises)<br>
- [https://cult.honeypot.io/reads/ultimate-guide-to-hire-javascript-developers/](https://cult.honeypot.io/reads/ultimate-guide-to-hire-javascript-developers/)<br>
- [https://blog.bitsrc.io/javascript-interview-question-what-are-iterables-and-iterators-5773ff3409f7](https://blog.bitsrc.io/javascript-interview-question-what-are-iterables-and-iterators-5773ff3409f7)<br>
- [https://dev.to/coderpad/the-complete-guide-to-regular-expressions-regex-1m6](https://dev.to/coderpad/the-complete-guide-to-regular-expressions-regex-1m6)<br>
- [https://javascript.works-hub.com/learn/top-80-javascript-interview-questions-javascript-works-f5b5f?utm_source=social&utm_medium=social&utm_content=romina2709](https://javascript.works-hub.com/learn/top-80-javascript-interview-questions-javascript-works-f5b5f?utm_source=social&utm_medium=social&utm_content=romina2709)<br>
- [https://medium.com/vanguards-of-code/lodash-is-dead-long-live-radash-d9d52abf428b](https://medium.com/vanguards-of-code/lodash-is-dead-long-live-radash-d9d52abf428b)<br>

## `Tips and Tricks`
- [https://javascript.plainenglish.io/13-javascript-anomalies-331833001bd2](https://javascript.plainenglish.io/13-javascript-anomalies-331833001bd2)<br/>
- [https://hackernoon.com/the-clean-code-book-for-javascript-developers-a-quick-summary-m82b373s](https://hackernoon.com/the-clean-code-book-for-javascript-developers-a-quick-summary-m82b373s)<br/>
- [https://iampalash.hashnode.dev/10-awesome-javascript-shorthands](https://iampalash.hashnode.dev/10-awesome-javascript-shorthands)<br/>
- [https://medium.com/geekculture/javascript-hacks-cf8f0fecbc60](https://medium.com/geekculture/javascript-hacks-cf8f0fecbc60)<br/>
- [https://apoorvtyagi.tech/javascript-tips-and-best-practices](https://apoorvtyagi.tech/javascript-tips-and-best-practices)<br/>
- [https://javascript.plainenglish.io/10-tips-to-improve-readability-in-javascript-382eb287437](https://javascript.plainenglish.io/10-tips-to-improve-readability-in-javascript-382eb287437)<br>
- [https://blog.yogeshchavan.dev/tricky-javascript-code-snippets-asked-in-the-interview-1](https://blog.yogeshchavan.dev/tricky-javascript-code-snippets-asked-in-the-interview-1)<br>
- [https://javascript.plainenglish.io/50-javascript-output-questions-818d45c3e381](https://javascript.plainenglish.io/50-javascript-output-questions-818d45c3e381)<br>
- [https://www.smashingmagazine.com/2021/04/vanilla-javascript-code-snippets/](https://www.smashingmagazine.com/2021/04/vanilla-javascript-code-snippets/)<br>
- [https://dev.to/worldindev/8-javascript-tips-tricks-that-no-one-teaches-24g1](https://dev.to/worldindev/8-javascript-tips-tricks-that-no-one-teaches-24g1)<br>
- [https://thenextweb.com/news/how-to-write-cleaner-code-with-javascript](https://thenextweb.com/news/how-to-write-cleaner-code-with-javascript)<br>
- [https://alimammiya.hashnode.dev/5-useful-javascript-tricks-for-beginners](https://alimammiya.hashnode.dev/5-useful-javascript-tricks-for-beginners)<br>
- [https://javascript.plainenglish.io/7-concepts-you-should-know-as-a-javascript-developer-f406597319ab](https://javascript.plainenglish.io/7-concepts-you-should-know-as-a-javascript-developer-f406597319ab)<br>
- [https://medium.com/javascript-in-plain-english/18-tips-tricks-for-a-junior-javascript-developer-ae4af698a596](https://medium.com/javascript-in-plain-english/18-tips-tricks-for-a-junior-javascript-developer-ae4af698a596)<br>
- [https://medium.com/@manish2bharti/javascript-tricks-for-developers-2637e1c1835d](https://medium.com/@manish2bharti/javascript-tricks-for-developers-2637e1c1835d)<br>
- [https://medium.com/@deepikawadhera1996/javascript-tips-and-tricks-b1a5d93c9c03](https://medium.com/@deepikawadhera1996/javascript-tips-and-tricks-b1a5d93c9c03)<br>
- [https://blog.greenroots.info/5-useful-tips-about-the-javascript-array-sort-method-ckfs2cifq00eju9s17dfy3jq8](https://blog.greenroots.info/5-useful-tips-about-the-javascript-array-sort-method-ckfs2cifq00eju9s17dfy3jq8)<br>
- [https://dev.to/ga/7-javascript-tips-and-tricks-3d2o](https://dev.to/ga/7-javascript-tips-and-tricks-3d2o)<br>
- [https://dev.to/alwarg/fun-with-javascript-tricks-jmk](https://dev.to/alwarg/fun-with-javascript-tricks-jmk)<br>
- [https://blog.greenroots.info/my-favorite-javascript-tips-and-tricks-ckd60i4cq011em8s16uobcelc?utm_campaign=my-favorite-javascript-tips-and-tricks](https://blog.greenroots.info/my-favorite-javascript-tips-and-tricks-ckd60i4cq011em8s16uobcelc?utm_campaign=my-favorite-javascript-tips-and-tricks)<br>
- [https://thenextweb.com/syndication/2020/07/25/how-to-write-cleaner-code-with-javascript/](https://thenextweb.com/syndication/2020/07/25/how-to-write-cleaner-code-with-javascript/)<br>
- [http://pop.frontendweekly.co/VdB6qN?utm_campaign=most-useful-javascript-tips-&-tricks-for](http://pop.frontendweekly.co/VdB6qN?utm_campaign=most-useful-javascript-tips-&-tricks-for)<br>
- [https://medium.com/developers-arena/some-simple-and-amazing-javascript-tricks-292e1962b1f6](https://medium.com/developers-arena/some-simple-and-amazing-javascript-tricks-292e1962b1f6)<br>
- [https://medium.com/javascript-in-plain-english/some-js-shortcuts-82bc2f56146e](https://medium.com/javascript-in-plain-english/some-js-shortcuts-82bc2f56146e)<br>
- [https://www.freecodecamp.org/news/nine-most-common-mistakes-developers-make-in-javascript/](https://www.freecodecamp.org/news/nine-most-common-mistakes-developers-make-in-javascript/)<br>
- [https://apoorvtyagi.tech/javascript-clean-code-tips-and-good-practices](https://apoorvtyagi.tech/javascript-clean-code-tips-and-good-practices)<br>
- [https://github.com/neonmob/NeonMob-beta/pull/4397](https://github.com/neonmob/NeonMob-beta/pull/4397)<br>
- [https://livecodestream.dev/post/awesome-javascript-one-liners-to-look-like-a-pro/](https://livecodestream.dev/post/awesome-javascript-one-liners-to-look-like-a-pro/)<br>
- [https://dev.to/alexdevero/7-practices-to-create-good-javascript-variables-1a6l](https://dev.to/alexdevero/7-practices-to-create-good-javascript-variables-1a6l)<br>
-[https://codeoz.hashnode.dev/improve-your-js-skills-with-theses-tips-2](https://codeoz.hashnode.dev/improve-your-js-skills-with-theses-tips-2)<br>
-[https://dev.to/pascavld/10-javascript-tips-that-can-help-you-understand-this-programming-language-better-3fi0](https://dev.to/pascavld/10-javascript-tips-that-can-help-you-understand-this-programming-language-better-3fi0)<br>
- [https://tech.groww.in/worst-javascript-practices-that-degrade-code-quality-c21e068f0212](https://tech.groww.in/worst-javascript-practices-that-degrade-code-quality-c21e068f0212)<br>
- [https://javascript.plainenglish.io/another-17-life-saving-javascript-one-liners-8c335bf73d2c](https://javascript.plainenglish.io/another-17-life-saving-javascript-one-liners-8c335bf73d2c)<br>
- [https://javascript.plainenglish.io/the-javascript-nobody-told-you-about-ac1bf4f56eb9](https://javascript.plainenglish.io/the-javascript-nobody-told-you-about-ac1bf4f56eb9)<br>
- [https://blog.bitsrc.io/writing-clean-code-in-javascript-dd584bbe1874](https://blog.bitsrc.io/writing-clean-code-in-javascript-dd584bbe1874)<br>
- [https://dev.to/perenstrom/four-tricky-javascript-concepts-in-one-line-of-code-3i3p](https://dev.to/perenstrom/four-tricky-javascript-concepts-in-one-line-of-code-3i3p)<br>
- [https://towardsdev.com/javascript-the-hard-parts-part-1-80b45aa8ce53](https://towardsdev.com/javascript-the-hard-parts-part-1-80b45aa8ce53)<br>
- [https://dev.to/martinkr/series/15146](https://dev.to/martinkr/series/15146)<br>
- [https://dev.to/codewithahsan/8-techniques-to-write-cleaner-javascript-code-369e](https://dev.to/codewithahsan/8-techniques-to-write-cleaner-javascript-code-369e)<br>
- [https://blog.bitsrc.io/9-javascript-console-tips-that-will-improve-your-debugging-skills-1899e37469d5](https://blog.bitsrc.io/9-javascript-console-tips-that-will-improve-your-debugging-skills-1899e37469d5)<br>
- [https://blog.logrocket.com/how-detect-dead-code-frontend-project/](https://blog.logrocket.com/how-detect-dead-code-frontend-project/)<br>
- [https://javascript.plainenglish.io/5-javascript-concepts-to-make-you-an-excellent-front-end-developer-994676aa2431](https://javascript.plainenglish.io/5-javascript-concepts-to-make-you-an-excellent-front-end-developer-994676aa2431) <br>
- [https://intspirit.medium.com/top-of-js-topics-mostly-failed-by-developers-53397f13eb78](https://intspirit.medium.com/top-of-js-topics-mostly-failed-by-developers-53397f13eb78)<br>
- [https://devdojo.com/posandu/16-javascript-snippets-to-save-your-time](https://devdojo.com/posandu/16-javascript-snippets-to-save-your-time)<br>
- [https://medium.com/@dreamy-player/40-killer-javascript-one-liners-fc76edaf8439](https://medium.com/@dreamy-player/40-killer-javascript-one-liners-fc76edaf8439)<br/>
- [https://dev.to/devsimc/change-your-old-methods-for-writing-a-javascript-code-shorthands-for-javascript-code-54hp](https://dev.to/devsimc/change-your-old-methods-for-writing-a-javascript-code-shorthands-for-javascript-code-54hp)<br/>
- [https://blog.openreplay.com/javascript-seo-best-practices/](https://blog.openreplay.com/javascript-seo-best-practices/)<br>
- [https://hackernoon.com/optimizing-performance-with-throttling-in-javascript?source=rss](https://hackernoon.com/optimizing-performance-with-throttling-in-javascript?source=rss)<br>


## `Javascript Cheatsheet`
- [https://blog.rahulism.co/ultimate-javascript-cheatsheet](https://blog.rahulism.co/ultimate-javascript-cheatsheet)<br/>
- [https://medium.com/javascript-in-plain-english/a-javascript-cheatsheet-you-need-in-2020-d81b3dd89e09](https://medium.com/javascript-in-plain-english/a-javascript-cheatsheet-you-need-in-2020-d81b3dd89e09)<br/>
- [https://ilovecoding.org/blog/js-cheatsheet](https://ilovecoding.org/blog/js-cheatsheet)<br>
- [https://dev.to/sakhnyuk/js-array-cheatsheet-31h0](https://dev.to/sakhnyuk/js-array-cheatsheet-31h0)<br>
- [https://dev.to/anmolraj/javascript-cheatsheet-for-beginners-to-advance-4en4](https://dev.to/anmolraj/javascript-cheatsheet-for-beginners-to-advance-4en4)<br>
- [https://dev.to/abhirajb/the-ultimate-javascript-cheatsheet-55j2](https://dev.to/abhirajb/the-ultimate-javascript-cheatsheet-55j2)<br>
- [https://blog.suhailkakar.com/javascript-cheat-sheet-for-beginners-2021](https://blog.suhailkakar.com/javascript-cheat-sheet-for-beginners-2021)<br>
- [https://dev.to/thisurathenuka/closures-javascript-concepts-simplified-4665](https://dev.to/thisurathenuka/closures-javascript-concepts-simplified-4665)<br>

## `Javascript News Letters`
- [https://javascriptkicks.com/@JavaScriptKicks](https://javascriptkicks.com/@JavaScriptKicks)<br/>
- [https://www.30secondsofcode.org/](https://www.30secondsofcode.org/)<br/>
- [https://jsstartup.com/https://jsstartup.com/]()<br>
- [https://hashnode.com/n/javascript](https://hashnode.com/n/javascript)<br/>
- [https://javascriptweekly.com/](https://javascriptweekly.com/)<br>
- [https://weekly.bestofjs.org/](https://weekly.bestofjs.org/)<br>
- [http://esnextnews.com/](http://esnextnews.com/)<br>
- [http://adripofjavascript.com/archive.html](http://adripofjavascript.com/archive.html)<br>
- [http://jster.net/blog](http://jster.net/blog)<br>
- [https://js.libhunt.com/newsletter](https://js.libhunt.com/newsletter)<br>
- [https://webtoolsweekly.com/](https://webtoolsweekly.com/)<br>
- [https://techbeacon.com/app-dev-testing/27-javascript-experts-follow-twitter](https://techbeacon.com/app-dev-testing/27-javascript-experts-follow-twitter)<br>
- [https://gamedevjsweekly.com/](https://gamedevjsweekly.com/)<br>
- [https://ponyfoo.com/weekly](https://ponyfoo.com/weekly)<br>
- [https://readme.md/category/javascript](https://readme.md/category/javascript)<br>
- [https://javascript.plainenglish.io/](https://javascript.plainenglish.io/)<br>
- [https://learn.devkode.io/#/ecmascript/rest-parameters/guides](https://learn.devkode.io/#/ecmascript/rest-parameters/guides)<br>
- [https://soshace.com/category/javascript/](https://soshace.com/category/javascript/)<br>
- [https://www.ma-no.org/en/programming/javascript](https://www.ma-no.org/en/programming/javascript)<br>
- [https://medium.com/javascript-in-plain-english](https://medium.com/javascript-in-plain-english)<br>
- [https://www.w3docs.com/snippets/javascript.html](https://www.w3docs.com/snippets/javascript.html)<br>

## `Developers to follow`
- [https://hashnode.com/@iampalash](https://hashnode.com/@iampalash)<br/>
- [https://umaar.com/dev-tips/](https://umaar.com/dev-tips/)<br>
- [https://dmitripavlutin.com/](https://dmitripavlutin.com/)<br>
- [https://wasefs.medium.com/](https://wasefs.medium.com/)<br>
- [https://anil-pace.medium.com/](https://anil-pace.medium.com/)<br>
- [https://madasamy.medium.com/](https://madasamy.medium.com/)<br>
- [https://daveceddia.com/archives/](https://daveceddia.com/archives/)<br>
- [https://www.ibrahima-ndaw.com/](https://www.ibrahima-ndaw.com/)<br>
- [https://github.com/yogain123](https://github.com/yogain123)<br>
- [https://dev.to/coderslang](https://dev.to/coderslang)<br>
- [https://www.freecodecamp.org/news/author/joy/](https://www.freecodecamp.org/news/author/joy/)<br>
- [https://github.com/kealanparr/Every-link-I-wish-I-had-as-a-beginner](https://github.com/kealanparr/Every-link-I-wish-I-had-as-a-beginner)<br>
- [https://hashnode.com/@Madza](https://hashnode.com/@Madza)<br>
- [https://kittygiraudel.com/blog/](https://kittygiraudel.com/blog/)<br>

## `Javascript Algorithm`
- [https://hackernoon.com/algorithms-and-data-structures-implemented-in-es6-javascript-h41w342t](https://hackernoon.com/algorithms-and-data-structures-implemented-in-es6-javascript-h41w342t)<br>
- [https://dev.to/doabledanny/how-to-compare-arrays-in-javascript-efficiently-1p0](https://dev.to/doabledanny/how-to-compare-arrays-in-javascript-efficiently-1p0)<br>
- [https://github.com/trekhleb/javascript-algorithms](https://github.com/trekhleb/javascript-algorithms)<br>
- [https://dev.to/deleteman123/practical-big-o-notation-for-javascript-developers-2lhn](https://dev.to/deleteman123/practical-big-o-notation-for-javascript-developers-2lhn)<br>
- [https://www.freecodecamp.org/news/introduction-to-algorithms-with-javascript-examples/](https://www.freecodecamp.org/news/introduction-to-algorithms-with-javascript-examples/)<br>

## `Learn Javascript`
- [https://jstherightway.org/](https://jstherightway.org/)<br>
- [https://code.tutsplus.com/series/learn-javascript-the-complete-guide--cms-1112](https://code.tutsplus.com/series/learn-javascript-the-complete-guide--cms-1112)<br>
- [https://scotch.io/courses/getting-started-with-javascript-for-web-development?ref=home-start-here](https://scotch.io/courses/getting-started-with-javascript-for-web-development?ref=home-start-here)<br>
- [https://danysdevcorner.hashnode.dev/useful-javascript-resources-to-learn-and-remember](https://danysdevcorner.hashnode.dev/useful-javascript-resources-to-learn-and-remember)<br>
- [https://reactgo.com/tutorials/javascript/](https://reactgo.com/tutorials/javascript/)<br>
- [https://devdojo.com/piyushsinha24/modern-javascript-iii](https://devdojo.com/piyushsinha24/modern-javascript-iii)<br>
- [https://techstack.hashnode.dev/the-core-of-javascript](https://techstack.hashnode.dev/the-core-of-javascript)<br>
- [https://medium.com/javascript-in-plain-english/guide-for-mastering-modern-javascript-skills-7d4ee42bf009](https://medium.com/javascript-in-plain-english/guide-for-mastering-modern-javascript-skills-7d4ee42bf009)<br>
- [https://daily.dev/posts/the-7-best-resources-to-learn-javascript-as-a-beginner](https://daily.dev/posts/the-7-best-resources-to-learn-javascript-as-a-beginner)<br>
- [https://courses.learncodeonline.in/](https://courses.learncodeonline.in/)<br>
- [https://dev.to/codinglistsdev/48-articles-to-go-beginner-to-pro-in-javascript-2ofn](https://dev.to/codinglistsdev/48-articles-to-go-beginner-to-pro-in-javascript-2ofn)<br>
- [https://dev.to/tyaga001/a-simple-and-effective-way-to-learn-practice-javascript-5f3p](https://dev.to/tyaga001/a-simple-and-effective-way-to-learn-practice-javascript-5f3p)<br>
- [https://dev.to/devcronin/level-up-with-javascript-lvl-5-1406](https://dev.to/devcronin/level-up-with-javascript-lvl-5-1406)<br>
- [https://css-tricks.com/comparing-methods-for-appending-and-inserting-with-javascript/](https://css-tricks.com/comparing-methods-for-appending-and-inserting-with-javascript/)<br>
 - [https://javascript.plainenglish.io/how-javascript-works-a-visual-guide-515199eef837](https://javascript.plainenglish.io/how-javascript-works-a-visual-guide-515199eef837)<br>
 - [https://dev.to/tyaga001/if-i-were-to-restart-javascript-again-from-scratch-then-i-will-follow-this-roadmap-5c02](https://dev.to/tyaga001/if-i-were-to-restart-javascript-again-from-scratch-then-i-will-follow-this-roadmap-5c02)<br>
 - [https://cult.honeypot.io/reads/how-to-learn-javascript-2021/](https://cult.honeypot.io/reads/how-to-learn-javascript-2021/)<br>
 - [https://www.freecodecamp.org/news/how-to-learn-javascript-a-little-faster/](https://www.freecodecamp.org/news/how-to-learn-javascript-a-little-faster/)<br>
 - [https://ajibolasegun.hashnode.dev/fundamentals-of-javascript-for-complete-beginners](https://ajibolasegun.hashnode.dev/fundamentals-of-javascript-for-complete-beginners)<br>
 - [https://blog.logrocket.com/storing-retrieving-javascript-objects-localstorage/](https://blog.logrocket.com/storing-retrieving-javascript-objects-localstorage/)<br>
 - [https://dev.to/ikamran/ultimate-list-of-javascript-learning-resource-free-3kef](https://dev.to/ikamran/ultimate-list-of-javascript-learning-resource-free-3kef)<br>
 - [https://javascript.plainenglish.io/javascript-roadmap-to-becoming-a-100000k-year-developer-78cf3ec3d466](https://javascript.plainenglish.io/javascript-roadmap-to-becoming-a-100000k-year-developer-78cf3ec3d466)<br>
 - [https://rajatgupta.net/local-storage-and-session-storage-javascript](https://rajatgupta.net/local-storage-and-session-storage-javascript)<br>
 - [https://dev.to/p42/level-up-your-javascript-with-these-60-quick-fixes-for-vs-code-5390](https://dev.to/p42/level-up-your-javascript-with-these-60-quick-fixes-for-vs-code-5390)<br>
 - [https://blog.tapan.app/javascript-a-single-threaded-non-blocking-synchronous-concurrent-language-part-1](https://blog.tapan.app/javascript-a-single-threaded-non-blocking-synchronous-concurrent-language-part-1)<br>
 - [https://tanishka.hashnode.dev/javascript-fundamentals-part-1](https://tanishka.hashnode.dev/javascript-fundamentals-part-1)<br>
 - [https://javascript.plainenglish.io/basic-javascript-mistakes-and-best-practices-aa97ffc0e553(https://javascript.plainenglish.io/basic-javascript-mistakes-and-best-practices-aa97ffc0e553)<br/>
 - [https://vercel.com/guides/nextjs-prisma-postgres](https://vercel.com/guides/nextjs-prisma-postgres)<br>
 - [https://www.freecodecamp.org/news/how-to-learn-javascript-faster/](https://www.freecodecamp.org/news/how-to-learn-javascript-faster/)<br/>
 - [https://tech.groww.in/introduction-to-javascript-380354c527e2](https://tech.groww.in/introduction-to-javascript-380354c527e2) <br>

## `Javascript Books`
- [https://matfuvit.github.io/UVIT/predavanja/literatura/TutorialsPoint%20JavaScript.pdf](https://matfuvit.github.io/UVIT/predavanja/literatura/TutorialsPoint%20JavaScript.pdf)<br>
- [https://exploringjs.com/impatient-js/downloads/impatient-js-preview-book.pdf](https://exploringjs.com/impatient-js/downloads/impatient-js-preview-book.pdf)<br>
- [https://minal-vaity95.medium.com/ultimate-javascript-cheatsheet-d21b0154d589](https://minal-vaity95.medium.com/ultimate-javascript-cheatsheet-d21b0154d589)<br>
- [https://blog.bitsrc.io/9-free-javascript-books-that-are-well-worth-reading-7cf6b0a20da9](https://blog.bitsrc.io/9-free-javascript-books-that-are-well-worth-reading-7cf6b0a20da9)<br>
- [https://jsbooks.revolunet.com/](https://jsbooks.revolunet.com/)<br>
- [https://dev.to/j471n/javascript-cheat-sheet-you-needed-2id?signin=true](https://dev.to/j471n/javascript-cheat-sheet-you-needed-2id?signin=true)<br>
- [https://www.sitepoint.com/best-javascript-books-for-beginners/?utm_source=rss](https://www.sitepoint.com/best-javascript-books-for-beginners/?utm_source=rss)<br>

## `General`
- [https://blog.ganeshjaiwal.dev/how-does-javascript-work](https://blog.ganeshjaiwal.dev/how-does-javascript-work)<br>
- [https://www.webfx.com/blog/web-design/6-advanced-javascript-techniques-you-should-know/](https://www.webfx.com/blog/web-design/6-advanced-javascript-techniques-you-should-know/)<br>
- [https://blog.kritikapattalam.com/use-strict-mode-in-javascript](https://blog.kritikapattalam.com/use-strict-mode-in-javascript)<br>
- [https://blog.logrocket.com/solid-principles-single-responsibility-in-javascript-frameworks/](https://blog.logrocket.com/solid-principles-single-responsibility-in-javascript-frameworks/)<br>
- [https://yogeshchavan.hashnode.dev/master-modern-javascript-skills-with-this-amazing-guide](https://yogeshchavan.hashnode.dev/master-modern-javascript-skills-with-this-amazing-guide)<br>
- [https://dmitripavlutin.com/javascript-null/](https://dmitripavlutin.com/javascript-null/)<br>
- [https://seven.hashnode.dev/understanding-import-and-export-statements-in-javascript](https://seven.hashnode.dev/understanding-import-and-export-statements-in-javascript)<br>
- [https://medium.com/@mirzaleka/exploring-javascript-ecosystem-popular-tools-frameworks-libraries-7901703ec88f](https://medium.com/@mirzaleka/exploring-javascript-ecosystem-popular-tools-frameworks-libraries-7901703ec88f)<br>
- [https://flaviocopes.com/javascript-lexical-structure/](https://flaviocopes.com/javascript-lexical-structure/)<br>
- [https://dev.to/bgoonz/all-of-my-articles-combined-284m](https://dev.to/bgoonz/all-of-my-articles-combined-284m)<br>
- [https://devdojo.com/devbookmark/an-ultimate-guide-to-logging-in-javascript](https://devdojo.com/devbookmark/an-ultimate-guide-to-logging-in-javascript)<br>
- [https://dev.to/aritik/essential-concepts-in-js-4bbj](https://dev.to/aritik/essential-concepts-in-js-4bbj)<br>
- [https://blog.jetbrains.com/webstorm/2021/08/js-roundup-episode-01/](https://blog.jetbrains.com/webstorm/2021/08/js-roundup-episode-01/)<br>
- [https://blog.siddu.tech/7-console-log-alternatives](https://blog.siddu.tech/7-console-log-alternatives)<br>
- [https://hashnode.com/post/fundamentals-of-javascript-for-complete-beginners-ckvh6uduj06kupus117db5uph](https://hashnode.com/post/fundamentals-of-javascript-for-complete-beginners-ckvh6uduj06kupus117db5uph)<br>
- [https://blog.bitsrc.io/best-practices-for-using-comments-in-javascript-4c4cd8619c18](https://blog.bitsrc.io/best-practices-for-using-comments-in-javascript-4c4cd8619c18)<br>
- [https://dev.to/snickdx/how-well-do-you-know-dom-javascript-3fl5](https://dev.to/snickdx/how-well-do-you-know-dom-javascript-3fl5)<br>
- [https://snipcart.com/blog/javascript-module-bundler](https://snipcart.com/blog/javascript-module-bundler)<br>
- [https://dev.to/josec/javascript-everything-you-always-wanted-to-know-about-localstorage-but-you-were-afraid-to-ask-2o7e](https://dev.to/josec/javascript-everything-you-always-wanted-to-know-about-localstorage-but-you-were-afraid-to-ask-2o7e)<br>
- [https://dev.to/vudodov/javascript-memory-architecture-and-lifecycle-ae9](https://dev.to/vudodov/javascript-memory-architecture-and-lifecycle-ae9)<br>
- [https://blog.bitsrc.io/javascript-sanitizer-api-the-modern-way-to-safe-dom-manipulation-828d5ea7dca6](https://blog.bitsrc.io/javascript-sanitizer-api-the-modern-way-to-safe-dom-manipulation-828d5ea7dca6)<br>
- [https://dev.to/devcronin/level-up-boost-your-javascript-skills-lvl-3-4m83](https://dev.to/devcronin/level-up-boost-your-javascript-skills-lvl-3-4m83)<br>
- [https://www.freecodecamp.org/news/javascript-modules-beginners-guide/](https://www.freecodecamp.org/news/javascript-modules-beginners-guide/)<br>
- [https://blog.devgenius.io/how-javascript-works-behind-the-scenes-88c546173f32](https://blog.devgenius.io/how-javascript-works-behind-the-scenes-88c546173f32)<br>
- [https://javascript.plainenglish.io/all-you-need-to-get-started-with-javascript-dom-d8c5dae38f02](https://javascript.plainenglish.io/all-you-need-to-get-started-with-javascript-dom-d8c5dae38f02)<br>
- [https://www.telerik.com/blogs/understanding-execution-context-javascript](https://www.telerik.com/blogs/understanding-execution-context-javascript)<br>
- [https://hackernoon.com/50-shortcut-links-for-developers-productivity](https://hackernoon.com/50-shortcut-links-for-developers-productivity)<br>
- [https://www.syncfusion.com/blogs/post/javascript-api-mocking-techniques.aspx](https://www.syncfusion.com/blogs/post/javascript-api-mocking-techniques.aspx)<br>
- [https://blog.openreplay.com/the-ultimate-guide-to-localstorage-in-javascript/](https://blog.openreplay.com/the-ultimate-guide-to-localstorage-in-javascript/)<br>
- [https://medium.com/mindful-engineering/what-how-and-why-javascript-engine-b75b45a23a81](https://medium.com/mindful-engineering/what-how-and-why-javascript-engine-b75b45a23a81)<br>


## `Best Practices`
- [https://stackoverflow.blog/2021/07/05/best-practices-for-writing-code-comments/](https://stackoverflow.blog/2021/07/05/best-practices-for-writing-code-comments/)<br>
- [https://javascript.plainenglish.io/improve-javascript-code-quality-with-these-best-practices-ee883a124d8e](https://javascript.plainenglish.io/improve-javascript-code-quality-with-these-best-practices-ee883a124d8e)<br>
- [https://dzone.com/articles/javascript-best-practices-to-improve-code-quality](https://dzone.com/articles/javascript-best-practices-to-improve-code-quality)<br>
- [https://deepaksisodiya.hashnode.dev/5-best-practices-for-clean-coding-in-javascript-ckewx32f801e7ggs1ddys9m3f](https://deepaksisodiya.hashnode.dev/5-best-practices-for-clean-coding-in-javascript-ckewx32f801e7ggs1ddys9m3f)<br>
- [https://medium.com/javascript-in-plain-english/19-simple-javascript-coding-standards-to-keep-your-code-clean-7422d6f9bc0](https://medium.com/javascript-in-plain-english/19-simple-javascript-coding-standards-to-keep-your-code-clean-7422d6f9bc0)<br>
- [https://betterprogramming.pub/clean-code-applied-to-javascript-part-1-9f3badd5715](https://betterprogramming.pub/clean-code-applied-to-javascript-part-1-9f3badd5715)<br>
- [https://www.webtips.dev/5-best-practices-for-clean-javascript](https://www.webtips.dev/5-best-practices-for-clean-javascript)<br>
- [https://dev.to/learnersbucket/industry-focused-roadmap-to-be-javascript-developer-2021-1m2b](https://dev.to/learnersbucket/industry-focused-roadmap-to-be-javascript-developer-2021-1m2b)<br>
- [https://blog.bitsrc.io/javascript-worst-practices-dc78e19d6f12](https://blog.bitsrc.io/javascript-worst-practices-dc78e19d6f12)<br>
- [https://dev.to/didof/penetration-and-security-in-javascript-probing-double-getter-p47](https://dev.to/didof/penetration-and-security-in-javascript-probing-double-getter-p47)<br>
- [https://www.ma-no.org/en/programming/javascript/javascript-programming-styles-best-practices](https://www.ma-no.org/en/programming/javascript/javascript-programming-styles-best-practices)<br>


## `Javascript Projects`
- [https://hashnode.com/post/15-project-ideas-for-web-developers-ckmg1p6vc00ialds1cmtl870c](https://hashnode.com/post/15-project-ideas-for-web-developers-ckmg1p6vc00ialds1cmtl870c)<br>
- [https://www.crio.do/blog/top-5-javascript-projects-reactjs/](https://www.crio.do/blog/top-5-javascript-projects-reactjs/)<br>
- [https://medium.com/swlh/projects-you-can-build-with-vanilla-javascript-e52c3e00f25c](https://medium.com/swlh/projects-you-can-build-with-vanilla-javascript-e52c3e00f25c)<br>
- [https://codelifefitness.hashnode.dev/projects-you-can-build-with-vanilla-javascript](https://codelifefitness.hashnode.dev/projects-you-can-build-with-vanilla-javascript)<br>
- [https://annysah.hashnode.dev/7-beginner-friendly-javascript-project-ideas-ckevszz7u021dnzs19gu4eaye](https://annysah.hashnode.dev/7-beginner-friendly-javascript-project-ideas-ckevszz7u021dnzs19gu4eaye)<br>
- [https://levelup.gitconnected.com/learn-concepts-of-vanilla-javascript-while-building-a-privacy-card-game-in-5-easy-steps-7b0a2d89db63](https://levelup.gitconnected.com/learn-concepts-of-vanilla-javascript-while-building-a-privacy-card-game-in-5-easy-steps-7b0a2d89db63)<br>
- [https://blog.kritikapattalam.com/build-a-simple-clock-using-javascript](https://blog.kritikapattalam.com/build-a-simple-clock-using-javascript)<br>
- [https://dev.to/devpool3000/4-javascript-projects-to-build-fast-and-get-hired-in-1-month-4agf](https://dev.to/devpool3000/4-javascript-projects-to-build-fast-and-get-hired-in-1-month-4agf)<br>
- [https://dev.to/lindelof/4-awesome-javascript-projects-worthy-of-your-collection-53fi](https://dev.to/lindelof/4-awesome-javascript-projects-worthy-of-your-collection-53fi)<br>
- [https://dev.to/chetan_atrawalkar/javascript-project-series-that-makes-you-pro-33ma](https://dev.to/chetan_atrawalkar/javascript-project-series-that-makes-you-pro-33ma)<br>
- [https://dev.to/suprabhasupi/top-api-s-for-next-javascript-project-cop](https://dev.to/suprabhasupi/top-api-s-for-next-javascript-project-cop)<br>
- [https://dev.to/chetan_atrawalkar/javascript-project-series-that-makes-you-pro-33ma](https://dev.to/chetan_atrawalkar/javascript-project-series-that-makes-you-pro-33ma)<br>
- [https://www.freecodecamp.org/news/learn-javascript-form-validation-by-making-a-form/](https://www.freecodecamp.org/news/learn-javascript-form-validation-by-making-a-form/)<br>
- [https://dev.to/kunaal438/how-to-make-an-e-commerce-website-with-html-css-and-js-3aon](https://dev.to/kunaal438/how-to-make-an-e-commerce-website-with-html-css-and-js-3aon)<br>
- [https://dev.to/colocodes/my-second-vanilla-javascript-project-using-apis-promises-classes-error-handling-and-more-24p8](https://dev.to/colocodes/my-second-vanilla-javascript-project-using-apis-promises-classes-error-handling-and-more-24p8)<br>
- [https://dev.to/haycuoilennao19/29-projects-to-help-you-practice-html-css-javascript-2021-1j88](https://dev.to/haycuoilennao19/29-projects-to-help-you-practice-html-css-javascript-2021-1j88)<br>
- [https://dev.to/pauld103/javascript-coding-projects-for-beginners-3fj0](https://dev.to/pauld103/javascript-coding-projects-for-beginners-3fj0)<br>
- [https://dev.to/kunaal438/advance-features-how-to-create-a-working-blogging-website-with-pure-html-css-and-js-in-2021-50io](https://dev.to/kunaal438/advance-features-how-to-create-a-working-blogging-website-with-pure-html-css-and-js-in-2021-50ioclear)<br>
- [https://daveyhert.hashnode.dev/how-to-implement-a-dark-mode-with-css-and-3-simple-lines-of-javascript](https://daveyhert.hashnode.dev/how-to-implement-a-dark-mode-with-css-and-3-simple-lines-of-javascript)<br>
- [https://github.com/KingsleyUbah/hacker-news-clone](https://github.com/KingsleyUbah/hacker-news-clone)<br>
- [https://enlear.academy/create-a-simple-movie-app-in-vanilla-javascript-5811bad69e09](https://enlear.academy/create-a-simple-movie-app-in-vanilla-javascript-5811bad69e09)<br>
- [https://www.foolishdeveloper.com/2021/10/coin-flip-game-using-javascript.html](https://www.foolishdeveloper.com/2021/10/coin-flip-game-using-javascript.html)<br>
- [https://www.freecodecamp.org/news/back-to-top-button-and-page-progressbar-with-html-css-and-js/](https://www.freecodecamp.org/news/back-to-top-button-and-page-progressbar-with-html-css-and-js/)<br>
- [https://devdojo.com/arpit/github-repos-to-become-better-javascript-developer](https://devdojo.com/arpit/github-repos-to-become-better-javascript-developer)<br>
- [https://devdojo.com/rahulism/13-unique-and-fun-apis-project-ideas](https://devdojo.com/rahulism/13-unique-and-fun-apis-project-ideas)<br>
- [https://blog.logrocket.com/how-to-build-file-upload-service-vanilla-javascript/](https://blog.logrocket.com/how-to-build-file-upload-service-vanilla-javascript/)<br>
- [https://github.com/Asabeneh/30-Days-Of-JavaScript](https://github.com/Asabeneh/30-Days-Of-JavaScript)<br>
- [https://blog.openreplay.com/building-a-mobile-app-using-html-css-and-javascript](https://blog.openreplay.com/building-a-mobile-app-using-html-css-and-javascript)<br>
- [https://blog.openreplay.com/four-useful-built-in-javascript-web-apis/](https://blog.openreplay.com/four-useful-built-in-javascript-web-apis/)<br>
- [https://mdjunaidap.notion.site/mdjunaidap/Learn-JavaScript-for-Free-31dfa430f4b54eaba33f493ebb964611](https://mdjunaidap.notion.site/mdjunaidap/Learn-JavaScript-for-Free-31dfa430f4b54eaba33f493ebb964611)<br>
- [https://moralis.io/web3-programming-how-to-learn-web3-programming/](https://moralis.io/web3-programming-how-to-learn-web3-programming/)<br>
- [https://www.honeybadger.io/blog/javascript-reddit-api/](https://www.honeybadger.io/blog/javascript-reddit-api/)<br>
- [https://www.freecodecamp.org/news/integrate-paypal-into-html-css-js-product-pages/](https://www.freecodecamp.org/news/integrate-paypal-into-html-css-js-product-pages/)<br>
- [https://www.freecodecamp.org/news/improve-your-javascript-skills-by-coding-a-card-game/](https://www.freecodecamp.org/news/improve-your-javascript-skills-by-coding-a-card-game/)<br>

## `Youtube channels`
- [https://dzone.com/articles/22-youtube-channels-to-level-up-your-programming-s](https://dzone.com/articles/22-youtube-channels-to-level-up-your-programming-s)<br>
- [https://www.codewall.co.uk/best-javascript-youtube-channels/](https://www.codewall.co.uk/best-javascript-youtube-channels/)<br>
- [https://www.youtube.com/watch?v=lI1ae4REbFM](https://www.youtube.com/watch?v=lI1ae4REbFM)<br>
- [https://www.youtube.com/watch?v=DqaTKBU9TZk](https://www.youtube.com/watch?v=DqaTKBU9TZk)<br>
- [https://www.youtube.com/watch?v=q7rnaVD_Wjc](https://www.youtube.com/watch?v=q7rnaVD_Wjc)<br>
- [https://www.youtube.com/watch?v=XIOLqoPHCJ4](https://www.youtube.com/watch?v=XIOLqoPHCJ4)<br>

## `Javascipt vs Typescript`
- [https://enlear.academy/typescript-vs-javascript-bdd1eca2f7b5](https://enlear.academy/typescript-vs-javascript-bdd1eca2f7b5)<br>
- [https://blog.logrocket.com/16-useful-typescript-javascript-shorthands-know/](https://blog.logrocket.com/16-useful-typescript-javascript-shorthands-know/)<br>
- [https://www.sitepoint.com/premium/books/typescript-4-design-patterns-and-best-practices/read/1/l3wpx4d2/](https://www.sitepoint.com/premium/books/typescript-4-design-patterns-and-best-practices/read/1/l3wpx4d2/)<br>
- [https://dev.to/nickytonline/learning-resources-for-typescript-4g1n](https://dev.to/nickytonline/learning-resources-for-typescript-4g1n)<br>
- [https://www.totaltypescript.com/tutorials](https://www.totaltypescript.com/tutorials)<br>
- [https://dev.to/jurooravec/7-tips-for-reverse-engineering-minified-typescript-javascript-4p64](https://dev.to/jurooravec/7-tips-for-reverse-engineering-minified-typescript-javascript-4p64)<br>
