here is fix:
`https://github.com/magento/magento2/pull/39283/commits/0d8f9034684b653a164b2296f71c85d1eb63e2de`

to get path add patch on the end

`https://github.com/magento/magento2/pull/39283/commits/0d8f9034684b653a164b2296f71c85d1eb63e2de.patch`

add to composer.json 

```
json "magento/module-reports": {
  "Fix for /Banneritem/Save.php": "https://github.com/magento/magento2/commit/0d8f9034684b653a164b2296f71c85d1eb63e2de.patch"
}
```
