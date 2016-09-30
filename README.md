# docker-ipmitool

## Build
```
docker build -t tsunokawa/ipmitool .
```

## RUN
docker run -it --rm tsunokawa/ipmitool /bin/bash
```

---

## IPMI(v1)
```
ipmitool -I lan -H 10.0.0.0 -U root isol activate
```

## IPMI(v2)
```
ipmitool -I lanplus -H 10.0.0.0 -U root sol activate
```

