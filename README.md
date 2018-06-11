# AK-Slack

The labels of datasets have following meanings:

sid         : Sensor Id of sensor which produced the event
ts          : Timestamp value
x, y, z     : Position of sensor
|v|         : Velocity
vx, vy, vz  : Metric used in velocity calculation. Read *
|a|         : Acceleration
ax, ay, az  : Absolute acceleration in respective direection

*   :   Using vx, vy, vz velocity in directions x,y and z can be calculated as,
        v’x = |v| * vx * 1e-4 * 1e-6
        
