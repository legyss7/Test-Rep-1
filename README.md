
git clone https://github.com/legyss7/Test-Rep-1.git

cd Test-Rep-1/

## Показать связи
git remote -v

## Удалить связи
git remote remove origin

## Привязять локальный репозиторий
git remote add origin https://github.com/legyss7/Test-Rep-2.git

## Сохранить на удаленный репозитой ветку main
git push -u origin main

## Добавили связь с именем переменной source
git remote add source https://github.com/legyss7/Test-Rep-1.git




git push -u origin main
git push -u source main



git fetch --all

она показывает изменения относительно последнего коммита ^main
git log origin/main ^main