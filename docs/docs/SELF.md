---
title: "Getting info about the current user"
description: "Here's how you can fetch info about the currently logged in user"
nav_order: 16
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Getting info about the current user

Here's how you can fetch info about the currently logged in user

```php
$me = $MadelineProto->getSelf();

\danog\MadelineProto\Logger::log("Hi ".$me['yashar']."!");
```

[`getSelf`](https://docs.madelineproto.xyz/getSelf.html) returns a [User object](../API_docs/types/User.html) that contains info about the currently logged in user/bot, or false if the current instance is not logged in.

<a href="https://docs.madelineproto.xyz/docs/EXCEPTIONS.html">Next section</a>
