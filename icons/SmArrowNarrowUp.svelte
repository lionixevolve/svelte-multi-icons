
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
  <path fill-rule="evenodd" d="M5.293 7.707a1 1 0 010-1.414l4-4a1 1 0 011.414 0l4 4a1 1 0 01-1.414 1.414L11 5.414V17a1 1 0 11-2 0V5.414L6.707 7.707a1 1 0 01-1.414 0z" clip-rule="evenodd"/>
</svg>
