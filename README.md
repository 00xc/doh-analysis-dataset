# doh-analysis-dataset #

This repository includes the labeled dataset used for my Master's Thesis, [DNS over HTTPS Traffic Analysis and Detection](http://openaccess.uoc.edu/webapps/o2/handle/10609/119946).

Columns:
1. Number of requests
2. Request size skewness
3. Response size skewness
4. Request duration skewness
5. Response duration skewness
6. Request time-delta skewness
7. ALPN
8. Connection duration
9. Packet count, server to client
10. Mean packet throughput (packets/second), client to server
11. Bytes per packet, client to server
12. Bytes per packet, server to client
13. Output label (0=HTTP, 1=DoH)
