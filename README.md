# DynamicSite_BS4
# DocuSketch_FastAPI_Unit_Tests_and_Logging
настройка виртуального окружения: 
python -m venv venv  
активация виртуального окружения: source venv/bin/activate для mac, venv\Scripts\activate.bat для Windows  
установка FastAPI: pip install fastapi[all]  
создаем приложение main.py, прописываем:  
- from fastapi import FastAPI
- app = FastAPI()
- @app.get('/')
  
  def hello():
  
    return 'Hello world'
  
запускаем для проверки: uvicorn main:app -- reload  
создаем базу данных из 3 item и endpoint `/items/{item_id}`  
для unit tests создаем папку tests, загружаем pip install pytest  
переносим зависимости в файл: pip freeze > requirements.txt  
устанавливаем pip install requests  

    

  


  
