{exec} = require 'child_process'

task 'scss', 'convert scss to css into bin/', ->
	exec 'node-sass src/scss bin/css', (err, stdout, stderr) ->
        throw err if err
        console.log stdout + stderr