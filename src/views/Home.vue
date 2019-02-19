<template>
  <z-view class="main-background">
    <div slot="extension">
      <!-- about me-->
      <z-spot
        style="background-color: orange; border-width: 4px; border-color: var(--background-color);"
        :angle="-145"
        size="xl"
        :distance="170"
        to-view="aboutMe">
        <i style="color: var( --accent-text-color)" class="fas fa-user-alt"></i><br>
        <span style="color: var( --accent-text-color)">About Me</span>
      </z-spot>
      <!-- projects-->
      <z-spot
        :angle="-30"
        size="l"
        :distance="160"
        label-pos="top"
        to-view="projects">
        <p>
Projects
        <i class="fas fa-th-list"></i>
        </p>
      </z-spot>
      <!-- Linkedn-->
      <z-spot
        :angle="0"
        size="m"
        :distance="140"
        label-pos="right"
        to-view="linkedn">
        <i class="fab fa-linkedin-in"></i>
      </z-spot>
      <!-- rooms-->
      <z-spot
        :angle="30"
        size="s"
        :distance="120"
        label="Rooms"
        label-pos="right"
        to-view="rooms">
        5
      </z-spot>
      <!-- devices-->
      <z-spot
        :angle="60"
        :distance="120"
        size="s"
        label="Devices"
        label-pos="right"
        to-view="devices">
        45
      </z-spot>
      <!-- settings-->
      <z-spot
        :angle="150"
        :distance="120"
        size="s"
        label="Settings"
        to-view="settings">
        <i class="fas fa-sliders-h"></i>
      </z-spot>
    </div>
  </z-view>
</template>

<style scoped>
.main-background{
    background-image: url('../assets/profile.jpg');
    width: 100%;
    background-size: contain
}
</style>
