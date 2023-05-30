# css-minifier-api
a Css minifier api
<div id="css_api" class="code">
			<h2>Css minifier api</h2>
			<div class="code-body">
				<div class="endpoint">
					<b>Endpoint : </b>
					<code>https://iysabox.com/api/css-minifier</code>
				</div>
				<b>Request :</b>
				<code>
<pre>$.ajax({
    type: "POST",
    url: "https://iysabox.com/api/css-minifier",
    data: {
        'css' : "css code here"
    },
    success: function(msg){
        console.log(msg.minified_css)
    }
})
</pre>
				</code>
			</div>
		</div>
