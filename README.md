# VR2G-Evanescent

This is the Delivery component developed within the VRTogether consortium. Currently this repository hosts the binaries of the Motion Spell SFU called Evanescent.

This is not currently open source (we are working on that), but the binaries are freely available. For example for use with the VR2Gather orchestrator <https://github.com/cwi-dis/vr2gather-orchestrator-v2>.

## Usage

Usage: ```LD_LIBRARY_PATH=$DIR $DIR/evanescent.exe [--tls] [--port port_number]```

If you use TLS don't forget to generate your own certificates for each server instance: https://www.digicert.com/csr-ssl-installation/apache-openssl.htm.

When deleting resources you can use a wildcard:
```curl -X DELETE http://127.0.0.1:9000/aaaa*bbbb```

