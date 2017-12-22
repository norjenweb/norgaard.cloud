---
title: Third Post
date: 2017-12-19T16:06:22.361Z
---
This is really exciting !!

Wow how easy ;-)

```PowerShell

$answer = read-host "Select All or single server"

    switch ($answer) {
    
        1 {$rebootChoice = "noaction"  }
    
        2 {$rebootChoice = "stop"  }
    
        3 {$rebootChoice = "restart"  }
    
        Default {Write-Error "No valid input submitted"}
    
    }

```

