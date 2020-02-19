#### StatefulSet with Headless Service

Before starting out on StatefulSet review [Prerequisite](../../README.md) before getting started with StatefulSet:

If you have followed the previous steps, you should be good to go.

Next: Apply the desired state using `kubectl app -f filepath` in the following order.
- Secrets/Config
- StatefulSet
- Headless Service
- Ingress Service
- Ingress 

**Note**: To simulate DNS resolution locally, edit `/etc/host` file and map the `Node IP` to `appscode.example.com`.