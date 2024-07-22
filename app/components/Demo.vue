<template>
  <TresCanvas window-size clear-color="#82dbc5">
    <TresMesh>
      <TresBoxGeometry :args="[2, 1, 1]" />
      <TresMeshBasicMaterial color="yellow" />
    </TresMesh>
  </TresCanvas>
</template>
