# Stress test

## T5 on RTX 3090 Ti

Rate of 5 users per second, total requests up to 50 users for 30 seconds,

```bash
locust -f t5.py -P 7001 -H http://localhost:7088 -r 5 -u 50 -t 30
```

![alt text](graph-t5.png)

Full report at [report-t5.html](report-t5.html).