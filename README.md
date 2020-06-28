# Movies-Review
## Setup Guide (Use command line)
1. Move to Movies-Review directory 
2. mkvirtualenv Movies-Review
3. setprojectdir
4. pip install flask
5. pip install SQLAlchemy
6. pip install FlaskSQLAlchemy
7. pip install psycopg2

## Run Guide (Use command line)
1. Move to Movies-Review directory
2. Start cái virtual environment, gõ workon Movies-Review. (Để stop, gõ deactivate)
3. set FLASK_APP=app.py (cái này hình như chỉ phải run first time)
4. set FLASK_ENV=development (cái này để mỗi khi mình modify any file thì website nó sẽ auto-update, ko phải run lại)
5. flask run (Bắt buộc phải chạy cái này everytime run app)
6. Rồi copy cái URL http://127.0.0.1:5000/ lên browser và chạy :+1: