# esxi

ssh
cp -v /etc/vmware/vsphere-ui/compatibility-matrix.xml /etc/vmware/vsphere-ui/compatibility-matrix.xml.backup

vi /etc/vmware/vsphere-ui/compatibility-matrix.xml

<PluginPackage id="com.vmware.vrops.install" status="incompatible"/>

service-control --stop vsphere-ui

service-control --start vsphere-ui

https://172.168.168.151/ui/vropspluginui/rest/services/checkmobregister
