# DevTools Project
[![My Java CI](https://github.com/reallyloud/java-dev-tools/actions/workflows/ci.yml/badge.svg)](https://github.com/reallyloud/java-dev-tools/actions/workflows/ci.yml)

| №  | Чек-поинт                       | Ожидаемый результат                                                                 |
|----|----------------------------------|-------------------------------------------------------------------------------------|
| 1  | Репозиторий готов                | Репозиторий на GitHub содержит код из DVT-8, `./gradlew checkstyleMain test jacocoTestCoverageVerification build` локально проходит. |
| 2  | Доступ к редактору workflow      | Вы находитесь в GitHub-редакторе `.github/workflows/ci.yml`.                        |
| 3  | Workflow создан                  | Файл `.github/workflows/ci.yml` закоммичен, во вкладке Actions появился запуск.     |
| 4  | Workflow прошёл                  | Во вкладке Actions запуск workflow имеет зелёный статус (✅), все шаги успешны (включая JaCoCo). |
| 5  | PR-проверки работают             | В PR отображается секция Checks с результатами CI (зелёный статус).                 |
| 6  | Обработка ошибок                 | Вы воспроизвели падение CI, исправили ошибку и получили зелёный статус.            |
| 7  | Observability (Debug в Actions)  | Вы знаете, как включить debug-логирование и перезапустить workflow через UI.        |
| 8  | GitHub Actions badge             | В README отображается badge со статусом последней сборки, клик ведёт на Actions.    |
| 9  | SonarLint установлен             | Плагин lint.SonarLint установлен в IntelliJ IDEA, скриншот подготовлен для платформы.   |