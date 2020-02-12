# gfwlist4phicomm
Update the gfwlist for an unofficial Phicomm K3 ROM.

Working on this [Phicomm K3 ROM](http://www.right.com.cn/forum/thread-259012-1-1.html).
### Usage

Upload gfwlist4phicomm.sh to your Phicomm router:

```
scp gfwlist4phicomm.sh admin@p.to:/root
```

SSH to your Phicomm router:

```
ssh admin@p.to
```

**Attention:** This script needs `sed`, `base64` and `curl`. However, `base64` may not be included into the unofficial ROM by default, in which case you should install it first:

```
opkg update && opkg install coreutils-base64
```

Run gfwlist4phicomm.sh:

```
sh /root/gfwlist4phicomm.sh
```

Done!
