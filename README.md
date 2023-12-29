# jmeter-cli
```
 ${JMETER_HOME}/bin/jmeter \
 -t ${JMX_FILE_PATH}/test-file.jmx \
     -LINFO \
    -d ${JMETER_HOME} \
    -n \
    -j ${LOG_FILE} \
    -l ${RESULTS_FILE} \
    -e \
    -o ${RESULTS_DIR}/report-${JMX}-${NOW}
 
```
| **Option** | **Declarative Option**          | **Description**                           |
|------------|---------------------------------|-------------------------------------------|
| -t         | --testfile <argument>           | the jmeter test(.jmx) file to run         |
| -LINFO     | --loglevel                      | Logging level, other option DEBUG, WARN   |
| -d         | --homedir <argument>            | the jmeter home directory to use          |
| -n         | --nongui                        | run JMeter in nongui mode                 |
| -j         | --jmeterlogfile <argument>      | jmeter run log file (jmeter.log)          |
| -l         | --logfile <argument>            | the file to log samples to                |
| -e         | --reportatendofloadtests        | generate report dashboard after load test |
| -o         | --reportoutputfolder <argument> | output folder for report dashboard        |
