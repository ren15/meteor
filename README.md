# meteor

Computing resources provisioned and acquired Just-In-Time when computing is needed.

Maybe implement it using firecracker.

Ideal work case:

```
lazydag2            ->  call API  ->  meteor create microvm  -> recycle
(generate DAG                          
and State Machine)                     

control plane                          data plane
small VM                               A lot of vms on
                                       different metals
```
