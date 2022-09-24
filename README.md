# azure-service-bus
 Interacting with Service Bus queue and Service Bus topic utilizing the SDK.

 Notes for package.json:
  Utilizing a dependency called `npm‑run‑all`, and this enables us to run multiple scripts simultaneously. And if you look under the topic script, we're saying that we want to run in parallel everything that starts with the name topic and colon, and what we're going to do here is we're going to run our publisher, which actually pushes out messages, and then two of our subscribers, one named odd and one named even, simultaneously so that we can see how each of them are responding to the messages that are being published.
