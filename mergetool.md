[< к содержанию](./readme.md)

## git mergetool

**git mergetool** - просто вызывает внешнюю программу слияний, в случае если у вас возникли проблемы слияния.

Если при слиянии двух веток у вас возникнут конфликты, выполните команду _git mergetool_; она запустит P4Merge чтобы вы могли разрешить конфликты используя графический интерфейс.

+  _--tool-help_ - просмотр списка поддерживаемых инструментов.

```bash=
git mergetool
git mergetool --tool-help
```