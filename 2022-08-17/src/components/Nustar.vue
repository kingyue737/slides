<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    xmlns:xlink="http://www.w3.org/1999/xlink"
    viewBox="0 0 56 56"
  >
    <defs>
      <path id="inner-pie" d="M10,26.4A19.5,19.5,0,0,0,26.4,10H10V26.4Z" />
      <path
        id="outer-ring"
        d="M2,26.7A26.7,26.7,0,0,1,26.7,2v-2A28,28,0,0,0,0,26.7h2Z"
      />
    </defs>
    <g class="logo-inner">
      <use xlink:href="#inner-pie" />
      <use xlink:href="#inner-pie" transform="rotate(90, 28, 28)" />
      <use xlink:href="#inner-pie" transform="rotate(180, 28, 28)" />
      <use xlink:href="#inner-pie" transform="rotate(270, 28, 28)" />
    </g>
    <g class="logo-outer">
      <use xlink:href="#outer-ring" />
      <use xlink:href="#outer-ring" transform="rotate(90, 28, 28)" />
      <use xlink:href="#outer-ring" transform="rotate(180, 28, 28)" />
      <use xlink:href="#outer-ring" transform="rotate(270, 28, 28)" />
    </g>
  </svg>
</template>
