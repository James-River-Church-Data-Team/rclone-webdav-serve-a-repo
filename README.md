A Dockerfile that serves a git repo over WebDAV through rclone.

## Env vars
| Name   | Contents |
| ------ | -------- |
| `USER` | The username you'll give to authenticate to the WebDAV server |
| `PASS` | The password you'll give to authenticate to the WebDAV server |
| `REPO` | A .git link to clone. The server will host the repo's root    |
