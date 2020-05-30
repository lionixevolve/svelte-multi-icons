<script>
  export let size = "100%";
  let customClass = "";
  export { customClass as class };
  export let style = "";
  if (size !== "100%") {
    size =
      size.slice(-1) === "x"
        ? size.slice(0, size.length - 1) + "em"
        : parseInt(size) + "px";
  }
</script>

<svg
  style={style}
  width={size}
  height={size}
  class={customClass}
  viewBox="0 0 24 24"
  stroke="currentColor"
  fill="none"
  stroke-width="2"
  stroke-linecap="round"
  stroke-linejoin="round"
  xmlns="http://www.w3.org/2000/svg">
  <line x1="22" y1="2" x2="11" y2="13" />
  <polygon points="22 2 15 22 11 13 2 9 22 2" />
</svg>
