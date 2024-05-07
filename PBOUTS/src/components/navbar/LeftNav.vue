<template>
    <v-navigation-drawer
      expand-on-hover
      rail
    >
      <v-list>
        <v-list-item
          prepend-avatar="https://h7.alamy.com/comp/2PWERD5/student-avatar-illustration-simple-cartoon-user-portrait-user-profile-icon-youth-avatar-vector-illustration-2PWERD5.jpg"
          subtitle="Farrel Fauzan Herawan"
          title="Farrel Fauzan"
        ></v-list-item>
      </v-list>

      <v-divider></v-divider>

      <v-list density="compact" nav>
        <v-list-item prepend-icon="mdi-home" title="Home" :to="'/home'"></v-list-item>
        <v-list-item prepend-icon="mdi-account-multiple" title="Dosen" :to="'/dosen-entry'"></v-list-item>
        <v-list-item prepend-icon="mdi-star" title="Mahasiswa" :to="'/mahasiswa-entry'"></v-list-item>
        <v-list-item prepend-icon="mdi-star" title="Ruangan" :to="'/ruangan-entry'"></v-list-item>
      </v-list>
    </v-navigation-drawer>

    <v-main style="height: 250px"></v-main>
</template>
