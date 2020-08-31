<template>
  <svg
    version="1.1"
    id="loader-1"
    xmlns="http://www.w3.org/2000/svg"
    xmlns:xlink="http://www.w3.org/1999/xlink"
    x="0px"
    y="0px"
    :width="size"
    :height="size"
    viewBox="0 0 386 386"
    enable-background="new 0 0 386 386"
    xml:space="preserve"
  >
    <path
      d="M0,206.3v174.1c0,3.1,2.5,5.5,5.5,5.5h174.1c4.9,0,7.4-6,3.9-9.4L9.4,202.4C6,199,0,201.4,0,206.3z"
    />
    <path
      d="M179.7,0H5.5C2.5,0,0,2.5,0,5.5v174.1c0,4.9,6,7.4,9.4,3.9L183.6,9.4C187,6,184.6,0,179.7,0z"
    />
    <path
      d="M202.4,376.6l179.7-179.7c2.1-2.1,2.1-5.6,0-7.8L202.4,9.4c-3.5-3.5-9.4-1-9.4,3.9v359.4 C193,377.6,198.9,380.1,202.4,376.6z"
    />
    <circle cx="113" cy="193" r="72.2">
      <animateTransform
        attributeType="xml"
        attributeName="transform"
        type="scale"
        from="1 1 1"
        to="2 2 1"
        :dur="duration"
        repeatCount="indefinite"
      />
    </circle>
  </svg>
</template>

<script>
export default {
  name: "kod",
  props: {
    size: {
      type: String,
      default: "40px"
    },
    duration: {
      type: String,
      default: "0.6s"
    }
  }
};
</script>