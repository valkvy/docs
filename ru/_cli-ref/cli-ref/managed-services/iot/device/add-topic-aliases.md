# yc iot device add-topic-aliases

Add aliases for topics of specified device

#### Command Usage

Syntax: 

`yc iot device add-topic-aliases <DEVICE-NAME>|<DEVICE-ID> --aliases ALIAS=TOPIC[,ALIAS=TOPIC...] [Flags...] [Global Flags...]`

#### Global Flags

| Flag | Description |
|----|----|
|`--id`|<b>`string`</b><br/> Device id.|
|`--name`|<b>`string`</b><br/> Device name.|
|`--async`| Display information about the operation in progress, without waiting for the operation to complete.|
|`--topic-aliases`|<b>`key=value[,key=value...]`</b><br/> A list of ALIAS=TOPIC_PREFIX pairs to add.|

#### Flags

| Flag | Description |
|----|----|
|`--profile`|<b>`string`</b><br/>Set the custom configuration file.|
|`--debug`|Debug logging.|
|`--debug-grpc`|Debug gRPC logging. Very verbose, used for debugging connection problems.|
|`--no-user-output`|Disable printing user intended output to stderr.|
|`--retry`|<b>`int`</b><br/>Enable gRPC retries. By default, retries are enabled with maximum 5 attempts. Pass 0 to disable retries. Pass any negative value for infinite retries. Even infinite retries are capped with 2 minutes timeout.|
|`--cloud-id`|<b>`string`</b><br/>Set the ID of the cloud to use.|
|`--folder-id`|<b>`string`</b><br/>Set the ID of the folder to use.|
|`--folder-name`|<b>`string`</b><br/>Set the name of the folder to use (will be resolved to id).|
|`--token`|<b>`string`</b><br/>Set the OAuth token to use.|
|`--format`|<b>`string`</b><br/>Set the output format: text (default), yaml, json, json-rest.|
|`-h`,`--help`|Display help for the command.|