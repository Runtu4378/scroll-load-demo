<template>
  <div class="multi-tab">
    <Tabs value="name1">
      <TabPane label="标签一" name="name1">
        <Tab1/>
      </TabPane>
      <TabPane label="标签二" name="name2">
        <Tab2 />
      </TabPane>
    </Tabs>
  </div>
</template>

<script>
import Tab1 from './Tab1'
import Tab2 from './Tab2'

export default {
  components: {
    Tab1,
    Tab2
  }
}
</script>
