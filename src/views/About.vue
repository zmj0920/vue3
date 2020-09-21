<script lang="tsx">
import { defineComponent } from 'vue'

const wrapper = defineComponent({
  setup() {
    return () => (
      <div>
      	一段文字
      	<h1 class="ok">
      		标题
      	</h1>
      </div>
    )
  },
})
export default wrapper
</script>