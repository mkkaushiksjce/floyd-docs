Clone the code for a specific job.

### Usage
```bash
floyd clone JOB_NAME
```

### Options
| Name, shorthand | Default | Description |
| --------------- | ------- | ----------- |
| JOB_NAME or ID |      | Name or ID of your job. |

### Description
Use this command to clone an existing project on floyd. The code used for the job is downloaded to the
current directory. This will override any existing file or directory in the process.

This command is a great way to get started on floyd by starting from an existing project.

This command can take a [shortened job name](../guides/shortnames).

### Example
```bash
$ floyd clone floydhub/projects/deep-photo-styletransfer/4
Downloading the tar file to the current directory ...
Untarring the contents of the file ...
Cleaning up the tar file ...
```

{!contributing.md!}
