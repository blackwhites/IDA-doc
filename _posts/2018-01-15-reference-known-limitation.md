---
layout: page
title: "Known Limitation"
category: references
date: 2018-01-05 15:17:55
order: 7
---

- The IDA plugin only supports Firefox and Chrome.
- The JS window.alert function can't be supported by IDA plugin, so we disable it in IDA plugin.
- IDA firefox plugin doesn't support self-sign certification very well, please use http protocol if you want to use IDA firefox plugin.
- BPM Deployment feature only supports Linux server via SSH (or install SSH server on Windows server).
- Complex parameters can not be passed to the human service.
- Global variables declared in Server Managed files .JS are flagged as "was used before" it was defined in checkstyle report.
- The file upload commands UI.file and UI.bpmFileUploader can't be replayed on IDA Plugin due to browser security issue, but these commands can work on Selenium Grid. So you can record the file upload commands by IDA Plugin, but replay them on Selenium Grid.
- The command UI.close is disabled in IDA plugin which may caused issue in plugin.
