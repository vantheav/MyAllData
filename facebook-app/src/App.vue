<template>
  <v-app>
      <Toolbar></Toolbar>
      <DrawerRight></DrawerRight>
      <Drawerleft></Drawerleft>
      <v-container>
          <Feed></Feed>
      </v-container>
  </v-app>
</template>

<script>
import Toolbar from './components/ToolBar.vue'
import DrawerRight from './components/DrawerRight.vue'
import DrawerLeft from "./components/DrawerLeft.vue"
import Feed from "./components/Feed.vue";
export default {
  components:{
    'Toolbar': Toolbar,
    'DrawerRight': DrawerRight,
    'Drawerleft' : DrawerLeft,
    'Feed' : Feed,
  },
  data: () => ({
    links: ["Dashboard", "Messages", "Profile", "Updates"],
  }),
};
</script>

