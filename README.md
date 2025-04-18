(venv) PS D:\New folder\Smart Agriculture (CSE471)\Smart-Agriculture> # In your project directory
>> Remove-Item -Recurse -Force .\venv
>> python -m venv venv
>> .\venv\Scripts\Activate
>> (venv) PS D:\New folder\Smart Agriculture (CSE471)\Smart-Agriculture> pip install -r requirements.txt
>>
(venv) PS D:\New folder\Smart Agriculture (CSE471)\Smart-Agriculture\market> python manage.py migrate
>> python manage.py runserver
