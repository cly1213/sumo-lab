# sumo-lab

```bash
netconvert --node-files=exa.nod.xml --edge-files=exa.edg.xml --connection-files=exa.con.xml --output-file=exa.net.xml

sumo-gui -c exa.sumocfg

sumo -c myConfig.sumocfg --fcd-output sumoTrace.xml

python traceExporter.py --fcd-input sumoTrace.xml --ns2mobility-output ns2mobility.tcl
```
<img src="https://github.com/cly1213/sumo-lab/blob/master/demo.gif"/>

recording by https://github.com/phw/peek

https://sumo.dlr.de/docs/Tutorials/Trace_File_Generation.html
