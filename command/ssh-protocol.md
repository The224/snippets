# SSH Protocol

## File Transfer

The `scp` command will perform a file transfer with ssh protocol. 

```text
scp <source> <destination>
```

```text
scp /path/to/file user@domain:/path/to/destination
```

## Port Forwarding tunnel

```text
ssh -L 8080:localhost:8080 user@domain.com
```









