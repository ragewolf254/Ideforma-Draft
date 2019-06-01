<template>
  <div style="background-color: #fefefe">
    <Achievements/>
    <Core/>
    <Footer/>
  </div>
  
</template>

<script>
import Footer from '@/components/Footer/Footer'
import Core from '@/components/OurCore/Core'
import Achievements from '@/components/Achievements/Achievements'

export default {
  components: {
    Footer,
    Core,
    Achievements
  }
}
</script>
