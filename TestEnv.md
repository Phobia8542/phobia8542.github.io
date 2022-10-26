<picture>
 <source media="(prefers-color-scheme: dark)" srcset="YOUR-DARKMODE-IMAGE">
 <source media="(prefers-color-scheme: light)" srcset="YOUR-LIGHTMODE-IMAGE">
 <img alt="YOUR-ALT-TEXT" src="YOUR-DEFAULT-IMAGE">
</picture>
# Testing how comments work in markdown
<> (This was another example)
<!--- This is the only comment that actually changed colours. Take note of the triple dash.
-->
{% comment %} 
    Jekyll comment method
{% endcomment %}