[< к содержанию](./readme.md)

## git mv

**git mv** - переименование файлов. Или удобный способ переместить файл.

Переименовать файл или папку можно параметром _mv_. Для него указывается источник _source_ и назначение _destination_. Источник — реально существующий файл или папка, а назначение — существующая папка.

При выполнении команды файл или папка, указанные как источник, будут перемещены в папку назначения. Индекс будет обновлён соответственно, но изменения нужно записать с помощью команды _git add_ для нового файла и _git rm_ для старого.

```bash=
git mv dir1/somefile.js dir2
```