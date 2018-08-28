# Local experiences

## Install
```javascript
// dependencies
npm i
// db
npm run init
// parameters file
cp parameters.json.example parameters.json
```

## Dependencies
- PostgreSQL
- Redis (>=3.0.0)

## Developer mode tests
The first time, you will need to config the database:
```javascript
./config/db.sh local_experiences_test
```

Then, you can run:
```javascript
npm run dev-test
```
