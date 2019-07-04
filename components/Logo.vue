<template functional>
  <img class="willweb-logo" alt="Will Web Logo" src="/logo_transparent.png" />
</template>

<style>
.willweb-logo {
  width: 180px;
  transform: rotateY(360deg);
  animation: turn 3.5s ease-out forwards 1s;
}

@keyframes turn {
  100% {
    transform: rotateY(0deg);
  }
}
</style>
