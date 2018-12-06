# qemu-guest-agent

see [qga](https://wiki.qemu.org/Features/GuestAgent)

### guest-info

```
> virsh qemu-agent-command domain --cmd '{"execute":"guest-info"}'
```

### file write

写的内容使用base64编码
```
> virsh qemu-agent-command domain --cmd '{"execute":"guest-file-open",arguments":{"path":"/tmp/test","mode":"w+"}}'
{"return":1004}

> virsh qemu-agent-command domain --cmd '{"execute":"guest-file-write","arguments":{"handle":1004,"buf-b64":"aGVsbG8gd29ybGQhCg=="}}'
{"return":{"count":13,"eof":false}}

> virsh qemu-agent-command domain --cmd '{"execute":"guest-file-close","arguments":{"handle":1004}}'
{"return":{}}
```
