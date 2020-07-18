Run your application using the command `node app.js`

## Postman calls

1. To make sure your application is working fine and it creates the Genesis Block you can use POSTMAN to request the Genesis block:
    ![Request: http://localhost:8000/block/0 ](https://user-images.githubusercontent.com/10187576/87860696-85840100-c90d-11ea-9dc2-81c22c3387ac.jpg)
2. Make your first request of ownership sending your wallet address:
    ![Request: http://localhost:8000/requestValidation ](https://user-images.githubusercontent.com/10187576/87860743-ed3a4c00-c90d-11ea-8ea4-9426950ede2b.jpg)

3. Submit your Star
     ![Request: http://localhost:8000/submitstar](https://user-images.githubusercontent.com/10187576/87860746-f1ff0000-c90d-11ea-949e-c52c8ec936b2.jpg)
4. Retrieve Stars owned by me
    ![Request: http://localhost:8000/blocks/<WALLET_ADDRESS>](https://user-images.githubusercontent.com/10187576/87860744-ef9ca600-c90d-11ea-8965-bfc09d08c1c0.jpg)