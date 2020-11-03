## Base
```
.
├── config                  # App configuration files
│   ├── sequalize.json        # Sequalize config
│   ├── serviceOne.json       # ServiceOne config
│   └── ...                 # Other configurations
├── routes                  
│   ├── controllers         # Request managers
│   ├── middlewares         # Request middlewares
│   └── routes.js           # Define routes and middlewares here
├── services                # External services implementation   
│   ├── serviceOne
│   └── serviceTwo
│   └── ...                 # Other services
├── db                      # Data access stuff  (Sequalize mostly)
│   ├── models              # Models
│   ├── migrations          # Migrations
│   ├── seeds               # Seeds
│   └── index.js            # Sequalize instantiation
├── core                    # Business logic implementation
│   ├── accounts.js         
│   ├── sales.js            
│   ├── comments.js              
│   └── ...                 # Other business logic implementations
├── utils                   # Util libs (formats, validation, etc)
├── tests                   # Testing
├── scripts                 # Standalone scripts for dev uses
├── pm2.js                  # pm2 init
├── shipitfile.js           # deployment automation file
├── package.json           
├── README.md         
└── app.js                  # App starting point

```

## Advance

```
.
|-- config
|   |-- components
|   |   |-- common.js
|   |   |-- logger.js
|   |   |-- rabbitmq.js
|   |   |-- redis.js
|   |   |-- server.js
|   |   `-- twitter.js
|   |-- index.js
|   |-- social-preprocessor-worker.js
|   |-- twitter-stream-worker.js
|   `-- web.js
|-- models
|   |-- redis
|   |   |-- index.js
|   |   `-- redis.js
|   |-- tortoise
|   |   |-- index.js
|   |   `-- tortoise.js
|   `-- twitter
|       |-- index.js
|       `-- twitter.js
|-- scripts
|-- test
|   `-- setup.js
|-- web
|   |-- middleware
|   |   |-- index.js
|   |   `-- parseQuery.js
|   |-- router
|   |   |-- api
|   |   |   |-- tweets
|   |   |   |   |-- get.js
|   |   |   |   |-- get.spec.js
|   |   |   |   `-- index.js
|   |   |   `-- index.js
|   |   `-- index.js
|   |-- index.js
|   `-- server.js
|-- worker
|   |-- social-preprocessor
|   |   |-- index.js
|   |   `-- worker.js
|   `-- twitter-stream
|       |-- index.js
|       `-- worker.js
|-- index.js
`-- package.json

```
