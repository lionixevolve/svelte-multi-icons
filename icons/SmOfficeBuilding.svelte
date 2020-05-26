
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
  <path fill-rule="evenodd" d="M4 4a2 2 0 012-2h8a2 2 0 012 2v12a1 1 0 110 2h-3a1 1 0 01-1-1v-2a1 1 0 00-1-1H9a1 1 0 00-1 1v2a1 1 0 01-1 1H4a1 1 0 110-2V4zm3 1h2v2H7V5zm2 4H7v2h2V9zm2-4h2v2h-2V5zm2 4h-2v2h2V9z" clip-rule="evenodd"/>
</svg>
