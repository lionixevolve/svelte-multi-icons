
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
  <path fill="#4A5568" d="M21 10v1a1 1 0 001-1h-1zm0 4h1a1 1 0 00-1-1v1zM3 14v-1a1 1 0 00-1 1h1zm0-4H2a1 1 0 001 1v-1zm2-6a3 3 0 00-3 3h2a1 1 0 011-1V4zm14 0H5v2h14V4zm3 3a3 3 0 00-3-3v2a1 1 0 011 1h2zm0 3V7h-2v3h2zm-2 2a1 1 0 011-1V9a3 3 0 00-3 3h2zm1 1a1 1 0 01-1-1h-2a3 3 0 003 3v-2zm1 4v-3h-2v3h2zm-3 3a3 3 0 003-3h-2a1 1 0 01-1 1v2zM5 20h14v-2H5v2zm-3-3a3 3 0 003 3v-2a1 1 0 01-1-1H2zm0-3v3h2v-3H2zm2-2a1 1 0 01-1 1v2a3 3 0 003-3H4zm-1-1a1 1 0 011 1h2a3 3 0 00-3-3v2zM2 7v3h2V7H2z"/>
  <path stroke-linecap="round" stroke-width="2" d="M15 5v2"/>
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11v2M15 17v2"/>
</svg>
