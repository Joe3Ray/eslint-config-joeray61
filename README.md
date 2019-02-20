# JavaScript style guide of JoeRay61

> Note: 推荐使用局部安装的`eslint`进行校验，如果使用全局安装的`eslint`进行校验，请手动全局安装依赖`eslint-plugin-react`

## 安装

```
npm i -D eslint eslint-config-joeray61
```

## 支持环境

- `browser`
- `node`
- `es6`

## 使用

`.eslintrc`

`JS` 项目

```
{
  "extends": "joeray61"
}
```

`React` 项目

```
{
  "extends": "joeray61/react"
}
```

`joeray61/react`继承了`joeray61`的配置并添加了`React`相关规则
