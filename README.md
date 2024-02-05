## Build a Node.js app with Express

    ```bash
    npx express-generator   # to create the project
    ```

## Build docker image

    ```bash
    docker build -t express-server .
    ```

## Run the app

    ```bash
    docker run -p 3123:3000 express-server
    ```
