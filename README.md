trackobject
===========

this is an experimental and useful piece of javascript tool to keep track of JSON objects of similar structure (though, structure may vary if the signature key combinations are same). 

key objectives/features are 
    1. javascript only
    2. fast
    3. event driven
    4. support for adding 3-rd party event handlers (e.g. jQuery, knockout)

it is built with the No-Postback (aka no-refreshing of page) operation in mind and to track JSON objects in a Single Page (forwarding to multiple page is as easy as just moving a single javascript object) scenario.
