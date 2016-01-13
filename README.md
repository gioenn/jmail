### JMail - a simple GMail email sender in Java

#### How it works

```
GMailSender sender = new GMailSender("<your gmail address>", "<your gmail password>");
sender.sendMail("<subject>", <html body>, <sender display name>, "<comma separated recipients>");
```

#### Example Usage

```
GMailSender sender = new GMailSender("mike@gmail.com", "bobby");
sender.sendMail("I know", "Who killed Laura Palmer", "Mike", "cooper@fbi.com,drjacoby@aol.com");
```
