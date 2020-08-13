# -Javascripts-tutorial_guide

> Click :star:if you like the project. Pull Request are highly appreciated. Follow me [@SudheerJonna](https://twitter.com/SudheerJonna) for technical updates.

---

<div align="center">
    <p>
        <a href="https://www.fullstack.cafe/?utm_source=github&utm_medium=sud">
            <b>Having Tech Interview?</b>
            <br> 3600 Tech Interview Questions. <b>Answered</b>.
            <br>
            <div>
                <img src="https://user-images.githubusercontent.com/13550565/76382460-cc784d80-6393-11ea-8837-2b89265ac853.png" width="260" alt="FullStack.Cafe">
            </div>
        </a>
        <sub><i>Proudly supporting React Interview Questions</i></sub>
    </p>
</div>

---

## Downloading PDF/Epub formats

You can download the PDF and Epub version of this repository from the latest run on the [actions tab](https://github.com/sudheerj/reactjs-interview-questions/actions).

### Table of Contents

| No. | Questions |
| --- | --------- |
|   | **Core React** |
|1  | [What is React?](#what-is-react) |
|2  | [What are the major features of React?](#what-are-the-major-features-of-react) |
|3  | [What is JSX?](#what-is-jsx) |
|4  | [What is the difference between Element and Component?](#what-is-the-difference-between-element-and-component) |
|5  | [How to create components in React?](#how-to-create-components-in-react) |
|6  | [When to use a Class Component over a Function Component?](#when-to-use-a-class-component-over-a-function-component) |
|7  | [What are Pure Components?](#what-are-pure-components) |
|8  | [What is state in React?](#what-is-state-in-react) |
|9  | [What are props in React?](#what-are-props-in-react) |
|10 | [What is the difference between state and props?](#what-is-the-difference-between-state-and-props) |
|11 | [Why should we not update the state directly?](#why-should-we-not-update-the-state-directly) |
|12 | [What is the purpose of callback function as an argument of setState()?](#what-is-the-purpose-of-callback-function-as-an-argument-of-setstate)
|13 | [What is the difference between HTML and React event handling?](#what-is-the-difference-between-html-and-react-event-handling) |
|14 | [How to bind methods or event handlers in JSX callbacks?](#how-to-bind-methods-or-event-handlers-in-jsx-callbacks) |
|15 | [How to pass a parameter to an event handler or callback?](#how-to-pass-a-parameter-to-an-event-handler-or-callback) |
|16 | [What are synthetic events in React?](#what-are-synthetic-events-in-react) |
|17 | [What are inline conditional expressions?](#what-are-inline-conditional-expressions) |
|18 | [What is "key" prop and what is the benefit of using it in arrays of elements?](#what-is-key-prop-and-what-is-the-benefit-of-using-it-in-arrays-of-elements) |
|19 | [What is the use of refs?](#what-is-the-use-of-refs) |
|20 | [How to create refs?](#how-to-create-refs)
|21 | [What are forward refs?](#what-are-forward-refs) |
|22 | [Which is preferred option with in callback refs and findDOMNode()?](#which-is-preferred-option-with-in-callback-refs-and-finddomnode) |
|23 | [Why are String Refs legacy?](#why-are-string-refs-legacy) |
|24 | [What is Virtual DOM?](#what-is-virtual-dom) |
|25 | [How Virtual DOM works?](#how-virtual-dom-works) |
|26 | [What is the difference between Shadow DOM and Virtual DOM?](#what-is-the-difference-between-shadow-dom-and-virtual-dom) |
|27 | [What is React Fiber?](#what-is-react-fiber) |
|28 | [What is the main goal of React Fiber?](#what-is-the-main-goal-of-react-fiber) |
|29 | [What are controlled components?](#what-are-controlled-components) |
|30 | [What are uncontrolled components?](#what-are-uncontrolled-components) |
|31 | [What is the difference between createElement and cloneElement?](#what-is-the-difference-between-createelement-and-cloneelement) |
|32 | [What is Lifting State Up in React?](#what-is-lifting-state-up-in-react) |
|33 | [What are the different phases of component lifecycle?](#what-are-the-different-phases-of-component-lifecycle) |
|34 | [What are the lifecycle methods of React?](#what-are-the-lifecycle-methods-of-react) |
|35 | [What are Higher-Order components?](#what-are-higher-order-components) |
|36 | [How to create props proxy for HOC component?](#how-to-create-props-proxy-for-hoc-component) |
|37 | [What is context?](#what-is-context) |
|38 | [What is children prop?](#what-is-children-prop) |
|39 | [How to write comments in React?](#how-to-write-comments-in-react) |
|40 | [What is the purpose of using super constructor with props argument?](#what-is-the-purpose-of-using-super-constructor-with-props-argument) |
|41 | [What is reconciliation?](#what-is-reconciliation) |
|42 | [How to set state with a dynamic key name?](#how-to-set-state-with-a-dynamic-key-name) |
|43 | [What would be the common mistake of function being called every time the component renders?](#what-would-be-the-common-mistake-of-function-being-called-every-time-the-component-renders) |
|44 | [Is lazy function supports named exports?](#is-lazy-function-supports-named-exports) |
|45 | [Why React uses className over class attribute?](#why-react-uses-classname-over-class-attribute) |
|46 | [What are fragments?](#what-are-fragments) |
|47 | [Why fragments are better than container divs?](#why-fragments-are-better-than-container-divs) |
|48 | [What are portals in React?](#what-are-portals-in-react) |
|49 | [What are stateless components?](#what-are-stateless-components) |
|50 | [What are stateful components?](#what-are-stateful-components) |
|51 | [How to apply validation on props in React?](#how-to-apply-validation-on-props-in-react) |
|52 | [What are the advantages of React?](#what-are-the-advantages-of-react) |
|53 | [What are the limitations of React?](#what-are-the-limitations-of-react) |
|54 | [What are error boundaries in React v16](#what-are-error-boundaries-in-react-v16) |
|55 | [How error boundaries handled in React v15?](#how-error-boundaries-handled-in-react-v15) |
|56 | [What are the recommended ways for static type checking?](#what-are-the-recommended-ways-for-static-type-checking) |
|57 | [What is the use of react-dom package?](#what-is-the-use-of-react-dom-package) |
|58 | [What is the purpose of render method of react-dom?](#what-is-the-purpose-of-render-method-of-react-dom) |
|59 | [What is ReactDOMServer?](#what-is-reactdomserver) |
|60 | [How to use InnerHtml in React?](#how-to-use-innerhtml-in-react) |
|61 | [How to use styles in React?](#how-to-use-styles-in-react) |
|62 | [How events are different in React?](#how-events-are-different-in-react) |
|63 | [What will happen if you use setState in constructor?](#what-will-happen-if-you-use-setstate-in-constructor) |
|64 | [What is the impact of indexes as keys?](#what-is-the-impact-of-indexes-as-keys) |
|65 | [Is it good to use setState() in componentWillMount() method?](#is-it-good-to-use-setstate-in-componentwillmount-method) |
|66 | [What will happen if you use props in initial state?](#what-will-happen-if-you-use-props-in-initial-state) |
|67 | [How do you conditionally render components?](#how-do-you-conditionally-render-components)
|68 | [Why we need to be careful when spreading props on DOM elements??](#why-we-need-to-be-careful-when-spreading-props-on-dom-elements) |
|69 | [How you use decorators in React?](#how-you-use-decorators-in-react) |
|70 | [How do you memoize a component?](#how-do-you-memoize-a-component) |
|71 | [How you implement Server-Side Rendering or SSR?](#how-you-implement-server-side-rendering-or-ssr) |
|72 | [How to enable production mode in React?](#how-to-enable-production-mode-in-react) |
|73 | [What is CRA and its benefits?](#what-is-cra-and-its-benefits) |
|74 | [What is the lifecycle methods order in mounting?](#what-is-the-lifecycle-methods-order-in-mounting) |
|75 | [What are the lifecycle methods going to be deprecated in React v16?](#what-are-the-lifecycle-methods-going-to-be-deprecated-in-react-v16) |
|76 | [What is the purpose of getDerivedStateFromProps() lifecycle method?](#what-is-the-purpose-of-getderivedstatefromprops-lifecycle-method) |
|77 | [What is the purpose of getSnapshotBeforeUpdate() lifecycle method?](#what-is-the-purpose-of-getsnapshotbeforeupdate-lifecycle-method) |
|78 | [Do Hooks replace render props and higher order components?](#do-hooks-replace-render-props-and-higher-order-components) |
|79 | [What is the recommended way for naming components?](#what-is-the-recommended-way-for-naming-components) |
|80 | [What is the recommended ordering of methods in component class?](#what-is-the-recommended-ordering-of-methods-in-component-class) |
|81 | [What is a switching component?](#what-is-a-switching-component) |
|82 | [Why we need to pass a function to setState()?](#why-we-need-to-pass-a-function-to-setstate) |
|83 | [What is strict mode in React?](#what-is-strict-mode-in-react) |
|84 | [What are React Mixins?](#what-are-react-mixins) |
|85 | [Why is isMounted() an anti-pattern and what is the proper solution?](#why-is-ismounted-an-anti-pattern-and-what-is-the-proper-solution) |
|86 | [What are the Pointer Events supported in React?](#what-are-the-pointer-events-supported-in-react) |
|87 | [Why should component names start with capital letter?](#why-should-component-names-start-with-capital-letter) |
|88 | [Are custom DOM attributes supported in React v16?](#are-custom-dom-attributes-supported-in-react-v16) |
|89 | [What is the difference between constructor and getInitialState?](#what-is-the-difference-between-constructor-and-getinitialstate) |
|90 | [Can you force a component to re-render without calling setState?](#can-you-force-a-component-to-re-render-without-calling-setstate) |
|91 | [What is the difference between super() and super(props) in React using ES6 classes?](#what-is-the-difference-between-super-and-superprops-in-react-using-es6-classes) |
|92 | [How to loop inside JSX?](#how-to-loop-inside-jsx) |
|93 | [How do you access props in attribute quotes?](#how-do-you-access-props-in-attribute-quotes) |
|94 | [What is React PropType array with shape?](#what-is-react-proptype-array-with-shape) |
|95 | [How to conditionally apply class attributes?](#how-to-conditionally-apply-class-attributes) |
|96 | [What is the difference between React and ReactDOM?](#what-is-the-difference-between-react-and-reactdom) |
|97 | [Why ReactDOM is separated from React?](#why-reactdom-is-separated-from-react) |
|98 | [How to use React label element?](#how-to-use-react-label-element) |
|99 | [How to combine multiple inline style objects?](#how-to-combine-multiple-inline-style-objects) |
|100| [How to re-render the view when the browser is resized?](#how-to-re-render-the-view-when-the-browser-is-resized)
|101| [What is the difference between setState and replaceState methods?](#what-is-the-difference-between-setstate-and-replacestate-methods) |
|102| [How to listen to state changes?](#how-to-listen-to-state-changes) |
|103| [What is the recommended approach of removing an array element in react state?](#what-is-the-recommended-approach-of-removing-an-array-element-in-react-state) |
|104| [Is it possible to use React without rendering HTML?](#is-it-possible-to-use-react-without-rendering-html) |
|105| [How to pretty print JSON with React?](#how-to-pretty-print-json-with-react) |
|106| [Why you can't update props in React?](#why-you-cant-update-props-in-react) |
|107| [How to focus an input element on page load?](#how-to-focus-an-input-element-on-page-load) |
|108| [What are the possible ways of updating objects in state?](#what-are-the-possible-ways-of-updating-objects-in-state) |
|110| [How can we find the version of React at runtime in the browser?](#how-can-we-find-the-version-of-react-at-runtime-in-the-browser) |
|111| [What are the approaches to include polyfills in your create-react-app?](#what-are-the-approaches-to-include-polyfills-in-your-create-react-app) |
|112| [How to use https instead of http in create-react-app?](#how-to-use-https-instead-of-http-in-create-react-app) |
|113| [How to avoid using relative path imports in create-react-app?](#how-to-avoid-using-relative-path-imports-in-create-react-app) |
|114| [How to add Google Analytics for react-router?](#how-to-add-google-analytics-for-react-router) |
|115| [How to update a component every second?](#how-to-update-a-component-every-second) |
|116| [How do you apply vendor prefixes to inline styles in React?](#how-do-you-apply-vendor-prefixes-to-inline-styles-in-react) |
|117| [How to import and export components using react and ES6?](#how-to-import-and-export-components-using-react-and-es6) |
|118| [What are the exceptions on React component naming?](#what-are-the-exceptions-on-react-component-naming) |
|119| [Why is a component constructor called only once?](#why-is-a-component-constructor-called-only-once) |
|120| [How to define constants in React?](#how-to-define-constants-in-react) |
|121| [How to programmatically trigger click event in React?](#how-to-programmatically-trigger-click-event-in-react) |
|122| [Is it possible to use async/await in plain React?](#is-it-possible-to-use-asyncawait-in-plain-react) |
|123| [What are the common folder structures for React?](#what-are-the-common-folder-structures-for-react) |
|124| [What are the popular packages for animation?](#what-are-the-popular-packages-for-animation) |
|125| [What is the benefit of styles modules?](#what-is-the-benefit-of-styles-modules) |
|126| [What are the popular React-specific linters?](#what-are-the-popular-react-specific-linters) |
|127| [How to make AJAX call and In which component lifecycle methods should I make an AJAX call?](#how-to-make-ajax-call-and-in-which-component-lifecycle-methods-should-i-make-an-ajax-call) |
|128| [What are render props?](#what-are-render-props) |
|   | **React Router** |
|129| [What is React Router?](#what-is-react-router) |
|130| [How React Router is different from history library?](#how-react-router-is-different-from-history-library) |
|131| [What are the \<Router> components of React Router v4?](#what-are-the-router-components-of-react-router-v4) |
|132| [What is the purpose of push and replace methods of history?](#what-is-the-purpose-of-push-and-replace-methods-of-history) |
|133| [How do you programmatically navigate using React router v4?](#how-do-you-programmatically-navigate-using-react-router-v4) |
|134| [How to get query parameters in React Router v4](#how-to-get-query-parameters-in-react-router-v4) |
|135| [Why you get "Router may have only one child element" warning?](#why-you-get-router-may-have-only-one-child-element-warning) |
|136| [How to pass params to history.push method in React Router v4?](#how-to-pass-params-to-historypush-method-in-react-router-v4) |
|137| [How to implement default or NotFound page?](#how-to-implement-default-or-notfound-page) |
|138| [How to get history on React Router v4?](#how-to-get-history-on-react-router-v4) |
|139| [How to perform automatic redirect after login?](#how-to-perform-automatic-redirect-after-login) |
|   | **React Internationalization** |
|140| [What is React-Intl?](#what-is-react-intl) |
|141| [What are the main features of React Intl?](#what-are-the-main-features-of-react-intl) |
|142| [What are the two ways of formatting in React Intl?](#what-are-the-two-ways-of-formatting-in-react-intl) |
|143| [How to use FormattedMessage as placeholder using React Intl?](#how-to-use-formattedmessage-as-placeholder-using-react-intl) |
|144| [How to access current locale with React Intl](#how-to-access-current-locale-with-react-intl) |
|145| [How to format date using React Intl?](#how-to-format-date-using-react-intl) |
|   | **React Testing** |
|146| [What is Shallow Renderer in React testing?](#what-is-shallow-renderer-in-react-testing) |
|147| [What is TestRenderer package in React?](#what-is-testrenderer-package-in-react) |
|148| [What is the purpose of ReactTestUtils package?](#what-is-the-purpose-of-reacttestutils-package) |
|149| [What is Jest?](#what-is-jest) |
|150| [What are the advantages of Jest over Jasmine?](#what-are-the-advantages-of-jest-over-jasmine) |
|151| [Give a simple example of Jest test case](#give-a-simple-example-of-jest-test-case) |
|   | **React Redux** |
|152| [What is Flux?](#what-is-flux) |
|153| [What is Redux?](#what-is-redux) |
|154| [What are the core principles of Redux?](#what-are-the-core-principles-of-redux) |
|155| [What are the downsides of Redux compared to Flux?](#what-are-the-downsides-of-redux-compared-to-flux) |
|156| [What is the difference between mapStateToProps() and mapDispatchToProps()?](#what-is-the-difference-between-mapstatetoprops-and-mapdispatchtoprops) |
|157| [Can I dispatch an action in reducer?](#can-i-dispatch-an-action-in-reducer) |
|158| [How to access Redux store outside a component?](#how-to-access-redux-store-outside-a-component) |
|159| [What are the drawbacks of MVW pattern](#what-are-the-drawbacks-of-mvw-pattern) |
|160| [Are there any similarities between Redux and RxJS?](#are-there-any-similarities-between-redux-and-rxjs) |
|161| [How to dispatch an action on load?](#how-to-dispatch-an-action-on-load) |
|162| [How to use connect from React Redux?](#how-to-use-connect-from-react-redux) |
|163| [How to reset state in Redux?](#how-to-reset-state-in-redux) |
|164| [Whats the purpose of at symbol in the redux connect decorator?](#whats-the-purpose-of-at-symbol-in-the-redux-connect-decorator) |
|165| [What is the difference between React context and React Redux?](#what-is-the-difference-between-react-context-and-react-redux) |
|166| [Why are Redux state functions called reducers?](#why-are-redux-state-functions-called-reducers) |
|167| [How to make AJAX request in Redux?](#how-to-make-ajax-request-in-redux) |
|168| [Should I keep all component's state in Redux store?](#should-i-keep-all-components-state-in-redux-store) |
|169| [What is the proper way to access Redux store?](#what-is-the-proper-way-to-access-redux-store) |
|170| [What is the difference between component and container in React Redux?](#what-is-the-difference-between-component-and-container-in-react-redux) |
|171| [What is the purpose of the constants in Redux? ](#what-is-the-purpose-of-the-constants-in-redux) |
|172| [What are the different ways to write mapDispatchToProps()?](#what-are-the-different-ways-to-write-mapdispatchtoprops) |
|173| [What is the use of the ownProps parameter in mapStateToProps() and mapDispatchToProps()?](#what-is-the-use-of-the-ownprops-parameter-in-mapstatetoprops-and-mapdispatchtoprops) |
|174| [How to structure Redux top level directories?](#how-to-structure-redux-top-level-directories) |
|175| [What is redux-saga?](#what-is-redux-saga) |
|176| [What is the mental model of redux-saga?](#what-is-the-mental-model-of-redux-saga) |
|177| [What are the differences between call and put in redux-saga](#what-are-the-differences-between-call-and-put-in-redux-saga) |
|178| [What is Redux Thunk?](#what-is-redux-thunk) |
|179| [What are the differences between redux-saga and redux-thunk](#what-are-the-differences-between-redux-saga-and-redux-thunk) |
|180| [What is Redux DevTools?](#what-is-redux-devtools) |
|181| [What are the features of Redux DevTools?](#what-are-the-features-of-redux-devtools) |
|182| [What are Redux selectors and Why to use them?](#what-are-redux-selectors-and-why-to-use-them) |
|183| [What is Redux Form?](#what-is-redux-form) |
|184| [What are the main features of Redux Form?](#what-are-the-main-features-of-redux-form) |
|185| [How to add multiple middlewares to Redux?](#how-to-add-multiple-middlewares-to-redux) |
|186| [How to set initial state in Redux?](#how-to-set-initial-state-in-redux) |
|187| [How Relay is different from Redux?](#how-relay-is-different-from-redux) |
|188| [What is an action in Redux?](#what-is-an-action-in-redux) |
|   | **React Native** |
|188| [What is the difference between React Native and React?](#what-is-the-difference-between-react-native-and-react) |
|189| [How to test React Native apps?](#how-to-test-react-native-apps) |
|190| [How to do logging in React Native?](#how-to-do-logging-in-react-native) |
|191| [How to debug your React Native?](#how-to-debug-your-react-native) |
|   | **React supported libraries and Integration** |
|192| [What is reselect and how it works?](#what-is-reselect-and-how-it-works) |
|193| [What is Flow?](#what-is-flow) |
|194| [What is the difference between Flow and PropTypes?](#what-is-the-difference-between-flow-and-proptypes) |
|195| [How to use font-awesome icons in React?](#how-to-use-font-awesome-icons-in-react) |
|196| [What is React Dev Tools?](#what-is-react-dev-tools) |
|197| [Why is DevTools not loading in Chrome for local files?](#why-is-devtools-not-loading-in-chrome-for-local-files) |
|198| [How to use Polymer in React?](#how-to-use-polymer-in-react) |
|199| [What are the advantages of React over Vue.js?](#what-are-the-advantages-of-react-over-vuejs) |
|200| [What is the difference between React and Angular?](#what-is-the-difference-between-react-and-angular) |
|201| [Why React tab is not showing up in DevTools?](#why-react-tab-is-not-showing-up-in-devtools) |
|202| [What are styled components?](#what-are-styled-components) |
|203| [Give an example of Styled Components?](#give-an-example-of-styled-components) |
|204| [What is Relay?](#what-is-relay) |
|205| [How to use TypeScript in create-react-app application?](#how-to-use-typescript-in-create-react-app-application) |
|   | **Miscellaneous** |
|206| [What are the main features of reselect library?](#what-are-the-main-features-of-reselect-library) |
|207| [Give an example of reselect usage?](#give-an-example-of-reselect-usage) |
|209| [Does the statics object work with ES6 classes in React?](#does-the-statics-object-work-with-es6-classes-in-react) |
|210| [Can Redux only be used with React?](#can-redux-only-be-used-with-react) |
|211| [Do you need to have a particular build tool to use Redux?](#do-you-need-to-have-a-particular-build-tool-to-use-redux) |
|212| [How Redux Form initialValues get updated from state?](#how-redux-form-initialvalues-get-updated-from-state) |
|213| [How React PropTypes allow different type for one prop?](#how-react-proptypes-allow-different-types-for-one-prop) |
|214| [Can I import an SVG file as react component?](#can-i-import-an-svg-file-as-react-component) |
|215| [Why are inline ref callbacks or functions not recommended?](#why-are-inline-ref-callbacks-or-functions-not-recommended)|
|216| [What is render hijacking in React?](#what-is-render-hijacking-in-react)|
|217| [What are HOC factory implementations?](#what-are-hoc-factory-implementations)|
|218| [How to pass numbers to React component?](#how-to-pass-numbers-to-react-component)|
|219| [Do I need to keep all my state into Redux? Should I ever use react internal state?](#do-i-need-to-keep-all-my-state-into-redux-should-i-ever-use-react-internal-state)|
|220| [What is the purpose of registerServiceWorker in React?](#what-is-the-purpose-of-registerserviceworker-in-react)|
|221| [What is React memo function?](#what-is-react-memo-function)|
|222| [What is React lazy function?](#what-is-react-lazy-function)|
|223| [How to prevent unnecessary updates using setState?](#how-to-prevent-unnecessary-updates-using-setstate)|
|224| [How do you render Array, Strings and Numbers in React 16 Version?](#how-do-you-render-array-strings-and-numbers-in-react-16-version)|
|225| [How to use class field declarations syntax in React classes?](#how-to-use-class-field-declarations-syntax-in-react-classes)|
|226| [What are hooks?](#what-are-hooks)|
|227| [What are the rules needs to follow for hooks?](#what-are-the-rules-needs-to-follow-for-hooks)|
|228| [How to ensure hooks followed the rules in your project?](#how-to-ensure-hooks-followed-the-rules-in-your-project)|
|229| [What are the differences between Flux and Redux?](#what-are-the-differences-between-flux-and-redux)|
|230| [What are the benefits of React Router V4?](#what-are-the-benefits-of-react-router-v4)|
|231| [Can you describe about componentDidCatch lifecycle method signature?](#can-you-describe-about-componentdidcatch-lifecycle-method-signature)|
|232| [In which scenarios error boundaries do not catch errors?](#in-which-scenarios-error-boundaries-do-not-catch-errors)|
|233| [Why do not you need error boundaries for event handlers?](#why-do-not-you-need-error-boundaries-for-event-handlers)|
|234| [What is the difference between try catch block and error boundaries?](#what-is-the-difference-between-try-catch-block-and-error-boundaries)|
|235| [What is the behavior of uncaught errors in react 16?](#what-is-the-behavior-of-uncaught-errors-in-react-16)|
|236| [What is the proper placement for error boundaries?](#what-is-the-proper-placement-for-error-boundaries)|
|237| [What is the benefit of component stack trace from error boundary?](#what-is-the-benefit-of-component-stack-trace-from-error-boundary)|
|238| [What is the required method to be defined for a class component?](#what-is-the-required-method-to-be-defined-for-a-class-component)|
|239| [What are the possible return types of render method?](#what-are-the-possible-return-types-of-render-method)|
|240| [What is the main purpose of constructor?](#what-is-the-main-purpose-of-constructor)|
|241| [Is it mandatory to define constructor for React component?](#is-it-mandatory-to-define-constructor-for-react-component)|
|242| [What are default props?](#what-are-default-props)|
|243| [Why should not call setState in componentWillUnmount?](#why-should-not-call-setstate-in-componentwillunmount)|
|244| [What is the purpose of getDerivedStateFromError?](#what-is-the-purpose-of-getderivedstatefromerror)|
|245| [What is the methods order when component re-rendered?](#what-is-the-methods-order-when-component-re-rendered)|
|246| [What are the methods invoked during error handling?](#what-are-the-methods-invoked-during-error-handling)|
|247| [What is the purpose of displayName class property?](#what-is-the-purpose-of-displayname-class-property)|
|248| [What is the browser support for react applications?](#what-is-the-browser-support-for-react-applications)|
|249| [What is the purpose of unmountComponentAtNode method?](#what-is-the-purpose-of-unmountcomponentatnode-method)|
|250| [What is code-splitting?](#what-is-code-splitting)|
|251| [What is the benefit of strict mode?](#what-is-the-benefit-of-strict-mode)|
|252| [What are Keyed Fragments?](#what-are-keyed-fragments)|
|253| [Does React support all HTML attributes?](#does-react-support-all-html-attributes)|
|254| [What are the limitations with HOCs?](#what-are-the-limitations-with-hocs)|
|255| [How to debug forwardRefs in DevTools?](#how-to-debug-forwardrefs-in-devtools)|
|256| [When component props defaults to true?](#when-component-props-defaults-to-true)|
|257| [What is NextJS and major features of it?](#what-is-nextjs-and-major-features-of-it)|
|258| [How do you pass an event handler to a component?](#how-do-you-pass-an-event-handler-to-a-component)|
|259| [Is it good to use arrow functions in render methods?](#is-it-good-to-use-arrow-functions-in-render-methods)|
|260| [How to prevent a function from being called multiple times?](#how-to-prevent-a-function-from-being-called-multiple-times)|
|261| [How JSX prevents Injection Attacks?](#how-jsx-prevents-injection-attacks)|
|262| [How do you update rendered elements?](#how-do-you-update-rendered-elements)|
|263| [How do you say that props are read only?](#how-do-you-say-that-props-are-read-only)|
|264| [How do you say that state updates are merged?](#how-do-you-say-that-state-updates-are-merged)|
|265| [How do you pass arguments to an event handler?](#how-do-you-pass-arguments-to-an-event-handler)|
|266| [How to prevent component from rendering?](#how-to-prevent-component-from-rendering)|
|267| [What are the conditions to safely use the index as a key?](#what-are-the-conditions-to-safely-use-the-index-as-a-key)|
|268| [Is it keys should be globally unique?](#is-it-keys-should-be-globally-unique)|
|269| [What is the popular choice for form handling?](#what-is-the-popular-choice-for-form-handling)|
|270| [What are the advantages of formik over redux form library?](#what-are-the-advantages-of-formik-over-redux-form-library)|
|271| [Why do you not required to use inheritance?](#why-do-you-not-required-to-use-inheritance)|
|272| [Can I use web components in react application?](#can-i-use-web-components-in-react-application)|
|273| [What is dynamic import?](#what-is-dynamic-import)|
|274| [What are loadable components?](#what-are-loadable-components)|
|275| [What is suspense component?](#what-is-suspense-component)|
|276| [What is route based code splitting?](#what-is-route-based-code-splitting)|
|277| [Give an example on How to use context?](#give-an-example-on-how-to-use-context)|
|278| [What is the purpose of default value in context?](#what-is-the-purpose-of-default-value-in-context)|
|279| [How do you use contextType?](#how-do-you-use-contexttype)|
|280| [What is a consumer?](#what-is-a-consumer)|
|281| [How do you solve performance corner cases while using context?](#how-do-you-solve-performance-corner-cases-while-using-context)|
|282| [What is the purpose of forward ref in HOCs?](#what-is-the-purpose-of-forward-ref-in-hocs)|
|283| [Is it ref argument available for all functions or class components?](#is-it-ref-argument-available-for-all-functions-or-class-components)|
|284| [Why do you need additional care for component libraries while using forward refs?](#why-do-you-need-additional-care-for-component-libraries-while-using-forward-refs)|
|285| [How to create react class components without ES6?](#how-to-create-react-class-components-without-es6)|
|286| [Is it possible to use react without JSX?](#is-it-possible-to-use-react-without-jsx)|
|287| [What is diffing algorithm?](#what-is-diffing-algorithm)|
|288| [What are the rules covered by diffing algorithm?](#what-are-the-rules-covered-by-diffing-algorithm)|
|289| [When do you need to use refs?](#when-do-you-need-to-use-refs)|
|290| [Is it prop must be named as render for render props?](#is-it-prop-must-be-named-as-render-for-render-props)|
|291| [What are the problems of using render props with pure components?](#what-are-the-problems-of-using-render-props-with-pure-components)|
|292| [How do you create HOC using render props?](#how-do-you-create-hoc-using-render-props)|
|293| [What is windowing technique?](#what-is-windowing-technique)|
|294| [How do you print falsy values in JSX?](#how-do-you-print-falsy-values-in-jsx)|
|295| [What is the typical use case of portals?](#what-is-the-typical-use-case-of-portals?)|
|296| [How do you set default value for uncontrolled component?](#how-do-you-set-default-value-for-uncontrolled-component)|
|297| [What is your favorite React stack?](#what-is-your-favorite-react-stack)|
|298| [What is the difference between Real DOM and Virtual DOM?](#what-is-the-difference-between-real-dom-and-virtual-dom)|
|299| [How to add Bootstrap to a react application?](#how-to-add-bootstrap-to-a-react-application)|
|300| [Can you list down top websites or applications using react as front end framework?](#can-you-list-down-top-websites-or-applications-using-react-as-front-end-framework)|
|301| [Is it recommended to use CSS In JS technique in React?](#is-it-recommended-to-use-css-in-js-technique-in-react)|
|302| [Do I need to rewrite all my class components with hooks?](#do-i-need-to-rewrite-all-my-class-components-with-hooks)|
|303| [How to fetch data with React Hooks?](#how-to-fetch-data-with-react-hooks)|
|304| [Is Hooks cover all use cases for classes?](#is-hooks-cover-all-use-cases-for-classes)|
|305| [What is the stable release for hooks support?](#what-is-the-stable-release-for-hooks-support)|
|306| [Why do we use array destructuring (square brackets notation) in useState?](#why-do-we-use-array-destructuring-square-brackets-notation-in-usestate)|
|307| [What are the sources used for introducing hooks?](#what-are-the-sources-used-for-introducing-hooks)|
|308| [How do you access imperative API of web components?](#how-do-you-access-imperative-api-of-web-components)|
|309| [What is formik?](#what-is-formik)|
|310| [What are typical middleware choices for handling asynchronous calls in Redux?](#what-are-typical-middleware-choices-for-handling-asynchronous-calls-in-redux)|
|311| [Do browsers understand JSX code?](#do-browsers-understand-jsx-code)|
|312| [Describe about data flow in react?](#describe-about-data-flow-in-react)|
|313| [What is react scripts?](#what-is-react-scripts)|
|314| [What are the features of create react app?](#what-are-the-features-of-create-react-app)|
|315| [What is the purpose of renderToNodeStream method?](#what-is-the-purpose-of-rendertonodestream-method)|
|316| [What is MobX?](#what-is-mobx)|
|317| [What are the differences between Redux and MobX?](#what-are-the-differences-between-redux-and-mobx)|
|318| [Should I learn ES6 before learning ReactJS?](#should-i-learn-es6-before-learning-reactjs)|
|319| [What is Concurrent Rendering?](#what-is-concurrent-rendering)|
|320| [What is the difference between async mode and concurrent mode?](#what-is-the-difference-between-async-mode-and-concurrent-mode)|
|321| [Can I use javascript urls in react16.9?](#can-i-use-javascript-urls-in-react169)|
|322| [What is the purpose of eslint plugin for hooks?](#what-is-the-purpose-of-eslint-plugin-for-hooks)|
|323| [What is the difference between Imperative and Declarative in React?](#what-is-the-difference-between-imperative-and-declarative-in-react)|
|324| [What are the benefits of using typescript with reactjs?](#what-are-the-benefits-of-using-typescript-with-reactjs)|
|325| [How do you make sure that user remains authenticated on page refresh while using Context API State Management?](#how-do-you-make-sure-that-user-remains-authenticated-on-page-refresh-while-using-context-api-state-management)|

## Core React


    
1. ### What is React?

    React is an **open-source frontend JavaScript library** which is used for building user interfaces especially for single page applications. It is used for handling view layer for web and mobile apps. React was created by [Jordan Walke](https://github.com/jordwalke), a software engineer working for Facebook. React was first deployed on Facebook's News Feed in 2011 and on Instagram in 2012.


   **[⬆ Back to Top](#table-of-contents)**
    
2. ### What are the major features of React?

    The major features of React are:

    * It uses **VirtualDOM** instead of RealDOM considering that RealDOM manipulations are expensive.
    * Supports **server-side rendering**.
    * Follows **Unidirectional** data flow or data binding.
    * Uses **reusable/composable** UI components to develop the view.


   **[⬆ Back to Top](#table-of-contents)**
    
3. ### What is JSX?

    *JSX* is a XML-like syntax extension to ECMAScript (the acronym stands for *JavaScript XML*). Basically it just provides syntactic sugar for the `React.createElement()` function, giving us expressiveness of JavaScript along with HTML like template syntax.

    In the example below text inside `<h1>` tag is returned as JavaScript function to the render function.

    ```jsx harmony
    class App extends React.Component {
      render() {
        return(
          <div>
            <h1>{'Welcome to React world!'}</h1>
          </div>
        )
      }
    }
    ```


   **[⬆ Back to Top](#table-of-contents)**
    
4. ### What is the difference between Element and Component?

    An *Element* is a plain object describing what you want to appear on the screen in terms of the DOM nodes or other components. *Elements* can contain other *Elements* in their props. Creating a React element is cheap. Once an element is created, it is never mutated.

    The object representation of React Element would be as follows:

    ```javascript
    const element = React.createElement(
      'div',
      {id: 'login-btn'},
      'Login'
    )
    ```

    The above `React.createElement()` function returns an object:

    ```
    {
      type: 'div',
      props: {
        children: 'Login',
        id: 'login-btn'
      }
    }
    ```

    And finally it renders to the DOM using `ReactDOM.render()`:

    ```html
    <div id='login-btn'>Login</div>
    ```

    Whereas a **component** can be declared in several different ways. It can be a class with a `render()` method. Alternatively, in simple cases, it can be defined as a function. In either case, it takes props as an input, and returns a JSX tree as the output:

    ```javascript
    const Button = ({ onLogin }) =>
      <div id={'login-btn'} onClick={onLogin}>Login</div>
    ```

    Then JSX gets transpiled to a `React.createElement()` function tree:

    ```javascript
    const Button = ({ onLogin }) => React.createElement(
      'div',
      { id: 'login-btn', onClick: onLogin },
      'Login'
    )
    ```


   **[⬆ Back to Top](#table-of-contents)**
    
5. ### How to create components in React?

    There are two possible ways to create a component.

    1. **Function Components:** This is the simplest way to create a component. Those are pure JavaScript functions that accept props object as first parameter and return React elements:

        ```jsx harmony
        function Greeting({ message }) {
          return <h1>{`Hello, ${message}`}</h1>

        }
        ```

    2. **Class Components:** You can also use ES6 class to define a component. The above function component can be written as:

        ```jsx harmony
        class Greeting extends React.Component {
          render() {
            return <h1>{`Hello, ${this.props.message}`}</h1>
          }
        }
        ```


   **[⬆ Back to Top](#table-of-contents)**
    
6. ### When to use a Class Component over a Function Component?

    If the component needs *state or lifecycle methods* then use class component otherwise use function component.
    *However, from React 16.8 with the addition of Hooks, you could use state , lifecycle  methods and other features that were only available in class component right in your function component.*


   **[⬆ Back to Top](#table-of-contents)**
    
7. ### What are Pure Components?

    *`React.PureComponent`* is exactly the same as *`React.Component`* except that it handles the `shouldComponentUpdate()` method for you. When props or state changes, *PureComponent* will do a shallow comparison on both props and state. *Component* on the other hand won't compare current props and state to next out of the box. Thus, the component will re-render by default whenever `shouldComponentUpdate` is called.


   **[⬆ Back to Top](#table-of-contents)**
    
8. ### What is state in React?

    *State* of a component is an object that holds some information that may change over the lifetime of the component. We should always try to make our state as simple as possible and minimize the number of stateful components.

    Let's create an user component with message state,


    ```jsx harmony
    class User extends React.Component {
      constructor(props) {
        super(props)

        this.state = {
          message: 'Welcome to React world'
        }
      }

      render() {
        return (
          <div>
            <h1>{this.state.message}</h1>
          </div>
        )
      }
    }
    ```

    ![state](images/state.jpg)

    State is similar to props, but it is private and fully controlled by the component. i.e, It is not accessible to any component other than the one that owns and sets it.


   **[⬆ Back to Top](#table-of-contents)**
    
9. ### What are props in React?

    *Props* are inputs to components. They are single values or objects containing a set of values that are passed to components on creation using a naming convention similar to HTML-tag attributes. They are data passed down from a parent component to a child component.

    The primary purpose of props in React is to provide following component functionality:

    1. Pass custom data to your component.
    2. Trigger state changes.
    3. Use via `this.props.reactProp` inside component's `render()` method.

    For example, let us create an element with `reactProp` property:

    ```jsx harmony
    <Element reactProp={'1'} />
    ```

    This `reactProp` (or whatever you came up with) name then becomes a property attached to React's native props object which originally already exists on all components created using React library.

    ```
    props.reactProp
    ```


   **[⬆ Back to Top](#table-of-contents)**
    
10. ### What is the difference between state and props?

    Both *props* and *state* are plain JavaScript objects. While both of them hold information that influences the output of render, they are different in their functionality with respect to component. Props get passed to the component similar to function parameters whereas state is managed within the component similar to variables declared within a function.


   **[⬆ Back to Top](#table-of-contents)**
    
11. ### Why should we not update the state directly?

    If you try to update state directly then it won't re-render the component.

    ```javascript
    //Wrong
    this.state.message = 'Hello world'
    ```

    Instead use `setState()` method. It schedules an update to a component's state object. When state changes, the component responds by re-rendering.

    ```javascript
    //Correct
    this.setState({ message: 'Hello World' })
    ```

    **Note:** You can directly assign to the state object either in *constructor* or using latest javascript's class field declaration syntax.


   **[⬆ Back to Top](#table-of-contents)**
