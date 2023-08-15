## TODO
- V0.0.7
  - [fastapi] allow for multiple services (alchemy mongodb, s3, upload folders)
  - [fastapi] websockets - need to monitor resolution of the following
    - https://github.com/tiangolo/fastapi/pull/3280
    - https://github.com/tiangolo/fastapi/pull/2640/files
    - https://github.com/tiangolo/fastapi/issues/2904
    - https://github.com/tiangolo/fastapi/issues/2639
    - https://github.com/tiangolo/fastapi/issues/2904
  - [fastapi] add task db and API
  - [fastapi] SSE
    - https://amittallapragada.github.io/docker/fastapi/python/2020/12/23/server-side-events.html
    - https://morioh.com/p/91e29c138c23
    - https://ably.com/topic/server-sent-events
    - https://medium.com/javarevisited/building-scalable-facebook-like-notification-using-server-sent-event-and-redis-9d0944dee618
    - https://dev.to/miketalbot/server-sent-events-are-still-not-production-ready-after-a-decade-a-lesson-for-me-a-warning-for-you-2gie
    - https://stackoverflow.com/questions/33471766/node-js-server-sent-events-with-load-balancer
    - http://blog.bayn.es/real-time-web-applications-with-server-sent-events-pt-1/

## DONE
- V0.0.7
  - 2022-01-21
    - [streamlit] add example on cascading dropdown, update streamlit version
  - 2021-12-02
    - [streamlit] add example on preserving state between page changes
  - 2021-11-10
    - [streamlit] improve on streamlit-antv
    - [chore] update documentation
  - 2021-11-05
    - [streamlit] refactor for multiple custom components
  - 2021-10-25
    - [streamlit] create sidebar (alpha) and also publishing to pypi
  - 2021-10-18
    - [streamlit] state & sessions, aggrid example
  - 2021-10-07
    - [viteuve] maintained in seperate repository
- V0.0.6
  - 2021-09-29
    - [streamlit] make graph component configurable. multiple selection or unselectable, etc.
    - [streamlit] app session metadata error on first load
  - 2021-09-29
    - [streamlit] add graph demo with input and output, state persistance, component test harness
    - [vitevue] update dependencies
  - 2021-09-23
    - [streamlit] add custom components demo, aggrid demo
  - 2021-09-15
    - [streamlit] add file loading / save and multiple apps functionality
    - [vitevue] update dependencies
  - 2021-09-12
    - [streamlit] add new data science tool streamlit and create examples
    - [vitevue] update dependencies
  - 2021-08-28
    - [vitevue] improve folder layout for deployment
  - 2021-08-25
    - [vitevue] add Ant Vision G6 (graph visuals) example
  - 2021-07-31
    - [vitevue] make all pages and routes customizable
    - [vitevue] rename utils.js to util.js and move file to folder with reusable components
    - [vitevue] make forbidden and notfound pages available in both public and secure routes
  - 2021-07-30
    - [vitevue] make layout customizable
    - [vitevue] update dependencies
- V0.0.5:
  - 2021-07-14
    - [fastapi] added ApiKey to favv
    - [fastapi] added refresh & oidc refresh
  - 2021-07-09
    - [favv] SAML, bearer token settings, done
  - 2021-07-05
    - [favv] add OAuth for social login
  - 2021-06-28
    - [vitevue] redo custom app loading, dynamic import was causing problems, fixed
  - 2021-06-24
    - [fastapi] implement OIDC, use 3000 as backend port instead (to sync with express)
  - 2021-06-21
    - [fastapi] keycloak in progress, update libraries
  - 2021-06-11
    - [fastapi] add graphql sample
  - 2021-06-08
    - [vitevue] dynamic chart update using slider
  - 2021-06-04
    - [favv] backend configurable websocket
  - 2021-06-02
    - [favv] implement frontend configurable websocket
  - 2021-06-01
    - [vitevue] improve multiple environment configs
      - Add demo on adding hook functions for login/logout 
      - [BREAKING] moved **src/[VITE_APPNAME]/.env.[MODE].js** properties to **.env.[MODE]**
      - [NREADINH] rename API_URL to VITE_API_URL
  - 2021-05-28
    - [vitevue] improve multiple environment configs
      - [BREAKING] remove **src/.env.vite.js** and use **.env.[MODE]** (see --mode in package.json)
      - [BREAKING] move  **src/.env.js** to **src/[VITE_APPNAME]/.env.[MODE].js**
      - [BREAKING] package.json need to add --mode
- V0.0.4:
  - 2021-05-14
    - vitevue DemoTableApi add filter to find function e.g. col=startDate&op=gte&val=10
- V0.0.4:
  - 2021-05-12
    - revisit python package management, update to version V0.0.5
  - 2021-05-11
    - API Table, also add notifications
  - 2021-05-10
    - add input to select columns to filter by (make it dynamic), make UI nicer, use localStorage
  - 2021-05-08
    - management of python package updates for framework and custom app
  - 2021-05-07
    - add https to fast API
  - 2021-05-06
    - Table 2 improvement... add copy csv, download csv
  - 2021-05-05
    - Table improvement... add And / Or text search condition and syntax highlight
  - 2021-05-02
    - Table improvement... add table preprocess function - sort: true, dropdownFilter: true, valerie filter (non API table)
  - 2021-04-30
    - V0.0.4: Non-API Table (filter, sort, page)
  - 2021-04-28
    - update demo chart 1 example where one of the charts is created on the fly and auto adjusted
  - 2021-04-24
    - implement object as store, and multiple properties (objects, primitive types), examples
  - 2021-04-23
   - clear all inputs on form, img auto adjust
  - 2021-04-22
    - V0.0.4: State Management (using pinia)
  - 2021-04-19
    - add file uplaod & json data multipart form API upload example
  - 2021-04-16
    - add slider with input box example
  - 2021-04-07
    - make fastapi .env handle various states (local, docker, etc. environments)
    - fix API_PORT bug (was stuck as 8000)
  - 2021-04-06
    - test and document network interaction between containers (docker-compose use case)
  - 2021-04-05
    - run with docker-compose
    - handle requirements.txt of custom app
    - include redis and huey
  - 2021-03-31
    - add website list frontend app
- V0.0.3
  - 2021-03-29
    - add HUEY_REDIS_CONNECTION and HUEY_TASK_QUEUES configurations
    - improve on task queue examples
  - 2021-03-27
    - wip add huey task queue
  - 2021-03-18
    - seperate requirements.txt for framework and custom app (but still use same venv)
    - add initial protected route for vitevue
    - vitevue configurable dev server port number
  - 2001-03-17
    - remove favv/.gitignore, not needed, custom code is implicit in now (folders suffix with **_app** for backend, suffix with **Web** for frontend)
    - add mongodb service
  - 2001-03-16
    - initial testing for dramatiq task queue
  - 2001-03-15
    - Add docker-compose.yml
    - Add Redis service
  - api version for (cascading muiti-select) (DemoMoreForm.vue)
- V0.0.2
  - 2001-03-09
    - FE: tidy up secure layout
    - FE: sub sub-combobox example
  - 2001-03-08
    - FE: redo custom (as production build was not possible)
    - BE: redo custom
    - Dockerfile testing
    - improve docs and structure, clean up code
- V0.0.1
  - 2021-03-07
    - BE: spawning process
    - BE: improve get_db...
    - ALL: save location of vite deploy
    - FE: make frontend configurable
    - BE: upload file/files, delete file, list files in folder, upload & get data, read from folder & get data, read from folder & download
    - BE: s3 - list buckets, list files, upload file to bucket, delete file from bucket, read from bucket
  - 2021-03-06
    - BE: configurable loading of endpoints