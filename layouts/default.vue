<template>
  <v-app>

    <v-app-bar elevate-on-scroll fixed app color="#ffffff" height="80px">   
      <div class="container d-flex pa-0">
        <NuxtLink to="/" class="logo d-flex align-center">
          <v-btn class="mr-3 primary black--text" rounded fab depressed small>
            <span color="#233348">TM</span>
          </v-btn>
          <span style="color: #233348">Total Master</span>
        </NuxtLink>
        
        <v-spacer />

        <!-- menu-btn-acive : havn't done yet. (on-active show weight 700) -->
        <div class="hidden-lg-and-down d-lg-flex">
          <div class="d-flex flex-row flex-wrap align-center ml-10">
            <nuxt-link class="menu-btn" v-for="(item, i) in items" :key="i" :to="item.to">
              <span>{{ item.title }}</span>
            </nuxt-link>
          </div>

          <!-- <v-app-bar-nav-icon text rounded default class="hidden-lg-and-up"></v-app-bar-nav-icon> -->
          
          <div style="min-width: 245px">
            <v-btn class="mr-7 text-capitalize primary" rounded light depressed large href="/register">
              <span>register</span>
            </v-btn>
            <v-btn class="mr-7 text-capitalize primary--text" outlined rounded light depressed large href="/signin">
              <span>sign in</span>
            </v-btn>
          </div>
        </div>
      </div>
      
      <!-- <v-navigation-drawer right absolute temporary style="height: 100vh; top: 0px; transform: translateX(100%); width: 100%;"></v-navigation-drawer> -->

    </v-app-bar>

    <v-main>
        <nuxt />
    </v-main>
    
    <!-- <v-footer
      :absolute="!fixed"
      app
    >
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer> -->
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          title: 'Home',
          to: '/'
        },
        {
          title: 'Benefit',
          to: '/benefit'
        },
        {
          title: 'Services',
          to: '/services'
        },
        {
          title: "Customer's voice",
          to: '/cvoice'
        },
        {
          title: 'Contact Us',
          to: '/contactus'
        },
        {
          title: 'About Us',
          to: '/aboutus'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Total Master'
    }
  }
}
</script>

<style lang="stylus" scoped>
.logo{
    height: 45px;
    color: #233348;
    font-size: 24px;
    font-weight: 700;
    text-decoration: none;
}
.menu-btn{
    color: #1f1534;
    text-decoration: none;
    margin-right: 40px;
}
.menu-btn-active{
    font-weight: 700;
}
</style>