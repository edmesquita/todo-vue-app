<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline">
        <span>Todo App</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>

    </v-toolbar>

    <v-content>      
      <Task/>
    </v-content>
  </v-app>
</template>

<script>

import Task from './components/Task'

export default {
  name: 'App',
  components: {    
    Task
  },
  data () {
    return {
      //
    }
  }
}
</script>
