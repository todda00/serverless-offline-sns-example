## serverless-offline-sns-example

Simply run
```bash
npm install
npm start
```

And then go to http://localhost:3000/ping to trigger the event, you should see "pong" appear in the console.

To see the issue with webpack, open a new command line (while serverless offline is still running) and run:

```bash
serverless invoke local -f ping
```

You will see the trace error in the terminal where serverless offline is running.
