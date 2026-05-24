ALL TASKS MUST FOLLOW THIS LOOP:

1. Parse user intent
2. Classify task type
3. Select workflow
4. Generate plan (Planner Agent)
5. Build minimal context
6. Execute changes (Coder Agent)
7. Reconcile state (policy-based validation)
8. Commit to Git

NO STEP CAN BE SKIPPED.