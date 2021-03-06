# D3-driven AngularJS treemap app

See the treemap in action: [flekschas.github.io/treemap](https://flekschas.github.io/treemap/)

## Requirements

- git
- NodeJS
- NPM
- Bower
- Neo4J

## Install

1. Clone repository

   ```
   git clone https://github.com/flekschas/treemap && cd treemap
   ```

2. Download and install dependencies

   ```
   npm install && bower install
   ```

3. Setup local test data

    **Test data**:

    Open [src/app/treeMap/controller.js](src/app/treeMap/controller.js) and make sure that the lines between

    ```
    /* ---------------------------- [START: STATIC] --------------------------- */
    ...
    /* ---------------------------- [END: STATIC] --------------------------- */
    ```
    
    are uncommented, while the lines between

    ```
    /* ---------------------------- [START: LIVE] --------------------------- */
    ...
    /* ---------------------------- [END: LIVE] --------------------------- */
    ```
    
    are commented out.

    **Live data**:

    Do the exact opposite as for **test data**. Make sure that Neo4J is running!


## Start local test service and run app

```
gulp --open
```
