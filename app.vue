<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
<style>
::-webkit-scrollbar {
  width: 3px;
  height: 3px;
  background-color: transparent !important;
  margin-right: 30px;
}

::-webkit-scrollbar-track {
  background-color: rgba(179, 179, 179, 0);
  border-radius: 1rem;
  margin: 0.8rem;
  border-left: 1px solid rgba(211, 211, 211, 0);
}

::-webkit-scrollbar-thumb {
  border-radius: 1rem;
  background: linear-gradient(30deg, #64646441, #7e7e7e93);
  box-shadow: inset 0 0 6px #616161;
}
</style>
