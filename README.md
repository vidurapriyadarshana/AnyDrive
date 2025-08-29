# AnyDrive

npm install express googleapis mongoose express-session
npm install nodemon --save-dev


express → backend framework

googleapis → Google OAuth & Drive API

mongoose → MongoDB ODM (you can replace with PostgreSQL if needed)

express-session → session management for logged-in users

nodemon → automatically restart server during development

mkdir src
mkdir src\routes
mkdir src\services
mkdir src\models
mkdir src\config
 
New-Item -ItemType File src\index.js
New-Item -ItemType File src\routes\auth.js
New-Item -ItemType File src\routes\drive.js
New-Item -ItemType File src\services\googleAuth.js
New-Item -ItemType File src\services\driveService.js
New-Item -ItemType File src\models\user.js
New-Item -ItemType File src\config\db.js
New-Item -ItemType File credentials.json
