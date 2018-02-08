---
title: "Tally Odbc Port"
date: 2017-11-13T13:25:22+05:30
weight: 12
draft: false
---

## Find ODBC Port

Check for ODBC Port number on the bottom section of **Tally ERP 9** screen inside the configuration box. By default, it should be *&quot;9000&quot;*. Use this number to setup **Tally ERP 9** with **Biz Analyst Desktop** application.

If you do not see this port number you can easily setup ODBC port number by following these [instructions](#setup-odbc-port)

![Find ODBC Port](../../../images/tally/1_tally.png "Tally ODBC Port")

## Setup ODBC Port

1. Click inside the *Configuration* box located at the bottom right area of the screen.
2. In the *Configuration* screen, goto *ODBC Configuration* area and select *Tally is acting as* (this should be *None*) and press Enter.  
![ODBC Configuration](../../../images/tally/2_tally.png "ODBC Configuration")
3. In the *&quot;Client/Server Configuration&quot;* screen change *&quot;Tally.ERP 9 is acting as&quot;* to _**&quot;Server&quot;**_.  
![Tally.ERP 9 acting as Server](../../../images/tally/3_tally.png "Tally.ERP 9 acting as Server")
4. Save the configuration and restart *&quot;Tally ERP 9&quot;* by following on screen instructions.  
![Save configuration](../../../images/tally/4_tally.png "Save configuration")
![Restart Tally ERP 9](../../../images/tally/5_tally.png "Restart Tally ERP 9")
5. You should now see *&quot;Server with ODBC&quot;* with port number in the configuration section at the bottom right of the screen.