<script>
  export let size = "100%";
  let customClass = "";
  export { customClass as class };

  if (size !== "100%") {
    size =
      size.slice(-1) === "x"
        ? size.slice(0, size.length - 1) + "em"
        : parseInt(size) + "px";
  }
</script>

<svg
  width={size}
  height={size}
  class={customClass}
  fill="none"
  viewBox="0 0 24 24"
  stroke="currentColor">
  <path
    stroke-linecap="round"
    stroke-linejoin="round"
    stroke-width="2"
    d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0
    01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8
    9-8s9 3.582 9 8z" />
</svg>
