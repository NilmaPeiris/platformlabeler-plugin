#!groovy

// test base Jenkins version and 2.138.1
buildPlugin(jenkinsVersions: [null, '2.138.1'],
            jdkVersions: ['8'],
            findbugs: [run:true, archive:true, unstableTotalAll: '0'],
            checkstyle: [run:true, archive:true, unstableTotalAll: '16'],
            failFast: false)
