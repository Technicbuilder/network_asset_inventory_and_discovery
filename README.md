# network_asset_inventory_and_discovery

My program should answer the following questions when used:

What devices exist on my network?
When did a new device appear?
Did an IP or hostname change?
Is something missing or suspicious?

It will do this by pinging devices on the network every 5-10 mins, using nmap and other packages which I will add to a list if I do use them.
If any suspicous activityis to occur, it will alert me using gmail/somrthing (not sure yet)

main.py
 ├─ network_scan()
 ├─ normalize_results()
 ├─ compare_with_db()
 ├─ store_snapshot()
 └─ notify_changes()
