<template>
   <div id="app">
     <Level1/>
     <Level2/>
     <Level2a/>
     <LevelB1/>
     <LevelB2/>
     <LevelB3/>
     <LevelC/>
     <LevelG/>
     <LevelM/>
     <LevelPark/>
   </div>
</template>

<script>
import Level1 from '@/components/Floor/Level-1'
import Level2 from '@/components/Floor/Level-2'
import Level2a from '@/components/Floor/Level-2a'
import LevelB1 from '@/components/Floor/Level-B1'
import LevelB2 from '@/components/Floor/Level-B2'
import LevelB3 from '@/components/Floor/Level-B3'
import LevelC from '@/components/Floor/Level-C'
import LevelG from '@/components/Floor/Level-G'
import LevelM from '@/components/Floor/Level-M'
import LevelPark from '@/components/Floor/Level-Park'

export default {
    name: 'app',
    components:{
      Level1,
      Level2,
      Level2a,
      LevelB1,
      LevelB2,
      LevelB3,
      LevelC,
      LevelG,
      LevelM,
      LevelPark
    }
}
</script>

<style>
 rect:hover{
   fill:aqua;
   opacity: 0.5;
 }
</style>