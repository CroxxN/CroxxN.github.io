+++
title = 'timetrack: File Usage Instrumentation Utility'
date = 2025-05-27T01:23:40-05:00
draft = false
tags = ['c']
+++

[See @github/timetrack](https://github.com/CroxxN/timetrack)


`timetrack` is a utility to log file changes---particularly file open and file close and derive meaning usage statistics. It operates using a daemon-client model, where a daemon watches a pre-defined list of directories for changes and logs time difference between certain, connected events.

#### Written in: c
