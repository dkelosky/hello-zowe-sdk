# Getting Started

1. `git clone https://github.com/dkelosky/hello-zowe-sdk`
2. `cd hello-zowe-sdk`
3. `npm install`
4. `npx tsc`
5. `node lib\index.js`

## Output

```
C:\dev\node\hello-zowe-sdk>node lib\index.js
[
  {
    owner: 'IBMUSER',
    phase: 20,
    subsystem: 'JES2',
    'phase-name': 'Job is on the hard copy queue',
    'job-correlator': 'J0003237USILDAMDD998DC1B.......:',
    type: 'JOB',
    url: 'https://lpar.zosmf.net:443/zosmf/restjobs/jobs/J0003237USILDAMDD998DC1B.......%3A',
    jobid: 'JOB03237',
    class: 'K',
    'files-url': 'https://lpar.zosmf.net:443/zosmf/restjobs/jobs/J0003237USILDAMDD998DC1B.......%3A/files',
    jobname: 'IBMUSER$',
    status: 'OUTPUT',
    retcode: 'CC 0000'
  },
  {
    owner: 'IBMUSER',
    phase: 14,
    subsystem: 'JES2',
    'phase-name': 'Job is actively executing',
    'job-correlator': 'T0003235USILDAMDD998DC12.......:',
    type: 'TSU',
    url: 'https://lpar.zosmf.net:443/zosmf/restjobs/jobs/T0003235USILDAMDD998DC12.......%3A',
    jobid: 'TSU03235',
    class: 'TSU',
    'files-url': 'https://lpar.zosmf.net:443/zosmf/restjobs/jobs/T0003235USILDAMDD998DC12.......%3A/files',
    jobname: 'IBMUSER',
    status: 'ACTIVE',
    retcode: null
  }
]
```