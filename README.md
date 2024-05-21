proxies:
- name: jayenx5
  type: vmess
  server: 104.18.62.203
  port: 443
  uuid: 5bcef1a9-9d0b-4dde-b8fc-6b8524bb20d2
  alterId: 0
  cipher: auto
  udp: true
  xudp: false
  global-padding: false
  authenticated-length: false
  skip-cert-verify: true
  tls: true
  servername: sg-datacamp1.server-vpn.cloud
  network: ws
  ws-opts:
    path: "/vmess"
    headers:
      Host: sg-datacamp1.server-vpn.cloud
