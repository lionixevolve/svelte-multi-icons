
<script>
   export let size = "100%";
   let customClass = "";
   export { customClass as class };

   if (size !== "100%") {
   size = size.slice(-1) === 'x' 
         ? size.slice(0, size.length -1) + 'em'
         : parseInt(size) + 'px';
   }
</script>

<svg width={size} height={size} class='hero {customClass}' viewBox="0 0 20 20" fill="currentColor">
  <path d="M3 3a1 1 0 000 2h11a1 1 0 100-2H3zM3 7a1 1 0 000 2h7a1 1 0 100-2H3zM3 11a1 1 0 100 2h4a1 1 0 100-2H3zM15 8a1 1 0 10-2 0v5.586l-1.293-1.293a1 1 0 00-1.414 1.414l3 3a1 1 0 001.414 0l3-3a1 1 0 00-1.414-1.414L15 13.586V8z"/>
</svg>
