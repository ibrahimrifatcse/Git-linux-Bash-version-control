```sh
diskpart
list disk
select disk X (Replace X with the number of your SSD)
clean (This command erases the disk)
create partition primary
format fs=ntfs quick
exit
