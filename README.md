# conventional-commits

### Структура:
`<тип>` `[необязательный контекст]:` `<описание>`

### Примеры:
``` cpp
build(deps-dev): bump the playwright group with 2 updates

feature(Input): disable controls for type="number"
feature(Tappable): add borderRadiusMode

fix(Avatar/BaseImage): dispatch load img event if resource is already…
fix(PanelHeader): add z-index for visor={false}
```

### Типы коммитов:
* `build` — вносит изменение, влияющее на систему сборки или внешние зависимости
* `docs` — вносит изменение только в документацию
* `feature` — добавляет новую функцию
* `fix` — исправляет баг
* `perf` — вносит изменение, повышающее производительность
* `refactor` — вносит изменение, которое не исправляет ошибку и не добавляет новую функцию
* `style` — вносит изменение, не влияющее на смысл кода
* `test` — добавляет отсутствующие тесты или исправляет существующие

### Ссылки:
* [VKCOM/VKUI](https://github.com/VKCOM/VKUI/commits/master)
* [Conventional Commits](https://www.conventionalcommits.org/ru/v1.0.0/)
* [Angular](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#-commit-message-guidelines)
