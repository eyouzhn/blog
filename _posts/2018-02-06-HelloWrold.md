---
layout: default
title: 你好，世界
---

# SDD Node CI

## Networks Deployment

SDD Testing deployment has below networks:


{% plantuml format="png" %}
@startditaa
    +-----------------------------------+
    |                     +----------+  |	
    |                     |          |  |
    |                     +          |  |
    |                     |          |  |
    |                     |          |  |	
    |                     |  OSI-RC  |  |
    | Docker              |Simulator |  |
    |                     +---+-+----+  |
    +-------------------------| ^-------+

@endditaa
{% endplantuml %}







