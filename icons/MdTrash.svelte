
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

<svg width={size} height={size} class='hero {customClass}' fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 7l-.867 12.142A2 2 0 0116.138 21H7.862a2 2 0 01-1.995-1.858L5 7m5 4v6m4-6v6m1-10V4a1 1 0 00-1-1h-4a1 1 0 00-1 1v3M4 7h16"/>
</svg>
