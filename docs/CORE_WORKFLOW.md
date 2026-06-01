# Askutty Core Workflow

Askutty starts small and grows safely.

## Golden Flow

```text
doctor -> backup -> patch -> test -> approval -> deploy -> rollback ready
```

## Small Capacity Version

The first version does not control everything.

It only defines the safe working process:

1. Understand the task.
2. Prepare a plan.
3. Create a backup point.
4. Prepare a patch.
5. Ask Aslam approval.
6. Apply only after approval.
7. Test the result.
8. Keep rollback ready.

## Rule

No risky action is automatic.
