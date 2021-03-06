# Provision an Azure Virtual Machine with OS and Data Disks as Managed Disks  

## Example: Virtual Machine with Data Disks  
This example provisions a Virtual Machine with 2 Data Disks and an OS Disk all of which are Managed Disks.

### Notes:
- The files involved in this example are split out to make it easier to read, however all of the resources could be combined into a single file if needed.

### Variables:
- `prefix` (Required): The Prefix used for all resources in this example.
- `location` (Required): The Azure Region in which the resources in this example should exist.
- `tags` (Optional): Any tags which should be assigned to the resources in this example.
- `number_of_disks` (Optional): The number of Data Disks which should be attached, defaults to `2`.
