组件的自定义事件
- 父组件可以对子组件通过传递props，传递函数，子组件通过调用该函数传递数据
- 父组件通过@atguigu；子组件通过this.$emit('atguigu', data)来触发该自定义事件，以此来传递函数操作