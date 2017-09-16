# asap-api.github.io
Finally. an API that is easy to maintain, written in jQuery, with help from Python & some help from YML.
# About
This aQuery API Monster is an/a:
- Async JavaScript API
- HUGE high-level API
- API that adds `new API();` to JavaScript
# Install via npm
use `npm install --asap.git` - it will do the job :)
# Install via aQuery (aQJS)
use `grab(type=["API:jq|py"], name=["asap"], txtType=[text/git] src=[https://github.com/redstone2010/asap-api.github.io.git]);` - it will also do the job :)
# Install via aQL (aQuery)
use ``INSTALL(asap){
  method : INSTALL,
  aQJS(aQ.enableJSON;),
  aQJS{
    CL {
      npm install --asap
      \# the output should look like this:
      \#npm : installing asap
      \# it should stop for 1 second, then continue and output the following:
      \# asap : now use start --asap (or strt --asap)
      start --asap
			
     }
		 
  },
	
}``
