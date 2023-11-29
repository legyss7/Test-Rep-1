
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

## Добавили связь
git remote add source https://github.com/legyss7/Test-Rep-1.git


## -u говорит какой ветки и какой репозиторий push 
## далее можно исользовать просто push
