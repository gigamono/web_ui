<template lang="pug">
  svg(id="brand-svg", class="{$$props.class}", width="201", height="275", viewBox="0 0 201 275", fill="none", xmlns="http://www.w3.org/2000/svg")
    path(id="brand-svg-path-1", fill-rule="evenodd", clip-rule="evenodd", d="M100 200C155.228 200 200 155.228 200 100C200 80.8639 194.625 62.9832 185.302 47.7853C193.97 43.86 200 35.1342 200 25C200 11.1929 188.807 0 175 0C164.866 0 156.14 6.02998 152.215 14.6978C137.017 5.37506 119.136 0 100 0C44.7715 0 0 44.7715 0 100C0 155.228 44.7715 200 100 200ZM100 150C72.3858 150 50 127.614 50 100C50 72.3858 72.3858 50 100 50C127.614 50 150 72.3858 150 100C150 127.614 127.614 150 100 150Z", fill="url(#brand-svg-gradient)")
    path(id="brand-svg-path-2", fill-rule="evenodd", clip-rule="evenodd", d="M200.48 193C200.48 187.234 192.768 184.506 188.682 188.574C179.492 197.725 168.892 205.433 157.229 211.376C136.689 221.842 113.654 226.423 90.6725 224.615C69.6879 222.963 49.4935 216.042 31.9438 204.536C29.1726 202.719 25.4278 203.3 23.48 205.981L1.14421 236.724C-0.803544 239.405 -0.214857 243.166 2.53117 245.021C27.5604 261.926 56.5713 272.085 86.7496 274.461C118.924 276.993 151.172 270.578 179.928 255.926C186.141 252.761 192.138 249.238 197.893 245.382C199.523 244.289 200.48 242.444 200.48 240.481V193Z", fill="#c5c5c5")
    defs
      linearGradient(id="brand-svg-gradient", x1="100", y1="0", x2="100", y2="200", gradientUnits="userSpaceOnUse")
        stop(id="brand-svg-stop-1", stop-color="#c5c5c5")
        stop(id="brand-svg-stop-2", offset="1", stop-color="#c5c5c5")
</template>

<style lang="scss">
  #brand-svg {
    > #brand-svg-path-2 {
      fill: var(--color-brand-secondary);
    }

    > defs {
      > #brand-svg-gradient {
        > #brand-svg-stop-1 {
          stop-color: var(--color-brand-primary);
        }
        > #brand-svg-stop-2 {
          stop-color: var(--color-brand-secondary);
        }
      }
    }
  }
</style>
