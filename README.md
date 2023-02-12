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


# data
all versions of customer chats data ae stored here: [ML shared folder](\\ats-store01\BusinessIntelligence\ML\Annotation-tool\data).

Copy those data, paste them under data folder and **never** commit to git.




