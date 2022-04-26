# How to setup IntellJ Idea Community Edition


## Contents

<ol>
    <li><a href="#setup">Setup Intellij editor</a></li>
    <li><a href="#download">download</a></li>
</ol>


<div id="setup">something</div>

```code
Click Customize:

Click on Editor -> General -> Auto import -> check(
                            'add unambiguous imports on the fly',
                            'optimize imports on the fly'
)


Code folding -> uncheck(
            'imports',
             'one-line methods',
              'closures',
               'Generic constructor and method parameters'
)

General -> Appearance -> check('show line numbers')
```

## <div id="download">Download JDK</div>

Since we're working from a cloned project, we will not encounter the option to download the JDK.
Since we are working on a clean system each time we log in. So we'll have to select the following

```code
Projects -> New Project -> JDK -> Download JDK('corretto-11 java version "11.0.15"')
```
