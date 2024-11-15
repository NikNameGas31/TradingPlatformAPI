# tradingplatformapi
-Перед запуском скачать библиотеки:
`httpx
SQLalchemy
FastAPI
Uvicorn
`

-Чтобы запустить сервер в терминал прописать
`
uvicorn fastapi-shop.main:app --reload
`


-Чтобы создать новый продукт в терминал прописать(пример):
`
Invoke-WebRequest -Uri "http://127.0.0.1:8000/products/" -Method POST -ContentType "application/json" -Body '{"name": "Logitech G102","description": "Gaming Mouse","price": "20.0","category_id":1}'
`


-Чтобы создать новую категорию в терминал прописать(пример):
`
Invoke-WebRequest -Uri "http://127.0.0.1:8000/categories/" -Method POST -ContentType "application/json" -Body '{"name": "Gaming Mouses"}'
`


-Чтобы удалить продукт в терминал прописать(пример):
`
Invoke-WebRequest -Uri "http://127.0.0.1:8000/products/1/" -Method DELETE
`


-Чтобы удалить категорию в терминал прописать(пример):
`
Invoke-WebRequest -Uri "http://127.0.0.1:8000/categories/1/" -Method DELETE
`
