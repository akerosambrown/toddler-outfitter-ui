<template>
  <h1>Today, you should wear...</h1>
  <div class="flex justify-center items-center w-full">
    <!-- Bam star-->
    <svg width="1120" height="630" viewBox="0 0 1120 630" fill="none" xmlns="http://www.w3.org/2000/svg">
      <g filter="url(#filter0_d_8_721)">
      <path d="M413.772 29.7232L563.443 107.764L700.429 17.3076L766.386 125.5L949.562 107.764L916.057 212.409L1082.87 249.656L933.814 325.922L1082.87 403.963L865.321 421.699L949.562 540.534L738.481 485.551L700.429 603.073L563.443 501.514L431.348 603.073L398.551 476.682L200.68 540.534V421.699L33.2995 403.963L155.018 313.507L33.2993 249.656L231.122 212.409L200.68 107.764L383.33 139.689L413.772 29.7232Z" fill="#FFE500"/>
      <path d="M413.772 29.7232L563.443 107.764L700.429 17.3076L766.386 125.5L949.562 107.764L916.057 212.409L1082.87 249.656L933.814 325.922L1082.87 403.963L865.321 421.699L949.562 540.534L738.481 485.551L700.429 603.073L563.443 501.514L431.348 603.073L398.551 476.682L200.68 540.534V421.699L33.2995 403.963L155.018 313.507L33.2993 249.656L231.122 212.409L200.68 107.764L383.33 139.689L413.772 29.7232Z" stroke="black" stroke-width="15" stroke-linecap="square"/>
      </g>
      <defs>
      <filter id="filter0_d_8_721" x="0.712891" y="0.76416" width="1118.58" height="629.162" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="4"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_8_721"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_8_721" result="shape"/>
      </filter>
      </defs>
    </svg>

    <div class="suggestion">
      <img src="~/assets/src/elephant-top.png" alt="Elephants on a Top" />
    </div>
  </div>
  <NuxtLink to="/" class="btn flex justify-center items-center absolute bottom-10 right-10">
    Start Again
  </NuxtLink>
</template>

<style lang="scss" scoped>
h1 {
  font-size: 100px;
  margin-top: 2rem;
}
svg {
  .highlight {
    &.active {
      stroke: rgba(67, 240, 52, 1);
    }
  }
  &:hover {
    g.hover {
      filter: none;
    }
  }
}
.btn {
  font-size: 36px;
  width: fit-content;
  padding-left: 1rem;
  padding-right: 1rem;
  height: fit-content;
  padding-top: 2rem;
  padding-bottom: 1.25rem;
}
.suggestion {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  border: 15px solid;
  border-radius: 20px;
  width: 500px;
  height: 500px;
  img {
    max-height: 100%;
    width: 100%;
    border-radius: 5px;
  }
}
</style>