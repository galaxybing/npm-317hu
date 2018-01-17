# npm-317hu

**Forked from [sinalvee/pkg-save](https://github.com/sinalvee/pkg-save)**

Add feature: 1) Save cnpm's @317hu/* installed package(s) to package.json. 2) Config npm --registry value : `http://registry.npm.intra.317hu.com`.

## Install

`npm install npm317hu -g`

## Usage

`npm317hu <name> [option]`

### Options

```
-d, --dev      Save package to devDependencies
-h, --help     Show help
-v, --version  Show version number
```
### Examples

```
npm317hu @317hu/MainTemplateLayout                                      Save to @317huDependencies
npm317hu @317hu/MainTemplateLayout --dev                                Save to devDependencies
npm317hu @317hu/MainTemplateLayout @317hu/CascaderCheckboxSelect        Save * to @317huDependencies
npm317hu @317hu/MainTemplateLayout @317hu/CascaderCheckboxSelect --dev  Save * to devDependencies
```

## License

MIT
