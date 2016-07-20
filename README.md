syntaxed-plugin
===============

[![Code Climate](https://codeclimate.com/repos/578f1aa0a807416f490006c6/badges/2d92ff9b148a6334118a/gpa.svg)](https://codeclimate.com/repos/578f1aa0a807416f490006c6/feed)
##A simple code syntax highlighter for October CMS.


The plugin includes prism syntax highlighter on your pages. Add the component to your page and render it with the component tag:

```php
{% component 'syntaxed' %}
```

The only Component Setting is theme. You can select different themes. 

All code syntax goes in the CMS markup as shown below:

<p> CSS Highlighted Code </p>

```
<pre><code class="language-css">div { background-color: gray }</code></pre>
```

<p> PHP Highlighted Code </p>

```
<pre><code class="language-php">
    class Person{
        
        public $name;
        public $age;
        
        function Person(){
            $this->name = $name;
            $this->age = $age;
        }
    }
</code></pre>
```
Link to Github Repository
<a href="https://github.com/karingisi/syntaxed">https://github.com/karingisi/syntaxed</a>
