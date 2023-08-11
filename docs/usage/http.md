---
sidebar_position: 1
---

# Simple HTTP

The HTTP API is the easiest way to use AvatarGenerator and it can be use in many different contexts.

---

## How to use it

Use the following url and replace `[user-id]` by the id of your account that you can find on your [account](http://localhost:3000/profile).

```md title="Simple url without any seed"
http://localhost:8080/avatar/svg?u=[user-id]
```

:::tip Allowed Domains

By default your `[user-id]` can be used from any domain. If you want to restrict it you can manage allowed domains on your [profile page](http://localhost:3000/profile).

:::

---

### How to generate other avatars

To generate as many avatar that you want you can add a seed in the url you use. Use the following url and replace `[seed]` by any word, sentense, random string you want.

```md title="Simple url"
http://localhost:8080/avatar/svg?u=[user-id]&s=[seed]
```

### Some examples
