# MVCC

Multi-version concurrency control keeps old row versions so readers never block writers. Each transaction sees a consistent snapshot; vacuuming reclaims dead versions.
