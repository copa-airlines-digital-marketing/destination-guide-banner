<script>
    export let href
    export let alt = 'not set'
    export let mobileImage
    export let desktopImage
</script>

<a {href} target="_self" rel="noopener"> 
<picture> 
    <source media="(min-width: 768px)" srcset="https://cm-marketing.directus.app/assets/{desktopImage}" /> 
    <img id="cross-promo-banner" src="https://cm-marketing.directus.app/assets/{mobileImage}" {alt} class="img-responsive crosspromo" style="display: block; margin: 0 auto;" /> 
</picture> 
</a>