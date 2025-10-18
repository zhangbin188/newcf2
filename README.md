### 部署成功
<img width="1312" height="750" alt="image" src="https://github.com/user-attachments/assets/17ab8bc8-9bc3-44d8-8f44-bc5906ed7347" />



###  配套工具

| 类型 | 描述 | 链接 |
| :--- | :--- | :--- |
|  **生成节点** | 一键生成所有优选 IP/域名的 VLESS 链接 | [https://cfy.jhb.ovh/](https://cfy.jhb.ovh/) |


###  部署
混肴前增加
const authToken = '6f52a2ef-2a34-4937-b26f-9a5883092d66'; //不可以重复赋值
let authToken = '6f52a2ef-2a34-4937-b26f-9a5883092d66'; //可以在后续中给与重复赋值
	
| 变量名 | 值 | 说明 |
| :--- | :--- | :--- |
| `u` | `你的 UUID` | **必需**。 |
| `p` | `proxyip` | **可选**但强烈推荐，填写一个稳定的用来访问 Cloudflare IP 可以用 ProxyIP.cmliussss.net CM提供的公益项目 在次感谢。 |
| `s` | `你的SOCKS5地址` | **可选**。用于将所有出站流量通过 SOCKS5 代理转发，格式为 `user:pass@host:port` 或 `host:port`。 |
| `d` | `你的订阅地址` | **可选**。不填就是/你的uuid

###  致谢

  * 本项目基于 [zizifn/edgetunnel](https://github.com/zizifn/edgetunnel) 修改，感谢原作者的贡献。

