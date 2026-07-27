FROM redis:7.4.10

COPY ./dump.rdb /data/dump.rdb
ENTRYPOINT ["redis-server", "--dbfilename", "dump.rdb", "--dir", "/data"]