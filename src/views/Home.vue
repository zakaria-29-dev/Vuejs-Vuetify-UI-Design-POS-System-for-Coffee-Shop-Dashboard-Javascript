<template>
 <v-app :style="{background: $vuetify.theme.themes.dark.background}">
   <SideBar />
   <SideBarRight />
   <v-container>
     <v-toolbar color="rgba(0,0,0,0)" flat>
       <v-toolbar-title class="mt-n3">Choose Category</v-toolbar-title>
       <v-spacer></v-spacer>
       <v-text-field label="Search category or menu..." 
            class="mt-5"
            color="brown"
            filled  append-icon="mdi-magnify" 
            dense solo flat background-color="grey lighten-4"  ></v-text-field>
       </v-toolbar>
       <v-item-group mandatory class="mt-n1">
    <v-container>
      <v-row justify="center" class="space">
        <v-col
          cols="12"
          md="2"
        >
          <v-item v-slot="{ active, toggle }" > 
           <v-card
              :color="active ? '#F6EFEF' : 'white'"
              :class="active ? 'borderme' : 'borderout'"
              class="d-flex align-center rounded-lg mx-2"
              dark
              height="140"
              @click="toggle"
              flat
            >
              <v-row>
                <v-col cols="12" sm="12">
                  <v-list-item three-line  class="text-center ">
                    <v-list-item-content>
                      <div align="center" justify="center">
                       
                          <v-img  src="c1.png" max-height="110" max-width="110" contain></v-img>
                       
                      </div>
                      <v-list-item-subtitle
                       :class="active ? 'brown--text' : 'black--text'" class=" caption mt-4">ALL</v-list-item-subtitle>
                      
                    </v-list-item-content>
                  </v-list-item>
                </v-col>
              </v-row>
              
            </v-card>
          </v-item>
        </v-col>
         <v-col
          cols="12"
          md="2"
        >
          <v-item v-slot="{ active, toggle }" > 
           <v-card
              :color="active ? '#F6EFEF' : 'white'"
              :class="active ? 'borderme' : 'borderout'"
              class="d-flex align-center rounded-lg mx-2"
              dark
              height="140"
              @click="toggle"
              flat
              
            >
              <v-row>
                <v-col cols="12" sm="12">
                  <v-list-item three-line  class="text-center ">
                    <v-list-item-content>
                      <div align="center" justify="center">
                       
                          <v-img  src="c2.png" max-height="90" max-width="90" contain></v-img>
                       
                      </div>
                      <v-list-item-subtitle
                   :class="active ? 'brown--text' : 'black--text'" class=" caption mt-3">Coffee</v-list-item-subtitle>
                      
                    </v-list-item-content>
                  </v-list-item>
                </v-col>
              </v-row>
              
            </v-card>
          </v-item>
        </v-col>
         <v-col
          cols="12"
          md="2"
        >
          <v-item v-slot="{ active, toggle }" > 
           <v-card
              :color="active ? '#F6EFEF' : 'white'"
              :class="active ? 'borderme' : 'borderout'"
              class="d-flex align-center rounded-lg mx-2"
              dark
              height="140"
              @click="toggle"
              flat
            >
              <v-row>
                <v-col cols="12" sm="12">
                  <v-list-item three-line  class="text-center ">
                    <v-list-item-content>
                      <div align="center" justify="center">
                       
                          <v-img  src="c3.png" max-height="80" max-width="80" contain></v-img>
                       
                      </div>
                      <v-list-item-subtitle
                       :class="active ? 'brown--text' : 'black--text'" class=" caption mt-2">Juice</v-list-item-subtitle>
                      
                    </v-list-item-content>
                  </v-list-item>
                </v-col>
              </v-row>
              
            </v-card>
          </v-item>
        </v-col>
         <v-col
          cols="12"
          md="2"
        >
          <v-item v-slot="{ active, toggle }" > 
           <v-card
              :color="active ? '#F6EFEF' : 'white'"
              :class="active ? 'borderme' : 'borderout'"
              class="d-flex align-center rounded-lg mx-2"
              dark
              height="140"
              @click="toggle"
              flat
            >
              <v-row>
                <v-col cols="12" sm="12">
                  <v-list-item three-line  class="text-center ">
                    <v-list-item-content>
                      <div align="center" justify="center">
                       
                          <v-img  src="c4.png" max-height="80" max-width="80" contain></v-img>
                       
                      </div>
                      <v-list-item-subtitle :class="active ? 'brown--text' : 'black--text'"
                       class=" caption mt-2">Milk Based</v-list-item-subtitle>
                      
                    </v-list-item-content>
                  </v-list-item>
                </v-col>
              </v-row>
              
            </v-card>
          </v-item>
        </v-col>
         <v-col
          cols="12"
          md="2"
        >
          <v-item v-slot="{ active, toggle }" > 
           <v-card
              :color="active ? '#F6EFEF' : 'white'"
              :class="active ? 'borderme' : 'borderout'"
              class="d-flex align-center rounded-lg mx-2"
              dark
              height="140"
              @click="toggle"
              flat
            >
              <v-row>
                <v-col cols="12" sm="12">
                  <v-list-item three-line  class="text-center ">
                    <v-list-item-content>
                      <div align="center" justify="center">
                       
                          <v-img  src="c5.png" max-height="110" max-width="110" contain></v-img>
                       
                      </div>
                      <v-list-item-subtitle :class="active ? 'brown--text' : 'black--text'" 
                      class=" caption mt-3">Snack</v-list-item-subtitle>
                      
                    </v-list-item-content>
                  </v-list-item>
                </v-col>
              </v-row>
              
            </v-card>
          </v-item>
        </v-col>
         <v-col
          cols="12"
          md="2"
        >
          <v-item v-slot="{ active, toggle }" > 
           <v-card
              :color="active ? '#F6EFEF' : 'white'"
              :class="active ? 'borderme' : 'borderout'"
              class="d-flex align-center rounded-lg mx-2"
              dark
              height="140"
              @click="toggle"
              flat
            >
              <v-row>
                <v-col cols="12" sm="12">
                  <v-list-item three-line  class="text-center ">
                    <v-list-item-content>
                      <div align="center" justify="center">
                       
                          <v-img  src="c6.png" max-height="110" max-width="110" contain></v-img>
                       
                      </div>
                      <v-list-item-subtitle :class="active ? 'brown--text' : 'black--text'"
                       class=" caption mt-4">Dessert</v-list-item-subtitle>
                      
                    </v-list-item-content>
                  </v-list-item>
                </v-col>
              </v-row>
              
            </v-card>
          </v-item>
        </v-col>
      </v-row>
     
    </v-container>
  </v-item-group>
  <v-toolbar color="#EEEEEE" flat>
    <v-toolbar-title>Coffee Menu</v-toolbar-title><v-spacer></v-spacer><span color="grey">12 Coffees Results</span>
  </v-toolbar>
  <v-row>
    <v-col cols="12" sm="6">
      <v-card    
    flat class="rounded-lg mx-5"
  >
    <v-list-item three-line>
       <v-list-item-avatar
        rounded
        size="120"
        color="grey lighten-4"
      >
      <v-img src="2.png"></v-img>
      </v-list-item-avatar>
      <v-list-item-content>
        <v-list-item-title class="text-h5">
          Caramel Frappuccino
        </v-list-item-title>
        <v-list-item-subtitle class="mt-1">Caramel sytrup with coffee, milk, and whipped cream</v-list-item-subtitle>
        <strong class="mt-3">
          $3.95
        </strong>
        
        
      </v-list-item-content>

     
    </v-list-item>

    <v-card-actions>
     <v-row>
       <v-col cols="12" sm="6" class="mt-1 ">
         <strong class="ml-3" >Mood</strong><br>
         <v-item-group mandatory class="mt-n1 ">
    <v-container>
      <v-row  class="">
        <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              dark
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <v-icon dark color="orange" >
        fas fa-fire
      </v-icon>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
         <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" class=""> 
      <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              dark
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <v-icon dark color="blue" >
      fab fa-modx
      </v-icon>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
      </v-row>
    </v-container>
         </v-item-group>


        
       </v-col>
       <v-col cols="12" sm="6" class="mt-1 ">
          <strong class="ml-3">Size</strong><br>
         <v-item-group mandatory class="mt-n1">
    <v-container>
      <v-row  class="">
        <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="font-weight-black">S</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
          <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="font-weight-black">M</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
          <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="font-weight-black">L</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
      </v-row>
    </v-container>
         </v-item-group>
       </v-col>
       
     </v-row>
     
    </v-card-actions>
    <v-card-actions>
     <v-row>
       <v-col cols="12" sm="6" class="mt-1 ">
         <strong class="ml-3" >Sugar</strong><br>
        
 <v-item-group mandatory class="mt-n1">
    <v-container>
      <v-row  class="">
        <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle"
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="overline" :class="active ? 'brown--text' : 'red--text'">30%</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
          <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="overline" :class="active ? 'brown--text' : 'red--text'">50%</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
          <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="overline" :class="active ? 'brown--text' : 'red--text'">70%</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
      </v-row>
    </v-container>
         </v-item-group>
        
       </v-col>
       <v-col cols="12" sm="6" class="mt-1 ">
          <strong class="ml-3">Ice</strong><br>
       <v-item-group mandatory class="mt-n1">
    <v-container>
      <v-row  class="">
        <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle"
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="overline" :class="active ? 'brown--text' : 'red--text'">30%</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
          <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="overline" :class="active ? 'brown--text' : 'red--text'">50%</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
          <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="overline" :class="active ? 'brown--text' : 'red--text'">70%</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
      </v-row>
    </v-container>
         </v-item-group>
       </v-col>
       
     </v-row>
     
    </v-card-actions>
   <v-card-actions>
     
 <v-btn color="#704232" block dark class="withoutupercase mb-2">Add Billing</v-btn>
 
   </v-card-actions>
  </v-card>
    </v-col>
    <v-col cols="12" sm="6">
       <v-card    
    flat class="rounded-lg mx-5"
  >
    <v-list-item three-line>
       <v-list-item-avatar
        rounded
        size="120"
        color="grey lighten-4"
      >
      <v-img src="3.png"></v-img>
      </v-list-item-avatar>
      <v-list-item-content>
        <v-list-item-title class="text-h5">
          Chocolate Frappuccino
        </v-list-item-title>
        <v-list-item-subtitle class="mt-1">Sweet chocolate with coffee, milk, and whipped cream</v-list-item-subtitle>
        <strong class="mt-3">
          $4.51
        </strong>
        
        
      </v-list-item-content>

     
    </v-list-item>

    <v-card-actions>
     <v-row>
       <v-col cols="12" sm="6" class="mt-1 ">
         <strong class="ml-3" >Mood</strong><br>
         <v-item-group mandatory class="mt-n1 ">
    <v-container>
      <v-row  class="">
        <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              dark
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <v-icon dark color="orange" >
        fas fa-fire
      </v-icon>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
         <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" class=""> 
      <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              dark
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <v-icon dark color="blue" >
      fab fa-modx
      </v-icon>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
      </v-row>
    </v-container>
         </v-item-group>


        
       </v-col>
       <v-col cols="12" sm="6" class="mt-1 ">
          <strong class="ml-3">Size</strong><br>
         <v-item-group mandatory class="mt-n1">
    <v-container>
      <v-row  class="">
        <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="font-weight-black">S</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
          <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="font-weight-black">M</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
          <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="font-weight-black">L</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
      </v-row>
    </v-container>
         </v-item-group>
       </v-col>
       
     </v-row>
     
    </v-card-actions>
    <v-card-actions>
     <v-row>
       <v-col cols="12" sm="6" class="mt-1 ">
         <strong class="ml-3" >Sugar</strong><br>
        
 <v-item-group mandatory class="mt-n1">
    <v-container>
      <v-row  class="">
        <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle"
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="overline" :class="active ? 'brown--text' : 'red--text'">30%</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
          <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="overline" :class="active ? 'brown--text' : 'red--text'">50%</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
          <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="overline" :class="active ? 'brown--text' : 'red--text'">70%</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
      </v-row>
    </v-container>
         </v-item-group>
        
       </v-col>
       <v-col cols="12" sm="6" class="mt-1 ">
          <strong class="ml-3">Ice</strong><br>
       <v-item-group mandatory class="mt-n1">
    <v-container>
      <v-row  class="">
        <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle"
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="overline" :class="active ? 'brown--text' : 'red--text'">30%</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
          <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="overline" :class="active ? 'brown--text' : 'red--text'">50%</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
          <v-col
          cols="12"
          md="4"
        >
          <v-item v-slot="{ active, toggle }" > 
            <v-card
             color="#F6EFEF" 
            :class="active ? 'borderme' : ''"
           class="d-flex align-center rounded-circle "
              
              height="50"
              width="50"
              @click="toggle"
              flat
            >
 <v-list-item class="text-center">
    <v-list-item-content>
      <strong class="overline" :class="active ? 'brown--text' : 'red--text'">70%</strong>
        </v-list-item-content>
 </v-list-item>
   </v-card>
          </v-item>
        </v-col>
      </v-row>
    </v-container>
         </v-item-group>
       </v-col>
       
     </v-row>
     
    </v-card-actions>
   <v-card-actions>
     
 <v-btn color="#704232" block dark class="withoutupercase mb-2">Add Billing</v-btn>
 
   </v-card-actions>
  </v-card>
    </v-col>
  </v-row>
   </v-container>

 </v-app>
</template>

<script>
  import SideBar from '../components/SideBar'
  import SideBarRight from '../components/SideBarRight'

  export default {
    name: 'Home',

    components: {
      SideBar,
      SideBarRight
    },
  }
</script>
<style>
.v-card.borderme {
    border: 2px solid #704232 !important;
}
.v-card.borderout{
  border: 1px solid #BCAAA4 !important;
}
</style>
