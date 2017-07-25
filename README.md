# sshclient [![](https://images.microbadger.com/badges/version/jorgeandrada/ssh-client:latest.svg)](https://microbadger.com/images/jorgeandrada/ssh-client:latest "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/image/jorgeandrada/ssh-client:latest.svg)](https://microbadger.com/images/jorgeandrada/ssh-client:latest "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/commit/jorgeandrada/ssh-client:latest.svg)](https://microbadger.com/images/jorgeandrada/ssh-client:latest "Get your own commit badge on microbadger.com")

**SSH client with ansi2html**

SSH client with ansi2html to get the output of the commands in html. (debian-slim)

<a href='https://ko-fi.com/A417UXC' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi2.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

## Example for get html report

```shell
docker run -i jorgeandrada/ssh-client bash -c "ls -lh | ansi2html" > output.html
docker exec -i example sh -c 'command_to_execute | ansi2html' > output.html
```
