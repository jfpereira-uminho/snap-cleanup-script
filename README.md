# Snap CleanUp Script

## Why This Script is Needed in VMs?

Snap cleanup is crucial for limited resource environments like virtual machines (VMs) because disk space and system performance are often constrained.

## Key Benefits:

 **Frees Up Disk Space**

- Snap retains old, disabled versions of applications, consuming unnecessary storage.
- Removing them prevents disk bloat, which is critical in VMs with small storage allocations.

 **Clears Unused Cache**

- Snap stores temporary files in /var/lib/snapd/cache/, which accumulates over time.
- Cleaning it ensures efficient space utilization and prevents waste.

## Conclusion

Running this script regularly helps keep your VM efficient and free from unnecessary Snap clutter.

## Run
Navigate to the script's directory and execute:
    ```bash
    $ sudo ./snap_cleanup.sh
   ```
 
