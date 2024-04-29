Установите TypeScript в ваш проект, если еще не сделали:

npm install --save-dev typescript

Создайте файл tsconfig.json в корне вашего проекта с базовой конфигурацией:

{
  "compilerOptions": {
  
    "target": "es6",
    
    "module": "commonjs",
    
    "outDir": "dist",
    
    "strict": true
    
  }
  
}


Скомпилируйте ваш TypeScript-файл в JavaScript:

npx tsc

1-Избавиться от unknown, описать актуальный интерфейс:
![image](https://github.com/Yuriy228822/My-homework/assets/160457523/5c29de6f-689f-432e-9eaf-f67720eee4c4)


Задача 2
Даны несколько заготовленных типов. При помощи них "собран" тип Student. Соберите типы Teacher и Director из имеющихся типов. Для проверки используйте переменные в самом низу. Можно определять новые типы.

![image](https://github.com/Yuriy228822/My-homework/assets/160457523/1f138dc0-62a7-46fb-936e-bdde78404cbc)


Задача 3
Использя generic-параметры, типизируйте функции, чтобы не было ошибок компиляции. Возможно, потребуется дописать типы в теле функции

![image](https://github.com/Yuriy228822/My-homework/assets/160457523/8da961ab-4852-4321-9702-9d60b6a8ab53)



Задача 4
Соберите типы Teacher и Director из имеющихся типов, используя Partial, Pick, Omit, Exclude и при необходимости другие Utility Types.

![image](https://github.com/Yuriy228822/My-homework/assets/160457523/f6305320-fcea-4050-addc-739194dfed26)
![image](https://github.com/Yuriy228822/My-homework/assets/160457523/b7e72cdb-8c97-4b0d-82bb-2308a1af8cbf)

Задача 5
![image](https://github.com/Yuriy228822/My-homework/assets/160457523/65b3c181-8ea5-43a4-8281-7ed5916d1f9a)
![image](https://github.com/Yuriy228822/My-homework/assets/160457523/3de97d1d-0936-4a93-a942-7c7ba1f8ea3b)





