# Minimal Reproduction

For VuePress 2 not highlighting `vue-html` code blocks when using `@vuepress/plugin-shiki`.

1. `npm install`
2. `npm run dev`

To see the difference with Prism.js, disable the custom plugins in `.vuepress/config.js`.

```vue-html
<CFormGroup required>
  <CLabel>Label</CLabel>
  <CTextField />
</CFormGroup>
```
