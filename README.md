# npm-317hu

## Install

`npm --registry=http://registry.npm.intra.317hu.com/ install npm-317hu -g`

## Usage

`npm317 <name> [option]`

### Options

```
-d, --dev      Save package to devDependencies
-h, --help     Show help
-v, --version  Show version number
```
### Examples

```
npm317 @317hu/MainTemplateLayout                                      Save to @317huDependencies
npm317 @317hu/MainTemplateLayout --dev                                Save to devDependencies
npm317 @317hu/MainTemplateLayout @317hu/CascaderCheckboxSelect        Save * to @317huDependencies
npm317 @317hu/MainTemplateLayout @317hu/CascaderCheckboxSelect --dev  Save * to devDependencies
```

## License

MIT
