# generamba-tableview-content-catalog

It's a shared catalog of templates for [Generamba](https://github.com/strongself/Generamba) code generator.

## Usage

1. Add templates to `Rambafile` .

```yaml:Rambafile
### Templates
catalogs:
- 'https://github.com/0x0c/generamba-tableview-content-catalog'
templates:
- {name: 0x0c_viper_tableview_content_layout}
```

2. Run `generamba template install` .

3. Run `generamba gen [Module name] [Tempalate name]` .

## Templates

- [0x0c_viper_tableview_content](https://raw.githubusercontent.com/0x0c/generamba-tableview-content-catalog/main/0x0c_viper_tableview_content/0x0c_viper_tableview_content.rambaspec)

# Dependencies

- [TableViewContent](https://github.com/0x0c/TableViewContent)
- [TableViewContentViperExtension](https://github.com/0x0c/TableViewContentViperExtension)
