# osx-inform-on
Commandline tool to display Mac OS X notifications for lines matching regex

Example run:

    sbt benchmark |  inform-on '\[success\]' 'Run progress' 'Run complete'

Will run `sbt benchmark` and pipe output through `inform-on` which
will fire Mac OS X notifications when a line from stdin will match any
of the regex supplied.
