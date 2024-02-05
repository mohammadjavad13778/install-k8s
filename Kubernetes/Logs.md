# Kubelet

```bash
kubelet.service - kubelet: The Kubernetes Node Agent
     Loaded: loaded (/lib/systemd/system/kubelet.service; enabled; vendor preset: enabled)
    Drop-In: /usr/lib/systemd/system/kubelet.service.d
             └─10-kubeadm.conf
     Active: inactive (dead) (Result: exit-code) since Sat 2024-02-03 19:09:12 UTC; 31s ago
       Docs: https://kubernetes.io/docs/
    Process: 5119 ExecStart=/usr/bin/kubelet $KUBELET_KUBECONFIG_ARGS $KUBELET_CONFIG_ARGS $KUBELET_KUBEADM_ARGS $KUBELE>
   Main PID: 5119 (code=exited, status=1/FAILURE)
        CPU: 55ms

Feb 03 19:09:03 master-node systemd[1]: kubelet.service: Main process exited, code=exited, status=1/FAILURE
Feb 03 19:09:03 master-node systemd[1]: kubelet.service: Failed with result 'exit-code'.
Feb 03 19:09:12 master-node systemd[1]: Stopped kubelet: The Kubernetes Node Agent.
```

## Journalctl 

