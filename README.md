# USB-device-access-monitor

📝 Problem Statement

USB devices (pen drives, external HDDs, etc.) can be misused to steal sensitive data or inject malware. Most systems don’t log when a USB is connected or disconnected. This project builds a tool that monitors all USB device activity and provides a web dashboard to track it.

🔹 Data to Collect & Store

     When a USB device is connected/disconnected, log:

        Timestamp (date & time of event)

        Event type (Connected / Disconnected)

        Device Name (e.g., SanDisk USB)

        Device ID / Serial Number

        Volume Label (if available)

        System Username (who was logged in)

   
🔹 Website Pages

   1.Home/Dashboard

    Shows latest USB activities in a table.

   2.Search/Filter Page

    Search by date, device name, or user.

  3.Analytics Page

    Graph of “Number of USB devices connected per day/week”. 




