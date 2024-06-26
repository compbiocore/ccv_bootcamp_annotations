## To use this notebook

1.  Go to `ood.ccv.brown.edu` (you will need an Oscar account).
2.  Go to 'Clusters' in the blue menu bar at the top and click the drop-down that says '\>\_OSCAR Shell Access'
3.  Go to your home folder (`cd ~`)
4.  Git clone the repo (\``git clone https://github.com/compbiocore/ccv_bootcamp_annotations.git`\`)
5.  Go back to `ood.ccv.brown.edu` and look under `Interactive Apps` in the blue menu bar and click on `RStudio on Singularity` under `Expert GUIs`.

Fill in the fields as follows:

-   `Account`: leave blank

-   `Partition`: leave blank

-   `Number of hours`: 24

-   `Num Cores`: 4

-   `Memory`: 15

-   `Singularity Container Path`:/oscar/data/shared/databases/workshops/bootcamp_2024/ngs_counts/ngscounts.sif

-   `Package install Path`: leave blank

-   `Path for R Executable`: ~/scratch

-   `R Module`: leave blank

-   `Additional Data Path`: leave blank

-   `Reservation`: leave blank

I added many of you to the reservation, but not all of you, so you might need to leave the `Reservation` field blank as well. Once your job starts, click the button to connect to session. At the top of the screen you'll see a menu bar that starts with 'file', click on 'file' and 'open file' and open the notebooks/index.qmd file in the repo you cloned. 
