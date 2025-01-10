# Manage Map & Zone

{% hint style="info" %}
Currently in the Fleet Management System, when merchant created new orders, it will sort to the system delivery zone, however, every logistics company has their service area, and the coverage area would vary even if they are using the same name for the service area. This document is about how fleet manager can manage their delivery zone, a.k.a Service Area.
{% endhint %}



## Get Start with My Zones

Before creating your first delivery zones in My Zone, it's important to understand the relationship between zoom level and grid level. These two factors play a crucial role in defining the level of detail and granularity of your zones.



### Zoom Level

By default, when you access My Zone, you will see a world map. As you zoom in on the map, it will automatically focus on your region, which includes Hong Kong, Malaysia, Singapore, and Taiwan.



### Grid Level

My Zone utilizes a hexagonal grid structure to organize geographical areas and define delivery zones. This grid is made up of hexagonal cells, each representing a specific area on the map. The size of these cells varies depending on the grid level, which ranges from **level 1 to 15**. These grid levels determine the level of detail and scale of the zones.



As a Fleet Manager, you have the flexibility to define the granularity of your zones based on your specific requirements. By selecting the appropriate grid level, you can determine the level of detail and precision needed for your delivery zones. <mark style="color:blue;">**Higher grid levels offer more detailed**</mark> and <mark style="color:blue;">**smaller hexagonal cells**</mark>, while <mark style="color:purple;">**lower grid levels provide broader coverage**</mark> with <mark style="color:purple;">**larger hexagonal cells**</mark>.



It's important to note that zones can overlap each other, but only if they are different grid levels. For example, a level 3 zone can overlap with a level 4 zone, but two level 3 zones cannot overlap. When there is an overlapping zone, and an order falls within the overlapping area, My Zone automatically assigns it to the zone with the higher grid level. This ensures that the order is assigned to the more specific and detailed zone, improving accuracy in zone assignment.



### Relationship between Zoom Level and Grid Level

The relationship between zoom level and grid level is that they work together to provide you with the desired level of detail and zoom in your map view.

When you increase the zoom level, the map displays smaller areas with more detail, and it allows you to visualize the hexagonal cells at higher grid levels.

Conversely, when you decrease the zoom level, the map shows larger areas with less detail, and it displays the hexagonal cells at lower grid levels.



## Overview of My Zones

<figure><img src="../.gitbook/assets/Fleet Portal User Manual Image-English.drawio.png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="67">#</th><th width="234">Items</th><th>Description</th></tr></thead><tbody><tr><td>1</td><td>Zoom</td><td>[+] : Zoom in, [-]: Zoom out</td></tr><tr><td>2</td><td>Map Pane</td><td>Area that allows fleet manager to visualize and interact with the zones</td></tr><tr><td>3</td><td>Delivery Zones</td><td>The delivery zone that has created/removed. <br><br>Tips: The colour of the delivery zone is the same as the colour of the Grid level header in the List of Delivery Zones.</td></tr><tr><td>4</td><td>Show All Zones</td><td>Display all the delivery zones across all grid levels</td></tr><tr><td>5</td><td>Last Publish at</td><td>Last publish datetime of the map</td></tr><tr><td>6</td><td>Grid Level</td><td>Current grid level of the map will display the created zones under this grid level only if "Show All Zones" is disabled.</td></tr><tr><td>7</td><td>Zone created</td><td>Total number of the zone that has been created including removed zone if the map is not published.</td></tr><tr><td>8</td><td>Expand All<br>Collapse All</td><td>Expand All: Reveal all of your delivery zones at once on the control panel;<br>Collapse All: Hide all of your delivery zones at once on the control panel</td></tr><tr><td>9</td><td>List of Delivery Zones</td><td>All delivery zones you have added or updated. The removed zone will also be listed until Publish Map</td></tr><tr><td>10</td><td>Create Zone</td><td>Enable to create new delivery zone on map</td></tr><tr><td>11</td><td>Publish Map</td><td>Enable all the changes of the map after the Last publish date to take effective, so that new order would sort to new zone.</td></tr></tbody></table>



## Zone Creation

1.  Navigate to the "My Zone" section.

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-08 at 4.13.54 PM.png" alt=""><figcaption></figcaption></figure>
2. Click \[+] to zoom into the map, locate the area for your delivery zone
3. Click "Create Zone" to activate the grid cell selector
   1. if the hexagonal cells are too big for the delivery zone, you can zoom in for a higher grid level to get a detailed and precise service area.
   2. if you want a border view of your delivery zone, you can zoom out for a lower grid level.
4. Select the hexagonal cells for the delivery zone.
   1. Once hexagonal cells are selected, the zoom level will be locked.
   2. Click the hexagonal cells again to deselect.
5.  Enter the "Zone Name".

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-08 at 11.42.04 PM.png" alt=""><figcaption></figcaption></figure>
6. Click "Save Zone" to create a zone
   1. After the zone is saved, a new record is created and there will be a red icon at the end of the row which means the change has not been activated
7.  Click "Publish" to activate your changes

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-08 at 11.45.22 PM.png" alt=""><figcaption></figcaption></figure>
8.  Click "Publish" again to confirm the changes

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-08 at 11.49.33 PM (1).png" alt=""><figcaption></figcaption></figure>
9. The map changes has take effective.
   1.  After the map is published, there will be a green icon at the end of the zone record which mean the change has activated

       <figure><img src="../.gitbook/assets/Screenshot 2024-02-08 at 11.52.27 PM.png" alt=""><figcaption></figcaption></figure>



## Edit Zone

1. Go to "My Zones"
2.  On the zone list under the control panel, select the delivery zone you would like to edit.

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-08 at 11.52.27 PM (1).png" alt=""><figcaption></figcaption></figure>
3. Click on the "Pencil icon" on the row to edit zone
   1. To update the delivery zone, select more hexagonal cells or deselect the hexagonal cells
   2. Update zone name if needed
4. Click "Save zone" after editing is completed
   1.  After the zone is saved, there will be a red icon at the end of the row which means the change has not been activated

       <figure><img src="../.gitbook/assets/Screenshot 2024-02-08 at 11.53.46 PM.png" alt=""><figcaption></figcaption></figure>
5.  Click "Publish" to activate the changes

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-08 at 11.54.02 PM.png" alt=""><figcaption></figcaption></figure>
6.  Click "Publish" again on the confirm window

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-08 at 11.54.26 PM (1).png" alt=""><figcaption></figcaption></figure>
7.  The map changes have taken effective.

    1.  After the map is published, there will be a green icon at the end of the zone record which means the change has been activated

        <figure><img src="../.gitbook/assets/Screenshot 2024-02-09 at 12.18.56 AM.png" alt=""><figcaption></figcaption></figure>



## Delete Zone

1. Go to "My Zones"
2. On the zone list under the control panel, select the delivery zone you would like to delete.
3.  Click on the "Pencil icon" to activate zone editing

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-08 at 11.54.54 PM.png" alt=""><figcaption></figcaption></figure>
4.  Click on the "Trash icon" to remove zone

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-09 at 12.19.26 AM (1).png" alt=""><figcaption></figcaption></figure>
5. Click "Delete" to confirm removing the zone
   1.  After confirming the deletion of the zone, the zone will be crossed out and there will be a red icon at the end of the row which means the change has not activated

       <figure><img src="../.gitbook/assets/Screenshot 2024-02-09 at 12.19.40 AM.png" alt=""><figcaption></figcaption></figure>
6.  Click "Publish" to activate the changes

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-09 at 12.19.50 AM (1).png" alt=""><figcaption></figcaption></figure>
7.  Click "Publish" again on the confirm window

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-09 at 12.20.09 AM (1).png" alt=""><figcaption></figcaption></figure>
8. The map changes have taken effect.
   1. After the map is published, the deleted zone will be removed from the list
   2.  If there is no more zone on the list after publication, the **Last publish at** will not be shown

       <figure><img src="../.gitbook/assets/Screenshot 2024-02-09 at 12.20.22 AM.png" alt=""><figcaption></figcaption></figure>



## Troubleshooting

1.  When creating a new zone/ editing a zone in an area where a delivery zone already exists nearby at the same grid level, you may encounter a limitation where you are unable to directly select or include the related hexagonal cells from the existing zone.

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-09 at 9.52.32 AM.png" alt=""><figcaption></figcaption></figure>
2.  When creating or editing zones, you have the option to enable the "Show all zones" feature. By enabling this feature, you can view and incorporate delivery zones that exist in other grid levels. This allows you to consider and include relevant zones from different grid resolutions while creating or modifying your zones.

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-09 at 9.54.54 AM.png" alt=""><figcaption></figcaption></figure>
