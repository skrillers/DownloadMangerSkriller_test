<div role="tabpanel" class="tab-pane active" id="gradle">
                              <p>Add it in your root build.gradle at the end of repositories:</p>
                            <pre class="kode language-css code-toolbar"><code class=" kode language-css">	<span class="token selector">allprojects</span> <span class="token punctuation">{</span>
		<span class="token selector">repositories</span> <span class="token punctuation">{</span>
			<span class="token selector">...
			maven</span> <span class="token punctuation">{</span> url <span class="token string">'https://jitpack.io'</span> <span class="token punctuation">}</span>
		<span class="token punctuation">}</span>
	<span class="token punctuation">}</span></code></pre>
                        </div>
                        
                        <div class="row">
			<div class="col-lg-8">
								<p><b>Step 2.</b> Add the dependency</p> 
			</div>
			<div class="col-lg-2 text-right">
				<div class="dropdown" id="subprojects" style="display: none;">
					  <button class="btn btn-default dropdown-toggle" type="button" id="moduleDropdown" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">
					    Subproject
					    <span class="caret"></span>
					  </button>
					  <ul class="dropdown-menu" aria-labelledby="moduleDropdown" id="modulesList"></ul>
				</div>
			</div>
		</div>
    <div class="row">
			<div class="col-lg-10">

				<div role="tabpanel">
					<div class="tab-content depTabs">
					   <div role="tabpanel" class="tab-pane depTab gradle active">
                            <pre class="kode code-toolbar  language-css"><code id="depCodeGradle" class=" kode  language-css">	<span class="token selector">dependencies</span> <span class="token punctuation">{</span>
	        implementation <span class="token string">'com.github.skrillers:DownloadMangerSkriller_test:v1.0'</span>
	<span class="token punctuation">}</span>
</code></pre>
                        </div>
                        
						<div role="tabpanel" class="tab-pane depTab maven">
							<pre class="kode code-toolbar  language-markup"><code id="depCode" class="kode  language-markup">	<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>dependency</span><span class="token punctuation">&gt;</span></span>
	    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>groupId</span><span class="token punctuation">&gt;</span></span>com.github.skrillers<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>groupId</span><span class="token punctuation">&gt;</span></span>
	    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>artifactId</span><span class="token punctuation">&gt;</span></span>DownloadMangerSkriller_test<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>artifactId</span><span class="token punctuation">&gt;</span></span>
	    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>version</span><span class="token punctuation">&gt;</span></span>v1.0<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>version</span><span class="token punctuation">&gt;</span></span>
	<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>dependency</span><span class="token punctuation">&gt;</span></span>
</code></pre>
						</div>

						<div role="tabpanel" class="tab-pane depTab sbt">
                            <pre class="kode code-toolbar  language-css"><code id="depCodeSbt" class="kode  language-css">	
	libraryDependencies += <span class="token string">"com.github.skrillers"</span> % <span class="token string">"DownloadMangerSkriller_test"</span> % <span class="token string">"v1.0"</span>	
</code></pre>
                        </div>
                        
                        <div role="tabpanel" class="tab-pane depTab lein">
                            <pre class="kode code-toolbar  language-css"><code id="depCodeLein" class="kode  language-css">	
	<span class="token punctuation">:</span>dependencies [[com.github.skrillers/DownloadMangerSkriller_test <span class="token string">"v1.0"</span>]]	
</code></pre>
                        </div>
					</div>
				</div>
			</div>
</div>
