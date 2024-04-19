<template>
  <h1>What do you want?</h1>
  <div class="flex justify-center items-center w-full mt-24">
    <!-- Lion -->
    <svg @click="lionActive = !lionActive" :class="{active: lionActive}" width="381" height="374" viewBox="0 0 381 374" fill="none" xmlns="http://www.w3.org/2000/svg">
      <g class="hover" filter="url(#filter0_d_7_451)">
      <circle cx="186.5" cy="183" r="176.5" fill="white"/>
      <circle class="highlight" cx="186.5" cy="183" r="169" stroke="black" stroke-width="15"/>
      </g>
      <g filter="url(#filter1_d_7_451)">
      <path d="M72.4662 111.803C7.59966 100.387 45.9654 128.998 39.1577 142.602C35.8 160.403 34.3205 176.282 34.4719 190.447C34.6558 207.65 37.2452 222.325 41.7974 234.843C48.3715 252.921 59.0391 266.501 72.4662 276.702C85.0675 286.275 100.099 292.873 116.46 297.42C133.785 302.235 152.601 304.75 171.596 306.064C192.367 307.5 213.353 307.5 232.842 307.5C261.15 307.5 283.776 297.984 301.663 283.861C310.478 276.901 318.142 268.822 324.768 260.212L324.799 260.172C331.078 252.013 343.356 236.059 347.856 227.472C353.105 217.456 347.856 205.909 340.885 198.059C345.763 183.806 370.224 205.418 370.937 198.059C372.152 185.52 355.568 137.09 339.058 115.608C328.572 101.966 314.309 88.5918 296.008 78.1177C276.08 66.7128 251.367 58.7462 221.532 57.6152C178.013 55.9653 115.52 72.4216 88.1842 82.6299C66.2693 90.8138 61.3227 78.1177 72.4662 111.803Z" fill="#AC4F3D"/>
      </g>
      <g filter="url(#filter2_d_7_451)">
      <path d="M101.894 136.276C80.353 154.802 92.9184 173.964 101.894 181.23C101.894 198.485 103.311 236.809 108.979 252.066C116.065 271.138 124.568 272.5 144.408 272.5C164.248 272.5 252.112 267.051 262.032 264.327C269.968 262.147 280.455 201.663 284.707 171.694C296.044 168.061 314.75 155.892 298.878 136.276C283.006 116.659 261.087 134.459 252.112 145.811H144.408C139.212 134.913 123.435 117.749 101.894 136.276Z" fill="#E2A755"/>
      </g>
      <path d="M176.711 216.5C159.108 216.5 163.909 227.5 167.109 232.214C176.697 240.06 184.511 243.205 191.143 243.562C192.018 243.609 193.165 258.546 194 258.5C195.593 258.413 196.823 243.227 198.286 242.85C207.705 240.417 214.611 232.586 221.517 227.5C234.319 218.071 194.313 216.5 176.711 216.5Z" fill="black"/>
      <path d="M148.826 178.885C147.445 187.769 147.445 193.691 151.59 190.73C155.735 187.769 154.354 172.963 148.826 178.885Z" fill="black"/>
      <path d="M230.04 189.087C229.21 180.794 227.747 175.501 224.382 179.211C221.017 182.921 226.041 195.799 230.04 189.087Z" fill="black"/>
      <defs>
      <filter id="filter0_d_7_451" x="0" y="0.5" width="373" height="373" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="4"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_7_451"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_7_451" result="shape"/>
      </filter>
      <filter id="filter1_d_7_451" x="24" y="51.5" width="357" height="270" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="4"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_7_451"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_7_451" result="shape"/>
      </filter>
      <filter id="filter2_d_7_451" x="80" y="121.5" width="235" height="165" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="4"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_7_451"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_7_451" result="shape"/>
      </filter>
      </defs>
    </svg>

    <!-- -->
    <!-- Elephant-->
    <svg @click="elephantActive = !elephantActive" :class="{active: elephantActive}" width="373" height="398" viewBox="0 0 373 398" fill="none" xmlns="http://www.w3.org/2000/svg">
      <g class="hover" filter="url(#filter0_d_7_452)">
      <circle cx="186.5" cy="183" r="176.5" fill="white"/>
      <circle class="highlight" cx="186.5" cy="183" r="169" stroke="black" stroke-width="15"/>
      </g>
      <g filter="url(#filter1_d_7_452)">
      <path d="M224.166 103.974C187.603 88.5211 148.916 102.134 134.143 110.872C110.049 69.0678 55.5482 69.0173 40.8003 110.872C-7.66943 248.431 46.3452 254.362 103.673 298.512C122.081 312.689 144.761 269.078 150.762 254.362L199.236 281.956L242.171 254.362C240.786 277.357 266.565 340.295 301.724 298.512C385.663 198.762 359.893 141.226 316.959 98.4553C282.612 64.2387 240.786 87.8774 224.166 103.974Z" fill="#D9D9D9"/>
      </g>
      <g filter="url(#filter2_d_7_452)">
      <path d="M69.4339 91.6726C96.8982 76.4342 112 106.912 120.24 119.38C129.996 131.848 128.479 252.372 120.24 274.537C112 296.703 71.6268 281.863 40.5954 230.206C13.1325 184.49 51.5465 101.597 69.4339 91.6726Z" fill="#EFE9EF"/>
      </g>
      <g filter="url(#filter3_d_7_452)">
      <path d="M287.802 91.6558C273.4 87.2301 247.641 95.8046 247.641 112.401C233.793 293.58 278.108 296.346 294.726 288.048C311.345 279.749 344.581 203.682 345.966 174.638C347.351 145.594 305.805 97.188 287.802 91.6558Z" fill="#EFE9EF"/>
      </g>
      <g filter="url(#filter4_d_7_452)">
      <path d="M145.912 253.342C80.2097 223.448 110.184 146.776 133.384 112.176C143.129 95.5685 175.423 70.6568 226.649 103.872C277.875 137.088 272.121 202.596 262.841 231.199C251.241 251.036 211.615 283.236 145.912 253.342Z" fill="#D9D9D9"/>
      </g>
      <path d="M157.162 175.243C155.465 182.283 155.281 190.826 150.72 191.373C146.159 191.92 141.649 185.585 140.646 177.223C139.643 168.862 142.527 161.64 147.088 161.093C151.649 160.546 157.162 165.648 157.162 175.243Z" fill="#352C35"/>
      <path d="M234.207 176.573C233.566 184.97 229.333 191.494 224.753 191.144C220.172 190.795 218.209 179.51 217.62 175.307C216.46 167.034 222.493 160.386 227.074 160.735C231.654 161.085 234.847 168.176 234.207 176.573Z" fill="#352C35"/>
      <path fill-rule="evenodd" clip-rule="evenodd" d="M189.415 228.376C190.697 230.35 190.137 232.99 188.162 234.272C171.53 245.077 158.568 245.24 149.261 239.099C140.475 233.303 136.4 222.756 135.145 215.215C134.759 212.893 136.328 210.697 138.65 210.311C140.972 209.924 143.168 211.493 143.555 213.816C144.621 220.227 147.982 228.042 153.956 231.984C159.408 235.581 168.531 236.859 183.518 227.123C185.492 225.841 188.132 226.402 189.415 228.376Z" fill="#352C35"/>
      <g filter="url(#filter5_d_7_452)">
      <path d="M175.939 373.341C146.812 356.592 149.334 267.265 153.535 228.184C191.345 214.227 237.555 189.103 237.555 246.329C237.555 257.748 231.072 268.772 226.364 277.036C201.703 320.322 200.814 347.27 213.749 349.614C226.072 351.847 226.352 338.448 224.952 331.469C228.686 327.747 237.555 323.932 243.156 338.448C250.158 356.592 212.348 394.277 175.939 373.341Z" fill="#D9D9D9"/>
      </g>
      <g filter="url(#filter6_d_7_452)">
      <path d="M235 335.5L226 331.631C229.086 328.536 233.286 329.481 235 330.341V335.5Z" fill="#352C35"/>
      </g>
      <defs>
      <filter id="filter0_d_7_452" x="0" y="0.5" width="373" height="373" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="4"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_7_452"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_7_452" result="shape"/>
      </filter>
      <filter id="filter1_d_7_452" x="12" y="73.5" width="355" height="253" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="4"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_7_452"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_7_452" result="shape"/>
      </filter>
      <filter id="filter2_d_7_452" x="21" y="81.5" width="116" height="217" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="4"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_7_452"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_7_452" result="shape"/>
      </filter>
      <filter id="filter3_d_7_452" x="235" y="84.5" width="121" height="220" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="4"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_7_452"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_7_452" result="shape"/>
      </filter>
      <filter id="filter4_d_7_452" x="96" y="81.5" width="183" height="198" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="4"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_7_452"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_7_452" result="shape"/>
      </filter>
      <filter id="filter5_d_7_452" x="141" y="208.5" width="113" height="189" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="8"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_7_452"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_7_452" result="shape"/>
      </filter>
      <filter id="filter6_d_7_452" x="216" y="323.5" width="29" height="26" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="4"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_7_452"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_7_452" result="shape"/>
      </filter>
      </defs>
    </svg>

    <!-- -->
  </div>
  <NuxtLink to="/suggestion" class="btn flex justify-center items-center absolute bottom-10 right-10">
    Next >
  </NuxtLink>
</template>

<script setup>
import { computed } from 'vue'
const lionActive = ref(false)
const elephantActive = ref(false)


</script>

<style lang="scss" scoped>
h1 {
  font-size: 100px;
  margin-top: 2rem;
}
svg {
  &.active {
    .highlight {
      stroke: rgba(67, 240, 52, 1);
    }
  }
  &:hover {
    g.hover {
      filter: none;
    }
  }
}
</style>