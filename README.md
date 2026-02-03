<h1><span>EU Inc. CSS Masonry</span></h1>
<ol>
    <li><a href="https://www.eu-inc.org">EU Inc</a> has a good Lighthouse score, but leaves a spinner for 70MB of images in a JS widget iframe (which is technically til first paint)</li>
    <li>In this example, the image gallery JSON is grabbed from the <a href="https://apps.elfsight.com/widget/076494aa-6dca-49ce-beca-23071b573eda">image gallery iframe widget</a> instead</li>
    <li>The same masonry layout is rendered using CSS grid columns and media queries, since the current CSS masonry feature is <a href="https://caniuse.com/?search=masonry">minimally supported</a></li>
    <li>Images use <a href="https://developer.mozilla.org/en-US/docs/Web/Performance/Guides/Lazy_loading">lazy-loading</a> and <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Attributes/fetchpriority">fetch-priority</a> attributes, to lessen 70MB effect on loading performance (ideally this is rendered server-side first, but fine for a dynamic gallery)</li>
    <li>The hats and famous people are cool, but ideally I'd just like to be able to register a company in <a href="https://proposal.eu-inc.org/">48 hours and with 1EUR of assets</a></li>
</ol>

<ul>
	<li><a href="https://autr.github.io/eu-inc-masonry/">View Example</a></li>
	<li><a href="https://autr.github.io/eu-inc-masonry/">View Source</a></li>
	<li><a href="https://web-directive.eu/">Web Accessibility Directive</a></li>
</ul>