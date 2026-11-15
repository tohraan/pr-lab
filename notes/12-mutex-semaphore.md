# Mutex vs semaphore

A mutex guards one critical section and has an owner; a semaphore counts permits and any thread may signal it. Use a mutex for exclusion, a semaphore for resource pools.
