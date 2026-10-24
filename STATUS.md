# Implementation Status

A scenario counts as VERIFIED only if I reproduced it, diagnosed it myself,
fixed it, and committed evidence in /evidence/<scenario>/.

| ID  | Scenario                  | Reproduced | Diagnosed by me | Fixed | Verified (evidence) |
|-----|---------------------------|:----------:|:---------------:|:-----:|---------------------|
| S01 | Security group vs NACL    | no | no | no | - |
| S02 | Missing route / IGW       | no | no | no | - |
| S03 | IAM AccessDenied          | no | no | no | - |
| S04 | systemd service failing   | no | no | no | - |
| S05 | Disk full / inode exhaust | no | no | no | - |

## Planned (not started)
DNS resolution failure, S3 bucket policy conflict, TLS certificate mismatch,
RDS connection failure, Lambda permission error (optional).
Not planned: NAT Gateway scenario (cost), unless done with a NAT instance later.
