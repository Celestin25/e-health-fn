
<!doctype html>
<html lang="en">

<head>
    <title>Code coverage report for Check.tsx</title>
    <meta charset="utf-8" />
    <link rel="stylesheet" href="prettify.css" />
    <link rel="stylesheet" href="base.css" />
    <link rel="shortcut icon" type="image/x-icon" href="favicon.png" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <style type='text/css'>
        .coverage-summary .sorter {
            background-image: url(sort-arrow-sprite.png);
        }
    </style>
</head>
    
<body>
<div class='wrapper'>
    <div class='pad1'>
        <h1><a href="index.html">All files</a> Check.tsx</h1>
        <div class='clearfix'>
            
            <div class='fl pad1y space-right2'>
                <span class="strong">100% </span>
                <span class="quiet">Statements</span>
                <span class='fraction'>3/3</span>
            </div>
        
            
            <div class='fl pad1y space-right2'>
                <span class="strong">50% </span>
                <span class="quiet">Branches</span>
                <span class='fraction'>1/2</span>
            </div>
        
            
            <div class='fl pad1y space-right2'>
                <span class="strong">100% </span>
                <span class="quiet">Functions</span>
                <span class='fraction'>1/1</span>
            </div>
        
            
            <div class='fl pad1y space-right2'>
                <span class="strong">100% </span>
                <span class="quiet">Lines</span>
                <span class='fraction'>3/3</span>
            </div>
        
            
        </div>
        <p class="quiet">
            Press <em>n</em> or <em>j</em> to go to the next uncovered block, <em>b</em>, <em>p</em> or <em>k</em> for the previous block.
        </p>
        <template id="filterTemplate">
            <div class="quiet">
                Filter:
                <input type="search" id="fileSearch">
            </div>
        </template>
    </div>
    <div class='status-line high'></div>
    <pre><table class="coverage">
<tr><td class="line-count quiet"><a name='L1'></a><a href='#L1'>1</a>
<a name='L2'></a><a href='#L2'>2</a>
<a name='L3'></a><a href='#L3'>3</a>
<a name='L4'></a><a href='#L4'>4</a>
<a name='L5'></a><a href='#L5'>5</a>
<a name='L6'></a><a href='#L6'>6</a>
<a name='L7'></a><a href='#L7'>7</a>
<a name='L8'></a><a href='#L8'>8</a>
<a name='L9'></a><a href='#L9'>9</a>
<a name='L10'></a><a href='#L10'>10</a>
<a name='L11'></a><a href='#L11'>11</a>
<a name='L12'></a><a href='#L12'>12</a>
<a name='L13'></a><a href='#L13'>13</a>
<a name='L14'></a><a href='#L14'>14</a>
<a name='L15'></a><a href='#L15'>15</a>
<a name='L16'></a><a href='#L16'>16</a>
<a name='L17'></a><a href='#L17'>17</a>
<a name='L18'></a><a href='#L18'>18</a>
<a name='L19'></a><a href='#L19'>19</a>
<a name='L20'></a><a href='#L20'>20</a>
<a name='L21'></a><a href='#L21'>21</a></td><td class="line-coverage quiet"><span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-yes">1x</span>
<span class="cline-any cline-yes">2x</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-yes">2x</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span>
<span class="cline-any cline-neutral">&nbsp;</span></td><td class="text"><pre class="prettyprint lang-js">import React, { useState } from "react";
&nbsp;
const Check = () =&gt; {
  const [showExtra, setShowExtra] = useState(false);
&nbsp;
  return (
    &lt;div className="flex flex-col items-start font-poppins text-sm"&gt;
      &lt;h1 className="text-gray-800"&gt;
        If you want to part of the program click button below
      &lt;/h1&gt;
      &lt;button className="py-2 px-7 ml-10 mt-5 bg-purple-700 text-white rounded-md hover:bg-purple-500"&gt;
        Confirm
      &lt;/button&gt;
      &lt;h1&gt;hello there&lt;/h1&gt;
      {showExtra &amp;&amp; <span class="branch-1 cbranch-no" title="branch not covered" >&lt;h2&gt;You are welcome&lt;/h2&gt;}</span>
    &lt;/div&gt;
  );
};
&nbsp;
export default Check;
&nbsp;</pre></td></tr></table></pre>

                <div class='push'></div><!-- for sticky footer -->
            </div><!-- /wrapper -->
            <div class='footer quiet pad2 space-top1 center small'>
                Code coverage generated by
                <a href="https://istanbul.js.org/" target="_blank" rel="noopener noreferrer">istanbul</a>
                at 2024-06-26T14:18:54.854Z
            </div>
        <script src="prettify.js"></script>
        <script>
            window.onload = function () {
                prettyPrint();
            };
        </script>
        <script src="sorter.js"></script>
        <script src="block-navigation.js"></script>
    </body>
</html>
    