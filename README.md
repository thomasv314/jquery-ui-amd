jquery-ui-amd
=============

jQuery-UI in Asynchronous Module Definition format. 

Clone repo and copy and paste the jqueryui folder into your AMD lib path. 

Add:

require.config({
  paths: {
      'jqueryui':       'lib/jqueryui',
    },
  }
});
