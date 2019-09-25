# supported features for WDC

## standardized features in oneM2M

Bindings
- HTTP and MQTT

Serialization
- JSON 

Resource types
- CSEBase
- remoteCSE
- AE
- container
    - latest
    - oldest 
- contentInstance
- group
    - fanOutPoint
- subscription
    - notification 
- flexContainer

Parameters
- Response Type
    - supported options: blocking 
- Result Content
    - supported options: attributes, child-resources
- Filter Criteria

## extended features that would be included in oneM2M Rel-4 soon

- geo-query
- getting multiple content instances on `latest` and `oldest` virtual resources
