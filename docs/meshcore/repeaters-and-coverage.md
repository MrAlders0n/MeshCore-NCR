# Overview

MeshCore coverage in the Ottawa area is provided by a backbone of solar-powered repeaters. Coverage can vary based on height, line-of-sight, and terrain, but the network generally reaches Ashton, Barrhaven, Buckingham, Carleton Place, Cumberland, Downtown, Kanata, Nepean, Old Ottawa South, Orleans, Richmond, and Stittsville.

For a live view of deployed nodes, check the [MeshCore Map](https://analyzer.letsme.sh/map?lat=45.4215&long=-75.6972&zoom=9).  
Use the filter at the top and select **Repeaters only** to see active backbone nodes in Ottawa.

## Available Repeater IDs

The following MeshCore node identifiers are currently **unused** and available for future Ottawa repeaters:  
```{{ unused_ids | join(',') }}```
*({{ unused_ids | length }} remaining IDs)*

## Deployed Repeater IDs

The table below lists currently deployed Ottawa repeaters.  
Each repeater has a unique ID, a name for easier reference, and basic information on location/height.

| Identifier | Repeater Name   | Antenna   | Location / Height   | MeshCore Contact URL |
|-----------:|-----------------|-----------|---------------------|----------------------|
{% for r in repeaters -%}
| {{ r.id }} | {{ r.name }} | {{ r.antenna }} | {{ r.location }} | {%- if r.contact %} [Contact]({{ r.contact }}) {%- else %} TBD {%- endif %} |
{% endfor %}

*If you spot an error in this repeater list or would like to add your own, please contact MrAlders0n on the Greater Ottawa Mesh Enthusiasts Discord.*

## Detailed Coverage Maps

This section contains community-generated coverage maps based on expected RF propagation.  
These are estimates only — actual coverage may vary depending on terrain, buildings, and antenna placement.

CAN to Ground (@2.0M)

![](images/CAN_to_Groundnode_2M.png){ width="300" }

CAN to Roof (@7.5M)

![](images/CAN_To_Roofnode.png){ width="300" }
