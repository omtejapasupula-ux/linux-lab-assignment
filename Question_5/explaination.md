1. `lsblk`

   - **Explanation:** This command lists all available block storage devices and their partitions. It displayed my primary NVMe drive (`nvme0n1`) with multiple partitions, including Linux, Windows, EFI, and several loop devices used by Snap packages.

2. `df -h`

   - **Explanation:** This command displays disk usage in a human-readable format. I observed that the Linux root partition (`/dev/nvme0n1p5`) has a total size of **233G**, with **61G used**, **160G available**, and **28% disk usage**.

3. `df -i`

   - **Explanation:** This command displays inode usage for mounted file systems. The Linux root partition contains **15,556,608** total inodes with **884,655** used and **14,671,953** available, resulting in only **6% inode usage**.

4. `vi Storage_Assessment_Report.txt`

   - **Explanation:** I used the **vi** text editor to create and save the storage assessment report after collecting the required storage information from the previous commands.
