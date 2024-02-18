  PA React Themes    

If you find "Diff Highlight" that uses Prism complicated, this is a much easier alternative...
----------------------------------------------------------------------------------------------

  
  

* * *

  
  

Code with "Default Prism Diff Highlight"
----------------------------------------

    

With line numbers (Add class="line-numbers")

    @@ -4,6 +4,5 @@
    -    let foo = bar.baz([1, 2, 3]);
    -    foo = foo + 1;
    +    const foo = bar.baz([1, 2, 3]) + 1;
         console.log(\`foo: \${foo}\`);

Without line numbers (Remove class="line-numbers")

    @@ -4,6 +4,5 @@
    -    let foo = bar.baz([1, 2, 3]);
    -    foo = foo + 1;
    +    const foo = bar.baz([1, 2, 3]) + 1;
         console.log(\`foo: \${foo}\`);

  
  

* * *

  
  

Code with "Diff Highlight Pro"
------------------------------

    
    <pre data-line-red="2,3" data-line-green="4" data-line-yellow="5" class="line-numbers">
    <code class="language-javascript">
        @@ -4,6 +4,5 @@
            let foo = bar.baz([1, 2, 3]);
            foo = foo + 1;
            const foo = bar.baz([1, 2, 3]) + 1;
                console.log(`foo: ${foo}`);
    </code>
    </pre>
    

With line numbers (Add class="line-numbers")

    
    @@ -4,6 +4,5 @@
        let foo = bar.baz([1, 2, 3]);
        foo = foo + 1;
        const foo = bar.baz([1, 2, 3]) + 1;
            console.log(\`foo: \${foo}\`);
    

Without line numbers (Remove class="line-numbers")

    
    @@ -4,6 +4,5 @@
        let foo = bar.baz([1, 2, 3]);
        foo = foo + 1;
        const foo = bar.baz([1, 2, 3]) + 1;
            console.log(\`foo: \${foo}\`);
    

  
  

* * *

  
  

Mode of Use
-----------

  

Add:

<link rel="stylesheet" href="./css/diff-highlight-pro.css">  
<script src="./js/diff-highlight-pro.js">  
  

data-line-red="" for red lines

data-line-green="" for green lines

data-line-yellow="" for yellow lines

  

Single line --> 4

Two lines --> 4,8

Range --> 4-6

Mixed --> 4,6-7

  

    
    <pre data-line-red="2,3" data-line-green="4" data-line-yellow="5" class="line-numbers">
    <code class="language-javascript">
        Your Code...
    </code>
    </pre>  PA React Themes    

If you find "Diff Highlight" that uses Prism complicated, this is a much easier alternative...
----------------------------------------------------------------------------------------------

  
  

* * *

  
  

Code with "Default Prism Diff Highlight"
----------------------------------------

    

With line numbers (Add class="line-numbers")

    @@ -4,6 +4,5 @@
    -    let foo = bar.baz([1, 2, 3]);
    -    foo = foo + 1;
    +    const foo = bar.baz([1, 2, 3]) + 1;
         console.log(\`foo: \${foo}\`);

Without line numbers (Remove class="line-numbers")

    @@ -4,6 +4,5 @@
    -    let foo = bar.baz([1, 2, 3]);
    -    foo = foo + 1;
    +    const foo = bar.baz([1, 2, 3]) + 1;
         console.log(\`foo: \${foo}\`);

  
  

* * *

  
  

Code with "Diff Highlight Pro"
------------------------------

    
    <pre data-line-red="2,3" data-line-green="4" data-line-yellow="5" class="line-numbers">
    <code class="language-javascript">
        @@ -4,6 +4,5 @@
            let foo = bar.baz([1, 2, 3]);
            foo = foo + 1;
            const foo = bar.baz([1, 2, 3]) + 1;
                console.log(`foo: ${foo}`);
    </code>
    </pre>
    

With line numbers (Add class="line-numbers")

    
    @@ -4,6 +4,5 @@
        let foo = bar.baz([1, 2, 3]);
        foo = foo + 1;
        const foo = bar.baz([1, 2, 3]) + 1;
            console.log(\`foo: \${foo}\`);
    

Without line numbers (Remove class="line-numbers")

    
    @@ -4,6 +4,5 @@
        let foo = bar.baz([1, 2, 3]);
        foo = foo + 1;
        const foo = bar.baz([1, 2, 3]) + 1;
            console.log(\`foo: \${foo}\`);
    

  
  

* * *

  
  

Mode of Use
-----------

  

Add:

&lt;link rel="stylesheet" href="./css/diff-highlight-pro.css">  
&lt;script src="./js/diff-highlight-pro.js">  
  

data-line-red="" for red lines

data-line-green="" for green lines

data-line-yellow="" for yellow lines

  

Single line --> 4

Two lines --> 4,8

Range --> 4-6

Mixed --> 4,6-7

  

    
    <pre data-line-red="2,3" data-line-green="4" data-line-yellow="5" class="line-numbers">
    <code class="language-javascript">
        Your Code...
    </code>
    </pre>