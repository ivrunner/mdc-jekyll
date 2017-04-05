Install Jekyll

jekyll new my-project

Copy _assets folder from gem theme.

create _sass directory and do bourbon install and neat install into that directory

Add @import "bourbon/bourbon"; and @import "neat/neat"; to main.scss in assets folder.

serve jekyll to check for errors.

notes:

To fix images, set baseurl in config file to "my-project". then add {{ site.baseurl }} in front of your img src. 
