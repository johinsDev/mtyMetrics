#My Metrics DB

##Usage

```js
  const setupDatabase = require('myMetricsDB');

  setupDatabase(config).then(db =>{
    const { Agent, Metric } = db;
  }).catch(err => console.error(err));
```