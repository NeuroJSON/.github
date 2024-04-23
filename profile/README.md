# NeuroJSON Project Overview

The NeuroJSON project is designed to address the following challenges in neuroimaging data sharing
1. **Scalability** - NeuroJSON data dissemination services capitalize upon modern NoSQL database technologies to efficient process and distribute large sized and complex neuroimaging datasets.
2. **Findablity** - NeuroJSON utilizes internationally standardized JSON format as the unified data exchange format for scientific data, making data both human and machine readable, directly searchable locally and in the cloud.
3. **Long-term reusability** - NeuroJSON recognizes that human-readability of the data is the underpinning for data's long-term viability, and is dedicated to enrich metadata-based annotations, queries, visualization etc to ensure data's long-lasting impact.

## Data consumers
Please browse our public data portal https://neurojson.io

You can read about
- [Getting-started guide](https://neurojson.org/Doc/Start/User)
- [Search data from 38,000 subjects](https://neurojson.org/Search)
- [Download our software tools](https://neurojson.org/#software) to use JSON-encoded data in [Python](https://pypi.org/project/jdata/), [MATLAB/Octave](https://github.com/fangq/jsonlab) etc
- If you need automation, please use our [RESTful API](https://neurojson.org/wiki/index.cgi?Doc/Start/User#Access_data_using_RESTful_APIs) to access our lightweight datasets in your program or cloud-based analyses

## Data creators
NeuroJSON.io is an NIH-funded data dissemination service and we'd love to help you disseminate your data. Please consider contributing your data to our [data constellation](https://neurojson.io)! We are committed to supporting long term public data availability and reusability.

- We prefer [BIDS data](https://bids-specification.readthedocs.io/en/stable/)! if you have raw or processed data that can be organized in the BIDS format, plese follow the [guides](https://bids-standard.github.io/bids-starter-kit/) to convert your data to the BIDS compliant format
- Please download our [light-weight client tool, `neuroj`](https://github.com/NeuroJSON/neuroj), or it's [read-to-use docker image](https://hub.docker.com/repository/docker/openjdata/neuroj/general) (`docker pull openjdata/neuroj:v0.5`) and convert your dataset to JSON form
- Please create a new ticket to upload your data to our database 

## Data archive admins
NeuroJSON is excited to become your collaborator for creating new pathways in disseminating the data you are currently hosting. We can particularly help with
- making your data searchable and discoverable across multiple data archives
- extracting metadata and integrate with our web-based search and visualization functions
- distributing your data using our RESTful APIs and JSON format for broad access across programming environments

We can create dedicated account for your organization to facilitate data upload, update, customized meta-data extraction and other advanced functionalities. Please contact [NeuroJSON admin](mailto:q.fang@neu.edu) to give it a try.
