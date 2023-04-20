mapMutations & mapActions
- 之前提到的mapState & mapGetters通常是放在计算属性computed中
    - 通过它们两个来快捷的生成计算属性，并通过state和getters来获取
- mapMutations和mapActions
    - mapMutations
        - ...mapMutations(['JIA','JIAN']),
        - 借助mapMutations生成对应的方法，方法中会调用commit去联系mutations(数组写法)
    - mapActions
        - ...mapActions(['jiaOdd','jiaWait'])
        - 借助mapActions生成对应的方法，方法中会调用dispatch去联系action