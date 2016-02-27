# WorkflowFileBrowser
An Alfred workflow to browse workflow files
## Usage:
### Workflow

    wf/     -access filtered workflows (see script usage)
    awf/    -access all workflows
    
Workflows can be searched by name, with regex search supported.

### Script
Usage:

    workflowsearch.py <query> [-c|-b|-r|-a|-w] [<keyword>]
    
Options:

    -c    Filter by category
    -b    Filter by bundleid
    -r    Filter by readme
    -a    Filter by createdby
    -w    Show all
