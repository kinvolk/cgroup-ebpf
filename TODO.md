- Create ebpf program
- Write k8s DaemonSet
    - Connect to k8s/kubelet API
    - Get list of pods + notification for pod creation
    - Install ebpf program on each container
- Write prometheus plugin
    - Read ebpf map
