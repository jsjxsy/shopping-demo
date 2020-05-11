<template>
    <div class="hello">
        <div v-for="item in List" :key="item.id">
            <label>id:</label>
            <span>{{item.id}}</span><br/>
            <label>name:</label>
            <span>{{item.name}}</span><br/>
        </div>
    </div>
</template>>

<script>
import person from '../person'

export default {
  name: 'List',
  data () {
    return {
      List: person
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
