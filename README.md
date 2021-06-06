### 用vue封装的一个tabbar组件

src > components > tabbar > MainTabbar

```vue
<TabBaritem path="/home" activeColor="">
      <img slot="item-icon" src="" alt />
      <img slot="item-icon-active" src="" alt />
      <div slot="item-text">首页</div>
 </TabBaritem>
```

activeColor  是tabbar文字的颜色，默认为red

slot="item-icon"  是正常状态下的图片

slot="item-icon-active"  是被选中状态下的图片