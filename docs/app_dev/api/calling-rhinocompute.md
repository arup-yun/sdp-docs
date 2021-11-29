---
title: Calling RhinoCompute from TDA
---
# How to run Grasshopper scripts on the RhinoCompute server

[ArupCompute](https://compute.arup.digital/) hosts a number of Engineering and Design libraries in a scalable cloud environment for other projects to use.  Libraries such as [DesignCheck](https://arup.sharepoint.com/teams/global-design-automation-team/SitePages/DesignCheck.aspx) include a large amount of verified engineering functions and logic that can be re-used.

Libraries (and the functions contained within them) can be called directly from the TDA App API using standard Web API calls.

## Examples
For a simple example of calling RhinoCompute directly via the REST API, see the 'sample_submit' app in the TDA Apps API repository.

For an example of calling RhinoCOmpute via the message queues, see the 'drawing_submit' app in the TDA API and UI repositories.


:::warning todo
- Summarize the two methods of calling RhinoCOmpute (pro/cons etc)
:::