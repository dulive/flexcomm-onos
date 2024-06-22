# Openflow

- **flexcomm-openflow-extension**: openflow extension that allows to retrieve
  current energy consumption and total power drawn of the device and for each port

# Onos modules

- **flexcomm-onos-statistics**: onos module that retrieves energy information of
  the device and its ports using the openflow extension
- **flexcomm-onos-energy**: onos module that allows to obtain flexibility and
  consumption estimate from the power grid (includes test version to use with
  [Flexcomm-Simulator](https://github.com/RuiCunhaM/Flexcomm-Simulator))
- **flexcomm-onos-fwd**: reactive forwarding based on energy flexibility for onos
- **flexcomm-onos-netcfglinksprovider**: onos modules to configure links without
  verifying with LLDP (for use with [Flexcomm-Simulator](https://github.com/RuiCunhaM/Flexcomm-Simulator))
