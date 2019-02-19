<template>
  <z-view class="main-background" >
    <div slot="extension">
      <!-- about me-->
      <z-spot

        :angle="-160"
        size="xl"
        :distance="180"
        to-view="aboutMe">
        <img class="profile-img" src="../assets/profileAbout.jpg" alt="Palmidia Garay Javascript Developer">
      </z-spot>
      <!-- projects-->
      <z-spot
        :angle="-50"
        size="l"
        :distance="150"
        label-pos="bottom"
        to-view="projects">
        <p>
        <i class="fas fa-th-list"><p>Projects</p></i>
        </p>
      </z-spot>
      <!-- Linkedn-->
      <z-spot
        :angle="-10"
        size="m"
        :distance="138">
            <a href="https://www.linkedin.com/in/jetzable/" target="_blank">       
             <i class="fab fa-linkedin-in"></i>
             </a>
      </z-spot>
            <!-- GitHub-->
      <z-spot
        :angle="20"
        size="m"
        :distance="135">
            <a href="https://github.com/jetzable" target="_blank">       
             <i class="fab fa-github"></i>
             </a>
      </z-spot>
      
      <!-- cv-->
      <z-spot
      label="CV"
      label-pos="bottom"
        :angle="60"
        :distance="130"
        size="s"
        to-view="devices">
        <i class="far fa-file-alt"></i>
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
a, i, span, h1{
  color: azure
}

.profile-img{
  width: 100%;
  border-radius: 50%
}

</style>
