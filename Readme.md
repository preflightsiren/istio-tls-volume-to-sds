# istio-sds

This project is a test-repo to help explore the migration path from using volume mounted TLS certificates, to Secret Discovery Service (SDS).

Tasks:
- [x] Create kind cluster
- [x] Install Istio
- [x] Install cert-manager
- [x] Install httpbin as a workload
- [x] Deploy Gateway's and VirtualService'
- [x] Test connectivity to http
- [ ] Enable SDS
- [ ] Deploy new certificate / secrets
- [ ] Make sure it wires up successfully
