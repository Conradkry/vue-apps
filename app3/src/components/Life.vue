<template>
  <div id="life">
    <div id="title">Death</div>
    <img alt="tombstone" src="../assets/Life.jpeg" />
    <div id="caption">gives life meaning</div>
  </div>
</template>

<style>
#life {
  aspect-ratio: 1 / 1;
  width: 200pt;
  background-color:rgb(49, 49, 49);
  border-radius: 9px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
#title {
  font-size: 25pt;
  color: white;
}
#caption {
  font-size: 15pt;
  color: white;
}
img {
  display: inline-block;
  width: 50%;
}
</style>