  
  ##qiankun项目搭建简要说明
主应用的Vue3和子应用的Vue2
主应用
main.js
app.vue
vue.config.js

```

module.exports = {
  transpileDependencies: ["single-spa", "qiankun", "import-html-entry"],
};
module.exports \= {
  transpileDependencies: \["single-spa", "qiankun", "import-html-entry"\],
};
```

子应用
public_path.js
main.js
vue.config.js
