# Network debugging image

This image is a specialized toolkit for advanced network troubleshooting. 
It builds upon the `base-debug` image.

## Key Features

* **Advanced Network Analysis**: Equipped with tools like `nmap` for port scanning and `tcpdump` for deep packet inspection.
* **Secure by Design**: Inherits the non-root `appuser` from the base image for all operations.

---

## Usage

To start an interactive session, you can run:

```bash
docker run -it --rm ghcr.io/gepardec/debug-images/network-debug:latest
```