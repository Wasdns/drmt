The commands in `run_experiments.sh`:

### test1 switch_combined

drmt_ipc_1 switch_combined 

```
/usr/bin/time python -u drmt.py switch_combined large_hw      drmt_latencies 10 > test//drmt_ipc_1_switch_combined.txt
```

drmt_ipc_2 switch_combined 

```
/usr/bin/time python -u drmt.py switch_combined large_hw_ipc2 drmt_latencies 10 > test//drmt_ipc_2_switch_combined.txt
```

prmt_fine switch_combined 

```
/usr/bin/time python -u prmt.py switch_combined large_hw      prmt_latencies fine> test//prmt_fine_switch_combined.txt
```

prmt_coarse switch_combined

```
/usr/bin/time python -u prmt.py switch_combined large_hw      prmt_latencies coarse> test//prmt_coarse_switch_combined.txt
```

### test2 switch_combined_subset

drmt_ipc_1 switch_combined_subset

```
/usr/bin/time python -u drmt.py switch_combined_subset large_hw      drmt_latencies 10 > test//drmt_ipc_1_switch_combined_subset.txt
```

drmt_ipc_2 switch_combined_subset

```
/usr/bin/time python -u drmt.py switch_combined_subset large_hw_ipc2 drmt_latencies 10 > test//drmt_ipc_2_switch_combined_subset.txt
```

prmt_fine switch_combined_subset

```
/usr/bin/time python -u prmt.py switch_combined_subset large_hw      prmt_latencies fine> test//prmt_fine_switch_combined_subset.txt
```

prmt_coarse switch_combined_subset

```
/usr/bin/time python -u prmt.py switch_combined_subset large_hw      prmt_latencies coarse> test//prmt_coarse_switch_combined_subset.txt
```

### test3 switch_egress

drmt_ipc_1 switch_egress

```
/usr/bin/time python -u drmt.py switch_egress large_hw      drmt_latencies 10 > test//drmt_ipc_1_switch_egress.txt
```

drmt_ipc_2 switch_egress

```
/usr/bin/time python -u drmt.py switch_egress large_hw_ipc2 drmt_latencies 10 > test//drmt_ipc_2_switch_egress.txt
```

prmt_fine switch_egress

```
/usr/bin/time python -u prmt.py switch_egress large_hw      prmt_latencies fine> test//prmt_fine_switch_egress.txt
```

prmt_coarse switch_egress

```
/usr/bin/time python -u prmt.py switch_egress large_hw      prmt_latencies coarse> test//prmt_coarse_switch_egress.txt
```

### test4 switch_egress_subset

drmt_ipc_1 switch_egress_subset

```
/usr/bin/time python -u drmt.py switch_egress_subset large_hw      drmt_latencies 10 > test//drmt_ipc_1_switch_egress_subset.txt
```

drmt_ipc_2 switch_egress_subset

```
/usr/bin/time python -u drmt.py switch_egress_subset large_hw_ipc2 drmt_latencies 10 > test//drmt_ipc_2_switch_egress_subset.txt
```

prmt_fine switch_egress_subset

```
/usr/bin/time python -u prmt.py switch_egress_subset large_hw      prmt_latencies fine> test//prmt_fine_switch_egress_subset.txt
```

prmt_coarse switch_egress_subset

```
/usr/bin/time python -u prmt.py switch_egress_subset large_hw      prmt_latencies coarse> test//prmt_coarse_switch_egress_subset.txt
```

### test5 switch_ingress

drmt_ipc_1 switch_ingress

```
/usr/bin/time python -u drmt.py switch_ingress large_hw      drmt_latencies 10 > test//drmt_ipc_1_switch_ingress.txt
```

drmt_ipc_2 switch_ingress

```
/usr/bin/time python -u drmt.py switch_ingress large_hw_ipc2 drmt_latencies 10 > test//drmt_ipc_2_switch_ingress.txt
```

prmt_fine switch_ingress

```
/usr/bin/time python -u prmt.py switch_ingress large_hw      prmt_latencies fine> test//prmt_fine_switch_ingress.txt
```

prmt_coarse switch_ingress

```
/usr/bin/time python -u prmt.py switch_ingress large_hw      prmt_latencies coarse> test//prmt_coarse_switch_ingress.txt
```

### test6 switch_ingress_subset

drmt_ipc_1 switch_ingress_subset

```
/usr/bin/time python -u drmt.py switch_ingress_subset large_hw      drmt_latencies 10 > test//drmt_ipc_1_switch_ingress_subset.txt
```

drmt_ipc_2 switch_ingress_subset

```
/usr/bin/time python -u drmt.py switch_ingress_subset large_hw_ipc2 drmt_latencies 10 > test//drmt_ipc_2_switch_ingress_subset.txt
```

prmt_fine switch_ingress_subset

```
/usr/bin/time python -u prmt.py switch_ingress_subset large_hw      prmt_latencies fine> test//prmt_fine_switch_ingress_subset.txt
```

prmt_coarse switch_ingress_subset

```
/usr/bin/time python -u prmt.py switch_ingress_subset large_hw      prmt_latencies coarse> test//prmt_coarse_switch_ingress_subset.txt
```