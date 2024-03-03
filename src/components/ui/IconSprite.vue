<template>
<svg v-if="name === 'arrow'" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <rect width="20" height="20" rx="6" fill="#F5F7FB"/>
  <path d="M6.66663 8.33333L9.99996 11.6667L13.3333 8.33333" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'attachment'" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M2.5 2.49999L8.33333 2.49999" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M2.5 4.99999L8.33333 4.99999" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M2.5 7.49999H5" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M13.2242 7.60916C14.2025 6.63083 15.7875 6.63083 16.7658 7.60916V7.60916C17.7442 8.5875 17.7442 10.1725 16.7658 11.1508L12.6017 15.315C11.6233 16.2933 10.0383 16.2933 9.06 15.315V15.315C8.08166 14.3367 8.08166 12.7517 9.06 11.7733L9.6825 11.1508" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M7.60917 16.7667C6.63083 17.745 5.04583 17.745 4.0675 16.7667V16.7667C3.08917 15.7883 3.08917 14.2033 4.0675 13.225L8.23167 9.06084C9.21 8.0825 10.795 8.0825 11.7733 9.06084V9.06084C12.7517 10.0392 12.7517 11.6242 11.7733 12.6025L11.125 13.25" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'bell'" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M9.70801 18.344V18.709C9.70801 19.974 10.734 21 12 21V21C13.266 21 14.292 19.974 14.292 18.708V18.343" stroke="#2A355A" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M13.833 5.751V4.833C13.833 3.821 13.013 3 12 3V3C10.987 3 10.167 3.821 10.167 4.833V5.751" stroke="#2A355A" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M6.563 10.188V10.188C6.563 7.685 8.592 5.657 11.094 5.657H12.907C15.41 5.657 17.438 7.686 17.438 10.188V10.188V12.985C17.438 13.515 17.649 14.024 18.024 14.399L18.665 15.04C19.04 15.415 19.251 15.924 19.251 16.454V16.454C19.251 17.498 18.405 18.344 17.361 18.344H6.64C5.596 18.344 4.75 17.498 4.75 16.454V16.454C4.75 15.924 4.961 15.415 5.336 15.04L5.977 14.399C6.352 14.024 6.563 13.515 6.563 12.985V10.188Z" stroke="#2A355A" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'burger'" width="16" height="12" viewBox="0 0 16 12" fill="none" xmlns="http://www.w3.org/2000/svg">
  <rect x="0.000999451" y="0.5" width="16" height="1" rx="0.5" fill="#2A355A"/>
  <rect x="0.000999451" y="5.5" width="16" height="1" rx="0.5" fill="#2A355A"/>
  <rect x="0.000999451" y="10.5" width="16" height="1" rx="0.5" fill="#2A355A"/>
</svg>
<svg v-else-if="name === 'business'" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M3.33333 14.1225V15.8333C3.33333 16.7542 4.07917 17.5 5 17.5H15C15.9208 17.5 16.6667 16.7542 16.6667 15.8333V8.95334" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M3.33333 11.2058L3.33333 4.16667C3.33333 3.24583 4.07917 2.5 5 2.5L15 2.5C15.9208 2.5 16.6667 3.24583 16.6667 4.16667V6.03667" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M4.35953 11.633C4.92905 12.2025 4.92905 13.1259 4.35953 13.6954C3.79002 14.2649 2.86665 14.2649 2.29714 13.6954C1.72763 13.1259 1.72763 12.2025 2.29714 11.633C2.86666 11.0635 3.79002 11.0635 4.35953 11.633" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M10.7908 12.4975C10.7908 11.6925 11.4433 11.0392 12.2492 11.0392C13.055 11.0392 13.7075 11.6917 13.7075 12.4975C13.7075 13.3033 13.055 13.9558 12.2492 13.9558C11.4467 13.9592 10.7942 13.3117 10.7908 12.5092C10.7908 12.505 10.7908 12.5017 10.7908 12.4975Z" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M8.8545 6.46379C9.42401 7.0333 9.42401 7.95667 8.8545 8.52618C8.28498 9.09569 7.36162 9.09569 6.79211 8.52618C6.22259 7.95666 6.22259 7.0333 6.79211 6.46379C7.36162 5.89427 8.28499 5.89427 8.8545 6.46379" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M17.7028 6.46379C18.2723 7.0333 18.2723 7.95667 17.7028 8.52618C17.1333 9.09569 16.2099 9.09569 15.6404 8.52618C15.0709 7.95666 15.0709 7.0333 15.6404 6.46379C16.21 5.89427 17.1333 5.89427 17.7028 6.46379" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M15.6583 8.54166L13.2417 11.4333" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M4.31667 11.5917L6.83333 8.55832" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M11.2583 11.4333L8.81667 8.55832" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'charts'" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path fill-rule="evenodd" clip-rule="evenodd" d="M11.7358 17.2917L11.7358 7.29166L14.7917 7.29166C15.2517 7.29166 15.625 7.66499 15.625 8.12499L15.625 17.2917L11.7358 17.2917Z" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M7.8475 17.2917L7.8475 3.12499C7.8475 2.66499 8.22083 2.29166 8.68083 2.29166L10.9033 2.29166C11.3633 2.29166 11.7367 2.66499 11.7367 3.12499L11.7367 17.2917L7.8475 17.2917Z" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M3.95833 17.2917L3.95833 5.62499C3.95833 5.16499 4.33167 4.79166 4.79167 4.79166L7.8475 4.79166L7.8475 17.2917L3.95833 17.2917Z" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M2.29167 17.2917L17.2917 17.2917" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'documents'" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M6.66667 10.8333L13.3333 10.8333" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M6.66667 14.1667L13.3333 14.1667" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M5 2.5L12.6433 2.5C13.085 2.5 13.5092 2.67583 13.8217 2.98833L16.1783 5.345C16.4908 5.6575 16.6667 6.08167 16.6667 6.52333V15.8333C16.6667 16.7542 15.9208 17.5 15 17.5H5C4.07917 17.5 3.33333 16.7542 3.33333 15.8333L3.33333 4.16667C3.33333 3.24583 4.07917 2.5 5 2.5Z" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M16.6667 6.66667L13.3333 6.66667C12.8733 6.66667 12.5 6.29333 12.5 5.83333V2.5" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M6.66667 7.50001H9.16667" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'logo'" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <g clip-path="url(#clip0_1_6161)">
    <path fill-rule="evenodd" clip-rule="evenodd" d="M2.18418 0C0.976328 0 0 0.976347 0 2.18418V20H17.8158C19.0236 20 20 19.0237 20 17.8158V0H2.18418ZM2.76798 3.70409C2.76798 3.18067 3.19072 2.768 3.70407 2.768H7.7101C8.2335 2.768 8.49521 3.40213 8.12279 3.77455L3.77453 8.12281C3.4021 8.49524 2.76798 8.23352 2.76798 7.71012V3.70409ZM17.232 16.296C17.232 16.8194 16.8092 17.232 16.2959 17.232H12.2899C11.7665 17.232 11.5048 16.5979 11.8772 16.2255L16.2254 11.8772C16.5979 11.5048 17.232 11.7665 17.232 12.2899V16.296ZM17.232 8.03224C17.232 10.0554 15.5913 11.686 13.5782 11.686H7.63963L7.62957 15.0478C7.62957 16.2456 6.65322 17.222 5.45545 17.222L2.76798 17.222V11.9477C2.76798 9.92455 4.40866 8.29396 6.42172 8.29396H12.3603L12.3704 4.93212C12.3704 3.73433 13.3467 2.75798 14.5445 2.75798L17.232 2.75796V8.03224Z" fill="#8F20EF"/>
  </g>
  <defs>
    <clipPath id="clip0_1_6161">
      <rect width="20" height="20" fill="white"/>
    </clipPath>
  </defs>
</svg>
<svg v-else-if="name === 'money'" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M11.6667 5.83334L8.9225 3.08918C8.59667 2.76334 8.06917 2.76334 7.74417 3.08918L5 5.83334" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M10 4.16668L11.0775 3.08918C11.4033 2.76334 11.9308 2.76334 12.2558 3.08918L15 5.83334" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M17.5 10H14.5158C13.8625 10 13.3333 10.5292 13.3333 11.1825V12.1508C13.3333 12.8042 13.8625 13.3333 14.5158 13.3333H17.5" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M15.8333 17.5H4.16667C3.24583 17.5 2.5 16.7542 2.5 15.8333L2.5 7.49999C2.5 6.57916 3.24583 5.83333 4.16667 5.83333L15.8333 5.83333C16.7542 5.83333 17.5 6.57916 17.5 7.49999V15.8333C17.5 16.7542 16.7542 17.5 15.8333 17.5Z" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'plus'" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <rect width="20" height="20" rx="6" fill="#F5F7FB"/>
  <path d="M10 6V14" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M14 10H6" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'search'" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M15.7138 6.8382C18.1647 9.28913 18.1647 13.2629 15.7138 15.7138C13.2629 18.1647 9.28913 18.1647 6.8382 15.7138C4.38727 13.2629 4.38727 9.28913 6.8382 6.8382C9.28913 4.38727 13.2629 4.38727 15.7138 6.8382" stroke="#2A355A" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M19 19L15.71 15.71" stroke="#2A355A" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'settings'" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M11.591 8.40901C12.4697 9.2877 12.4697 10.7123 11.591 11.591C10.7123 12.4697 9.2877 12.4697 8.40902 11.591C7.53033 10.7123 7.53033 9.2877 8.40902 8.40901C9.2877 7.53033 10.7123 7.53033 11.591 8.40901" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M4.375 10C4.375 10.2475 4.3975 10.495 4.4275 10.735L3.10417 11.77C2.81083 12 2.73083 12.4108 2.9175 12.7333L4.09417 14.7692C4.28 15.0917 4.675 15.2275 5.02083 15.0892L6.20583 14.6133C6.44 14.5192 6.70083 14.5567 6.91083 14.6958C7.09417 14.8175 7.28417 14.9292 7.48083 15.0292C7.70583 15.1433 7.86917 15.3475 7.905 15.5975L8.08583 16.8583C8.13833 17.2267 8.45417 17.5 8.82583 17.5H11.1733C11.545 17.5 11.8608 17.2267 11.9133 16.8583L12.0942 15.5983C12.13 15.3483 12.295 15.1425 12.5208 15.0292C12.7167 14.9308 12.9058 14.82 13.0883 14.6992C13.3 14.5592 13.5617 14.5192 13.7967 14.6142L14.9792 15.0892C15.3242 15.2275 15.7192 15.0917 15.9058 14.7692L17.0825 12.7333C17.2692 12.4108 17.1892 11.9992 16.8958 11.77L15.5725 10.735C15.6025 10.495 15.625 10.2475 15.625 10C15.625 9.7525 15.6025 9.505 15.5725 9.265L16.8958 8.23C17.1892 8 17.2692 7.58917 17.0825 7.26667L15.9058 5.23083C15.72 4.90833 15.325 4.7725 14.9792 4.91083L13.7967 5.38583C13.5617 5.48 13.3 5.44083 13.0883 5.30083C12.9058 5.18 12.7167 5.06917 12.5208 4.97083C12.295 4.8575 12.13 4.65167 12.0942 4.40167L11.9142 3.14167C11.8617 2.77333 11.5458 2.5 11.1742 2.5L8.82667 2.5C8.455 2.5 8.13917 2.77333 8.08667 3.14167L7.905 4.40333C7.86917 4.6525 7.705 4.8575 7.48083 4.97167C7.28417 5.07167 7.09417 5.18417 6.91083 5.305C6.7 5.44333 6.43917 5.48083 6.205 5.38667L5.02083 4.91083C4.675 4.7725 4.28 4.90833 4.09417 5.23083L2.9175 7.26667C2.73083 7.58917 2.81083 8.00083 3.10417 8.23L4.4275 9.265C4.3975 9.505 4.375 9.7525 4.375 10V10Z" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'tickets'" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M11.3794 8.62058C12.1413 9.38243 12.1413 10.6176 11.3794 11.3795C10.6176 12.1413 9.38237 12.1413 8.62053 11.3795C7.85868 10.6176 7.85868 9.38242 8.62053 8.62058C9.38237 7.85873 10.6176 7.85873 11.3794 8.62058" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M17.8741 8.75841C18.5598 9.44411 18.5598 10.5558 17.8741 11.2415C17.1884 11.9272 16.0767 11.9272 15.391 11.2415C14.7053 10.5558 14.7053 9.44411 15.391 8.75841C16.0767 8.07272 17.1884 8.07272 17.8741 8.75841" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M4.60906 8.75841C5.29475 9.44411 5.29475 10.5558 4.60906 11.2415C3.92336 11.9272 2.81163 11.9272 2.12593 11.2415C1.44024 10.5558 1.44024 9.44411 2.12593 8.75841C2.81163 8.07272 3.92336 8.07272 4.60906 8.75841" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M14.5574 3.01427C15.2431 3.69997 15.2431 4.8117 14.5574 5.4974C13.8717 6.18309 12.76 6.18309 12.0743 5.4974C11.3886 4.8117 11.3886 3.69997 12.0743 3.01427C12.76 2.32858 13.8717 2.32858 14.5574 3.01427" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M7.92573 14.5026C8.61142 15.1883 8.61142 16.3 7.92573 16.9857C7.24003 17.6714 6.1283 17.6714 5.4426 16.9857C4.75691 16.3 4.75691 15.1883 5.4426 14.5026C6.1283 13.8169 7.24003 13.8169 7.92573 14.5026" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M7.92573 3.01427C8.61142 3.69997 8.61142 4.8117 7.92573 5.4974C7.24003 6.18309 6.1283 6.18309 5.4426 5.4974C4.75691 4.8117 4.75691 3.69997 5.4426 3.01427C6.1283 2.32858 7.24003 2.32858 7.92573 3.01427" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M14.5574 14.5026C15.2431 15.1883 15.2431 16.3 14.5574 16.9857C13.8717 17.6714 12.76 17.6714 12.0743 16.9857C11.3886 16.3 11.3886 15.1883 12.0743 14.5026C12.76 13.8169 13.8717 13.8169 14.5574 14.5026" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M7.55833 14.225L9.025 11.6833" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M7.55833 5.77499L9.025 8.31666" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M14.875 10H11.95" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'tools'" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M9.8625 12.5L14.0292 16.6667C14.7192 17.3567 15.8392 17.3567 16.5292 16.6667V16.6667C17.2192 15.9767 17.2192 14.8567 16.5292 14.1667L12.3625 10" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M5.70004 5.83334L8.61671 8.75001" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M2.44417 3.5775L3.00583 5.26333C3.11917 5.60417 3.4375 5.83333 3.79667 5.83333H5.69583V3.93417C5.69583 3.57583 5.46667 3.25667 5.12583 3.14333L3.44 2.58167C3.29 2.53167 3.125 2.57083 3.01333 2.6825L2.545 3.15083C2.43333 3.2625 2.39417 3.4275 2.44417 3.5775V3.5775Z" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M17.43 4.8725C17.45 4.89167 17.465 4.91667 17.4725 4.94333C17.8642 6.24917 17.5608 7.71833 16.5292 8.75C15.4867 9.7925 13.9975 10.0908 12.6817 9.68083L5.72583 16.6367C5.04833 17.3142 3.94333 17.365 3.2425 16.7117C2.50583 16.0258 2.49083 14.8725 3.19583 14.1667L10.1817 7.18083C9.77167 5.865 10.07 4.37583 11.1125 3.33333C12.1442 2.30167 13.6133 1.99833 14.9192 2.39C14.9458 2.39833 14.9708 2.4125 14.99 2.4325L15.125 2.5675C15.19 2.6325 15.19 2.73833 15.125 2.80333L12.9292 5L14.8625 6.93333L17.0592 4.73667C17.1242 4.67167 17.23 4.67167 17.295 4.73667L17.43 4.8725V4.8725Z" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'user'" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path fill-rule="evenodd" clip-rule="evenodd" d="M11.4732 9.15182C12.2868 9.96541 12.2868 11.2845 11.4732 12.0981C10.6596 12.9117 9.34048 12.9117 8.52689 12.0981C7.7133 11.2845 7.7133 9.96541 8.52689 9.15182C9.34048 8.33823 10.6596 8.33823 11.4732 9.15182" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M16.0448 4.15185C16.8584 4.96544 16.8584 6.28453 16.0448 7.09813C15.2312 7.91172 13.9122 7.91172 13.0986 7.09813C12.285 6.28453 12.285 4.96544 13.0986 4.15185C13.9122 3.33826 15.2312 3.33826 16.0448 4.15185" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M15 10.2083C16.2775 10.2083 17.5 10.6525 18.3333 11.3191" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M6.90147 4.15185C7.71507 4.96544 7.71507 6.28453 6.90147 7.09813C6.08788 7.91172 4.76879 7.91172 3.9552 7.09813C3.14161 6.28453 3.14161 4.96544 3.9552 4.15185C4.76879 3.33826 6.08788 3.33826 6.90147 4.15185" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M1.66667 11.3191C2.5 10.6525 3.7225 10.2083 5 10.2083" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M13.8258 16.4583C12.855 15.7075 11.46 15.2083 10 15.2083C8.54 15.2083 7.145 15.7075 6.17417 16.4583" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'info'" width="14" height="15" viewBox="0 0 14 15" fill="none" xmlns="http://www.w3.org/2000/svg">
 <rect y="0.5" width="14" height="14" rx="7" fill="#F5F7FB"/>
 <path d="M7.00053 7.00003V11" stroke="#8591AE" stroke-linecap="round" stroke-linejoin="round"/>
 <circle cx="7.00101" cy="4.25003" r="0.75" fill="#8591AE"/>
</svg>
<svg v-else-if="name === 'add-button'" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M10 6V14" stroke="white" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M14 10H6" stroke="white" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'search-arrow'" width="9" height="5" viewBox="0 0 9 5" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M3.80404 0.187909C4.06925 -0.0625281 4.50216 -0.0625281 4.76737 0.187909L7.83832 3.08781C8.26185 3.48775 7.95873 4.16675 7.35666 4.16675L1.21475 4.16675C0.612678 4.16675 0.309557 3.48775 0.733089 3.08781L3.80404 0.187909Z" fill="#C2C9DA"/>
</svg>
<svg v-else-if="name === 'table-arrow'" width="21" height="20" viewBox="0 0 21 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <rect x="0.285706" width="20" height="20" rx="6" fill="white"/>
  <path d="M6.95239 8.33334L10.2857 11.6667L13.6191 8.33334" stroke="#8591AE" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'close'" width="21" height="20" viewBox="0 0 21 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M6.80951 6.66666L13.4762 13.3333" stroke="#8591AE" stroke-linecap="round" stroke-linejoin="round"/>
  <path d="M13.4762 6.66666L6.80951 13.3333" stroke="#8591AE" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'edit'" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M11.6932 6.74667L9.25317 4.30667" stroke="#8591AE" stroke-linecap="round" stroke-linejoin="round"/>
  <path fill-rule="evenodd" clip-rule="evenodd" d="M4.16721 14H1.99988V11.8327C1.99988 11.656 2.06988 11.486 2.19521 11.3613L11.0845 2.47135C11.3452 2.21068 11.7672 2.21068 12.0272 2.47135L13.5279 3.97202C13.7885 4.23268 13.7885 4.65468 13.5279 4.91468L4.63854 13.8047C4.51388 13.93 4.34388 14 4.16721 14V14Z" stroke="#8591AE" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<svg v-else-if="name === 'delete'" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M5.49784 7.49894C5.49784 7.2228 5.27398 6.99894 4.99784 6.99894C4.72169 6.99894 4.49784 7.2228 4.49784 7.49894H5.49784ZM15.502 7.49894C15.502 7.2228 15.2781 6.99894 15.002 6.99894C14.7259 6.99894 14.502 7.2228 14.502 7.49894H15.502ZM12.1673 8.33262C12.1673 8.05648 11.9434 7.83262 11.6673 7.83262C11.3911 7.83262 11.1673 8.05648 11.1673 8.33262H12.1673ZM11.1673 14.1684C11.1673 14.4445 11.3911 14.6684 11.6673 14.6684C11.9434 14.6684 12.1673 14.4445 12.1673 14.1684H11.1673ZM8.83256 8.33262C8.83256 8.05648 8.6087 7.83262 8.33256 7.83262C8.05642 7.83262 7.83256 8.05648 7.83256 8.33262H8.83256ZM7.83256 14.1684C7.83256 14.4445 8.05642 14.6684 8.33256 14.6684C8.6087 14.6684 8.83256 14.4445 8.83256 14.1684H7.83256ZM3.74731 4.4979C3.47117 4.4979 3.24731 4.72176 3.24731 4.9979C3.24731 5.27404 3.47117 5.4979 3.74731 5.4979V4.4979ZM16.2525 5.4979C16.5287 5.4979 16.7525 5.27404 16.7525 4.9979C16.7525 4.72176 16.5287 4.4979 16.2525 4.4979V5.4979ZM6.19086 4.83979C6.10353 5.10176 6.24511 5.38492 6.50708 5.47224C6.76905 5.55957 7.05221 5.41799 7.13954 5.15601L6.19086 4.83979ZM7.11872 3.63733L7.59306 3.79545L7.5931 3.79533L7.11872 3.63733ZM8.70104 2.49686L8.70092 2.99686H8.70104V2.49686ZM11.2988 2.49686V2.99686L11.2994 2.99686L11.2988 2.49686ZM12.8828 3.63733L13.3573 3.47974L13.3572 3.47933L12.8828 3.63733ZM12.8601 5.15549C12.9472 5.41756 13.2302 5.55945 13.4922 5.47242C13.7543 5.38538 13.8962 5.10238 13.8092 4.84031L12.8601 5.15549ZM4.49784 7.49894V15.8357H5.49784V7.49894H4.49784ZM4.49784 15.8357C4.49784 17.0327 5.4682 18.0031 6.6652 18.0031V17.0031C6.02048 17.0031 5.49784 16.4805 5.49784 15.8357H4.49784ZM6.6652 18.0031H13.3346V17.0031H6.6652V18.0031ZM13.3346 18.0031C14.5316 18.0031 15.502 17.0327 15.502 15.8357H14.502C14.502 16.4805 13.9794 17.0031 13.3346 17.0031V18.0031ZM15.502 15.8357V7.49894H14.502V15.8357H15.502ZM11.1673 8.33262V14.1684H12.1673V8.33262H11.1673ZM7.83256 8.33262V14.1684H8.83256V8.33262H7.83256ZM3.74731 5.4979H16.2525V4.4979H3.74731V5.4979ZM7.13954 5.15601L7.59306 3.79545L6.64438 3.47922L6.19086 4.83979L7.13954 5.15601ZM7.5931 3.79533C7.75194 3.31842 8.19825 2.99674 8.70092 2.99686L8.70116 1.99686C7.76788 1.99663 6.93926 2.59387 6.64434 3.47933L7.5931 3.79533ZM8.70104 2.99686H11.2988V1.99686H8.70104V2.99686ZM11.2994 2.99686C11.8025 2.99623 12.2494 3.31801 12.4084 3.79533L13.3572 3.47933C13.062 2.59312 12.2323 1.9957 11.2982 1.99686L11.2994 2.99686ZM12.4083 3.79492L12.8601 5.15549L13.8092 4.84031L13.3573 3.47974L12.4083 3.79492Z" fill="#8591AE"/>
</svg>
</template>

<script>
export default {
  props: {
    name: {
      type: String
    }
  }
}
</script>

<style>
template {
  color: #8F20EF;
}
</style>