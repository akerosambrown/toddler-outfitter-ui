<template>
  <h1>Sunny or Cloudy?</h1>
  <div class="flex justify-center items-center w-full mt-24">
    <!-- Sunny -->
    <svg @click="sunnyActive = !sunnyActive" :class="{active: sunnyActive}" width="373" height="373" viewBox="0 0 373 373" fill="none" xmlns="http://www.w3.org/2000/svg">
      <g class="hover" filter="url(#filter0_d_6_313)">
      <circle cx="186.5" cy="182.5" r="176.5" fill="white"/>
      <circle class="highlight" cx="186.5" cy="182.5" r="169" stroke="black" stroke-width="15"/>
      </g>
      <g filter="url(#filter1_d_6_313)">
      <path d="M257.11 156.93C269.858 195.297 252.592 240.084 216.878 251.951C181.165 263.818 127.594 242.569 114.845 204.202C102.097 165.835 131.805 115.272 167.519 103.405C203.232 91.538 244.361 118.563 257.11 156.93Z" fill="#F3D361"/>
      <path d="M105.385 72.7253C111.926 94.3476 130.433 101.812 138.869 102.842C149.77 106.266 149.77 102.842 138.869 84.3087C127.967 65.7752 97.2093 45.6974 105.385 72.7253Z" fill="#F3D361"/>
      <path d="M149.381 21.8685C148.135 39.4753 161.58 83.7939 168.459 92.4171C178.582 100.526 171.574 50.0548 168.459 32.6797C165.344 15.3047 150.938 -0.139925 149.381 21.8685Z" fill="#F3D361"/>
      <path d="M197.659 48.7863C190.496 58.6708 194.674 81.992 197.659 92.4171C206.614 100.526 207.004 78.1309 212.065 62.3002C217.126 46.4696 206.614 36.4306 197.659 48.7863Z" fill="#F3D361"/>
      <path d="M225.692 96.2782C226.471 84.3087 247.829 11.7558 266.517 14.8447C285.205 17.9336 229.975 119.831 225.692 96.2782Z" fill="#F3D361"/>
      <path d="M285.662 80.4429C264.61 89.1093 258.95 108.272 258.751 116.77C256.393 127.961 259.83 127.619 277.35 114.921C294.87 102.223 311.976 69.6099 285.662 80.4429Z" fill="#F3D361"/>
      <path d="M348.305 109.221C330.513 109.738 280.113 137.472 272.14 145.178C265.004 156.061 322.215 134.119 339.343 129.286C356.471 124.453 370.545 108.576 348.305 109.221Z" fill="#F3D361"/>
      <path d="M318.813 169.886C308.185 163.743 285.195 170.228 275.029 174.239C267.778 183.959 290.29 182.113 306.677 185.571C323.064 189.029 332.098 177.566 318.813 169.886Z" fill="#F3D361"/>
      <path d="M273.927 202.522C286.016 202.103 360.906 213.426 359.655 232.333C358.404 251.24 250.715 209.133 273.927 202.522Z" fill="#F3D361"/>
      <path d="M303.964 251.655C289.733 233.886 269.752 233.836 261.54 236.033C250.138 236.914 251.431 240.116 268.539 253.363C285.647 266.611 321.753 273.867 303.964 251.655Z" fill="#F3D361"/>
      <path d="M283.314 304.321C277.821 287.39 247.672 262.35 238.037 256.863C225.588 253.072 252.09 286.275 261.54 301.356C270.99 316.437 290.181 325.484 283.314 304.321Z" fill="#F3D361"/>
      <path d="M227.435 308.598C230.345 296.672 217.663 276.429 210.958 267.799C199.592 263.57 207.688 284.657 208.973 301.356C210.257 318.055 223.797 323.505 227.435 308.598Z" fill="#F3D361"/>
      <path d="M183.504 274.687C187.302 286.171 195.839 344.645 177.342 348.756C158.845 352.867 170.638 254.267 183.504 274.687Z" fill="#F3D361"/>
      <path d="M140.976 312.003C155.664 294.609 151.855 274.995 148.114 267.362C145.049 256.344 142.157 258.231 132.461 277.575C122.765 296.919 122.617 333.746 140.976 312.003Z" fill="#F3D361"/>
      <path d="M75.1664 299.512C90.7179 290.853 119.615 258.835 123.139 248.322C124.455 235.375 86.8445 265.391 73.8717 277.575C60.899 289.758 55.727 310.335 75.1664 299.512Z" fill="#F3D361"/>
      <path d="M70.3304 247.907C82.5939 248.46 100.007 232.109 107.181 223.864C109.136 211.895 90.0083 223.91 73.8718 228.394C57.7352 232.878 55.0012 247.215 70.3304 247.907Z" fill="#F3D361"/>
      <path d="M95.1225 198.256C84.5875 204.2 30.871 215.612 23.2668 198.256C15.6627 180.901 112.675 181.69 95.1225 198.256Z" fill="#F3D361"/>
      <path d="M48.0325 162.29C64.3933 169.301 89.4307 163.774 99.9043 160.134C110.954 153.258 82.1717 150.667 64.5987 147.852C47.0258 145.037 27.5815 153.527 48.0325 162.29Z" fill="#F3D361"/>
      <path d="M39.6156 93.6161C46.6764 103.658 98.5889 131.916 109.499 132.551C120.165 126.779 70.6363 94.5127 57.221 84.4864C43.8057 74.4602 30.7895 81.0636 39.6156 93.6161Z" fill="#F3D361"/>
      </g>
      <defs>
      <filter id="filter0_d_6_313" x="0" y="0" width="373" height="373" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="4"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_6_313"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_6_313" result="shape"/>
      </filter>
      <filter id="filter1_d_6_313" x="12.8411" y="5" width="356.921" height="357.881" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="4"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_6_313"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_6_313" result="shape"/>
      </filter>
      </defs>
    </svg>

    <!-- -->
    <!-- Cloudy -->
    <svg @click="cloudyActive = !cloudyActive" :class="{active: cloudyActive}" width="399" height="373" viewBox="0 0 399 373" fill="none" xmlns="http://www.w3.org/2000/svg">
      <g class="hover" filter="url(#filter0_d_6_314)">
      <circle cx="199.5" cy="182.5" r="176.5" fill="white"/>
      <circle class="highlight" cx="199.5" cy="182.5" r="169" stroke="black" stroke-width="15"/>
      </g>
      <g filter="url(#filter1_d_6_314)">
      <path d="M377.256 246.625C353.696 264.151 76.6919 275.451 34.3382 253.78C-8.01557 232.108 34.1655 185.544 59.1575 184.256C49.7363 152.403 50.6278 85.7096 129.563 73.7579C208.498 61.8062 234.966 111.736 238.332 138.194C282.97 119.229 308.474 157.433 315.645 178.905C371.086 174.068 400.815 229.099 377.256 246.625Z" fill="#C8CFE6"/>
      </g>
      <defs>
      <filter id="filter0_d_6_314" x="13" y="0" width="373" height="373" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="4"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_6_314"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_6_314" result="shape"/>
      </filter>
      <filter id="filter1_d_6_314" x="6.28906" y="65.9409" width="389.105" height="213.736" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
      <feFlood flood-opacity="0" result="BackgroundImageFix"/>
      <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
      <feOffset dy="4"/>
      <feGaussianBlur stdDeviation="5"/>
      <feComposite in2="hardAlpha" operator="out"/>
      <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"/>
      <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_6_314"/>
      <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_6_314" result="shape"/>
      </filter>
      </defs>
    </svg>

    <!-- -->
  </div>
  <NuxtLink to="/mood" class="btn flex justify-center items-center absolute bottom-10 right-10">
    Next >
  </NuxtLink>
</template>

<script setup>
const sunnyActive = ref(false)
const cloudyActive = ref(false)
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