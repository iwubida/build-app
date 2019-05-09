# build-app

通过git的tag和commit来触发gitlab CI,具体打包规则：

- 正式包触发规则：
打 tag 以下规则开头
`ios/v***`和
`android/v***`

- 测试包触发规则：
提交 message内容 开头以下规则
`build:android`和`build:ios`