<!DOCTYPE html><html><head><title>EaseInterpolator</title><meta charset='utf-8'><link href='https://dn-maxiang.qbox.me/res-min/themes/marxico.css' rel='stylesheet'></head><body><div id='preview-contents' class='note-content'>
                        <div id="wmd-preview" class="preview-content"></div>
                    <div id="wmd-preview-section-206" class="wmd-preview-section preview-content">

</div><div id="wmd-preview-section-207" class="wmd-preview-section preview-content">

<h1 id="easeinterpolator">EaseInterpolator</h1>

<p> <br>
Thirty different easing animation interpolators for Android.</p>

</div><div id="wmd-preview-section-208" class="wmd-preview-section preview-content">

<h2 id="demo">Demo</h2>

</div><div id="wmd-preview-section-209" class="wmd-preview-section preview-content">

<h2 id="installation">Installation</h2>

<p>In order to use the library, there are 2 options: <br>
<strong>1. Add jar file as library</strong><code>(Recommend)</code></p>

<ul><li>Download the <a href="https://github.com/cimi-chen/EaseInterpolator/blob/master/libs/ease-interpolator-1.0.jar?raw=true" target="_blank"><strong>latest .jar file</strong></a>.</li>
<li>Copy the <strong>ease-interpolator-.jar</strong> file into the <code>libs</code> folder of your Android application project.</li>
<li>Start using the library.</li>
</ul>

<p><strong>2. Clone whole repository</strong></p>

<ul><li>Open your <strong>commandline-input</strong> and navigate to your desired destination folder (where you want to put the library).</li>
<li>Use the command <code>git clone https://github.com/cimi-chen/EaseInterpolator</code> to download the full <strong>EaseInterpolator</strong> repository to your computer (this includes the folder of the library project as well as the demo project).</li>
<li>Import the library folder (<code>EaseInterpolatorLib</code>) into your workspace.</li>
<li>Add it as a reference to your project.</li>
</ul>

</div><div id="wmd-preview-section-210" class="wmd-preview-section preview-content">

<h2 id="usage">Usage</h2>

</div><div id="wmd-preview-section-211" class="wmd-preview-section preview-content">

<pre class="prettyprint hljs-dark"><code class="language-java hljs">    Interpolator interpolator = <span class="hljs-keyword">new</span> EaseBounceInInterpolator();
    Animation anim = <span class="hljs-keyword">new</span> TranslateAnimation(<span class="hljs-number">0</span>, <span class="hljs-number">0</span>, <span class="hljs-number">0</span>, <span class="hljs-number">200</span>);
    anim.setDuration(<span class="hljs-number">1200</span>);
    anim.setInterpolator(interpolator);
    view.startAnimation(anim);</code></pre>

</div><div id="wmd-preview-section-212" class="wmd-preview-section preview-content">

<h2 id="license">License</h2>

<p>Copyright 2015 <a href="https://github.com/cimi-chen" target="_blank">cimi-chen</a></p>

<p>Licensed under the Apache License, Version 2.0 (the “License”); you may not use this file except in compliance with the License. You may obtain a copy of the License at <a href="http://www.apache.org/licenses/LICENSE-2.0" target="_blank">LICENSE-2.0</a></p>

<p>Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an “AS IS” BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.</p></div><div id="wmd-preview-section-footnotes" class="preview-content"></div></div></body></html>