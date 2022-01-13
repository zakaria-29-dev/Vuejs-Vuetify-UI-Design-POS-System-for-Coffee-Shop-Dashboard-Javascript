<template>
  <v-navigation-drawer v-model="drawer" app color="white" mini-variant mini-variant-width="90">
      <v-avatar class="d-block text-center mx-auto mt-4" size="40">
          <v-icon color="#704232">fas fa-coffee</v-icon>
      </v-avatar>
      <v-list flat class="mt-4">
          <v-list-item-group v-model="selectedItem">
              <v-list-item v-for="(item, i) in items" :key="i" active-class="border" :ripple="false">
                  <v-list-item-content>
                      <v-icon v-text="item.icon"></v-icon>
                      <v-list-item-subtitle align="center" v-text="item.text" class="mt-3 caption"></v-list-item-subtitle>
                  </v-list-item-content>
              </v-list-item>
          </v-list-item-group>
      </v-list>
      <div style="position: absolute; bottom: 20px; margin-left: auto; margin-right: auto; left:0; right:0; text-align: center;">
          <v-icon>fas fa-sign-out-alt</v-icon><br><span class="caption">Logout</span>
      </div>
  </v-navigation-drawer>
</template>

<script>
export default {
data: () => ({
    selectedItem: 0,
    drawer: null,
    items: [
        {icon: 'fas fa-home', text:'Home'},
        {icon: 'fas fa-hamburger', text:'Menu'},
        {icon: 'fas fa-history', text:'History'},
        {icon: 'fas fa-wallet', text:'Wallet'},
        {icon: 'fas fa-percent', text:'Promo'},
        {icon: 'fas fa-cog', text:'Setting'},
    ],
})
}
</script>

<style>
.border {
    margin-left: 8px;
    margin-right: 8px;
    background: #704232;
    border-radius: 20px;
    text-decoration: none;
}
.v-list-item-group .v-list-item--active {
    color: white !important;
}
.theme--light.v-list-item--active .v-list-item__subtitle, .theme--light.v-list-item .v-list-item__action-text {
    color: white !important;
}
</style>