#### Simple chat Based on simplified Blockchain with persistent storage 

##### Clean chain:
```bash
rm ./blockchain-js-chat$/blockchain.js
```

##### Run:
```javascript
node ./blockchain.js
```

##### Navigate:
In Browser: /path/to/blockchain-js-chat/cli.html


##### blockchain.data - sample structure:

```javascript

[
    {
        "index": 0,
        "parentHash": "0",
        "ownHash": "4736da8abed4f7db7156afc3676993258165344c2e6337db8a921823784c1378",
        "timestamp": 1509904949880,
        "data": "{\"date\":\"2017-11-05T18:02:29.880Z\",\"author\":\"#Blockchain\",\"msg\":\"init message\"}"
    },
    {
        "index": 1,
        "parentHash": "4736da8abed4f7db7156afc3676993258165344c2e6337db8a921823784c1378",
        "ownHash": "cc79ab9542a6d81f3eea938bb88ac458ac9899c18e962a5e8a4f1fc9620e1518",
        "timestamp": 1509904961577,
        "data": "{\"date\":\"2017-11-05T18:02:41.571Z\",\"author\":\"D4N05S5SGM8vexcSd073sWA1KJ4-Wo-LcIVs65pI\",\"msg\":\"Hello world\"}"
    },
    {
        "index": 2,
        "parentHash": "cc79ab9542a6d81f3eea938bb88ac458ac9899c18e962a5e8a4f1fc9620e1518",
        "ownHash": "2482c48822ec09a79e89aff73a9dbe6efdf52bafa9117402c9c908eeef893d1a",
        "timestamp": 1509904973192,
        "data": "{\"date\":\"2017-11-05T18:02:53.191Z\",\"author\":\"D4N05S5SGM8vexcSd073sWA1KJ4-Wo-LcIVs65pI\",\"msg\":\"Messages from Blockchain\"}"
    }
]

```

