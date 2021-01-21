## css相关

1. 填充区域内svg的颜色
button {
  fill: red
}

2. 某元素的下一个元素
.icon + span {
  margin-left: 4px;
}

3. 元素调整位置
.ss-button-left {
  svg {order: 1};
  span {order: 2};
}

.ss-button-right {
  span {order: 1};
  svg {order: 2};
}

## 控制台
1. console.dir()
2. console.assert(this.$el.tagName === 'BUTTON', '子元素必须是button')



## 命令行命令
1. nvm ls
node版本号控制
2. nrm ls
npm包源控制