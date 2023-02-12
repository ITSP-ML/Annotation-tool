# Annotation-tool
Annotation tool for any NLP project

# run the front end:
cd src/
npm run dev

# run backend
$ cd src/backend/
python manage.py runserver

# run celery for upload and export of files
$ celery --app=config worker --loglevel=INFO --concurrency=1 --pool=solo

