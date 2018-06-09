# opendlv.standard-message-set

The OpenDLV standard message set should be used for all communication
within the OpenDLV framwork.

Where relevant, always use SI units.

## Messages

### Simulation messages

opendlv.sim.Frame (id: 1001)
opendlv.sim.KinematicState (id: 1002)

### Sensor readings

opendlv.proxy.AccelerationReading (id: 1030)
opendlv.proxy.AngularVelocityReading (id: 1031)
opendlv.proxy.MagneticFieldReading (id: 1032)
opendlv.proxy.AltitudeReading (id: 1033)
opendlv.proxy.PressureReading (id: 1034)
opendlv.proxy.TemperatureReading (id: 1035)
opendlv.proxy.TorqueReading (id: 1036)
opendlv.proxy.VoltageReading (id: 1037)
opendlv.proxy.AngleReading (id: 1038)
opendlv.proxy.DistanceReading (id: 1039)
opendlv.proxy.SwitchStateReading (id: 1040)
opendlv.proxy.PedalPositionReading (id: 1041)
opendlv.proxy.GroundSteeringReading (id: 1045)
opendlv.proxy.GroundSpeedReading (id: 1046)
opendlv.proxy.WheelSpeedReading (id: 1047)
opendlv.proxy.WeightReading (id: 1050)
opendlv.proxy.GeodeticHeadingReading (id: 1051)
opendlv.proxy.GeodeticWgs84Reading (id: 19)
opendlv.proxy.ImageReading (id: 1055)
opendlv.proxy.ImageReadingShared (id: 14)
opendlv.proxy.PointCloudReading (id: 49)
opendlv.proxy.PointCloudReadingShared (id: 28)

### Actuation requests

opendlv.proxy.PressureRequest (id: 1080)
opendlv.proxy.TemperatureRequest (id: 1081)
opendlv.proxy.TorqueRequest (id: 1082)
opendlv.proxy.VoltageRequest (id: 1083)
opendlv.proxy.AngleRequest (id: 1084)
opendlv.proxy.SwitchStateRequest (id: 1085)
opendlv.proxy.PedalPositionRequest (id: 1086)
opendlv.proxy.PulseWidthModulationRequest (id: 1087)
opendlv.proxy.GroundSteeringRequest (id: 1090)
opendlv.proxy.GroundSpeedRequest (id: 1091)
opendlv.proxy.GroundAccelerationRequest (id: 1092)
opendlv.proxy.GroundDecelerationRequest (id: 1093)
opendlv.proxy.WheelSpeedRequest (id: 1094)

### System messages

opendlv.system.SignalStatusMessage (id: 1100)
opendlv.system.SystemOperationState (id: 1101)
opendlv.system.NetworkStatusMessage (id: 1102)

### Perception messages

opendlv.logic.sensation.Direction (id: 1110)
opendlv.logic.sensation.Point (id: 1111)
opendlv.logic.sensation.Geolocation (id: 1116)
opendlv.logic.sensation.Equilibrioception (id: 1017)
opendlv.logic.perception.Object (id: 1130)
opendlv.logic.perception.ObjectType (id: 1131)
opendlv.logic.perception.ObjectProperty (id: 1132)
opendlv.logic.perception.ObjectDirection (id: 1133)
opendlv.logic.perception.ObjectDistance (id: 1134)
opendlv.logic.perception.ObjectAngularBlob (id: 1135)
opendlv.logic.perception.GroundSurface (id: 1140)
opendlv.logic.perception.GroundSurfaceType (id: 1141)
opendlv.logic.perception.GroundSurfaceProperty (id: 1142)
opendlv.logic.perception.GroundSurfaceArea (id: 1143)

### Control messages

opendlv.logic.action.AimDirection (id: 1171)
opendlv.logic.action.AimPoint (id: 1172)
opendlv.logic.action.PreviewPoint (id: 1173)
opendlv.logic.cognition.GroundSteeringLimit (id: 1191)
opendlv.logic.cognition.GroundSpeedLimit (id: 1192)
