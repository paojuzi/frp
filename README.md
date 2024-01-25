# frp

# 1、start frps in the service device

./frps -c ./frps.toml

# you can also run it in the background process

nohup ./frps -c ./frps.toml &

# 2、start frpc in the client device

./frpc -c ./frpc.toml

# you can also run it in the background process

nohup ./frpc -c ./frpc.toml &