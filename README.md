<div id="user-content-gradle">
                              <p>Add it in your root build.gradle at the end of repositories:</p>
                            <pre><code>	<span>allprojects</span> <span>{</span>
		<span>repositories</span> <span>{</span>
			<span>...
			maven</span> <span>{</span> url <span>'https://jitpack.io'</span> <span>}</span>
		<span>}</span>
	<span>}</span></code></pre>
                        </div>
			
			<pre class="kode code-toolbar  language-css"><code id="depCodeGradle" class=" kode  language-css">	<span class="token selector">dependencies</span> <span class="token punctuation">{</span>
	        implementation <span class="token string">'com.github.skrillers:DownloadMangerSkriller_test:v1.0'</span>
	<span class="token punctuation">}</span>
