# jmeter-cli
```
  ${JMETER_HOME}/bin/jmeter \
    -LINFO \
    -d ${JMETER_HOME} \
    -n -j ${LOG_FILE} \
    -l ${RESULTS_FILE} \
    -R ${SLAVE_IP_LIST::-1} \
    ${PARAM_HOSTS_ARGS} \
    ${PARAM_USERS_ARGS} \
    -t ${JMX_FILE_PATH} \
    -e \
    -o ${RESULTS_DIR}/report-${JMX}-${NOW}
    

    adicionar -l {csv report file path} -e -o {html output report path}
```
