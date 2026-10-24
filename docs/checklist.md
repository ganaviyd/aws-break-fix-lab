# Troubleshooting Checklist

1. **Reproduce**: Can I trigger the symptom myself? Capture the exact error and time.
2. **Scope**: One user or all? One resource or many? Since when? What changed?
3. **Check logs and state**: Service logs, system logs, CloudTrail, and the current
   config of every resource on the path (SG, NACL, route table, IAM, DNS).
4. **Hypothesize**: Write 2-3 candidate causes, ranked by likelihood and cheapness to test.
5. **Test**: Change or inspect ONE thing at a time. Record the command and the result.
6. **Verify**: Prove the symptom is gone using the same check that first showed it,
   and confirm nothing else broke.
