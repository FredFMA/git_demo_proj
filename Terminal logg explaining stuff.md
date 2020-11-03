#How to add a remote repository from github
#fredrik@P51s:~$ cd ~/git_demo_proj 
#fredrik@P51s:~/git_demo_proj$ git remote add origin https://github.com/FredFMA/git_demo_proj.git
#fredrik@P51s:~/git_demo_proj$ git remote
#origin
#fredrik@P51s:~/git_demo_proj$ git remote -v
#origin  https://github.com/FredFMA/git_demo_proj.git (fetch)
#origin  https://github.com/FredFMA/git_demo_proj.git (push)

#Pushing to github via the terminal. Make sure you're working from the correct directory'

#fredrik@P51s:~/git_demo_proj$ git branch = what branch are we working on
#* master
#fredrik@P51s:~/git_demo_proj$  git remote = dont remember just leave it like that unless working with several remote repositories
#origin
#fredrik@P51s:~/git_demo_proj$ git push -u origin master
#03 Nov 2020 12:43:02 [rpostback] ERROR system error 111 (Connection refused); OCCURRED AT void rstudio::core::http::TcpIpAsyncConnector::handleConnect(const rstudio_boost::system::error_code&, rstudio_boost::asio::ip::basic_resolver<rstudio_boost::asio::ip::tcp>::iterator) /var/lib/jenkins/workspace/IDE/open-source-pipeline/v1.3/src/cpp/core/include/core/http/TcpIpAsyncConnector.hpp:210; LOGGED FROM: int exitFailure(const rstudio::core::Error&) /var/lib/jenkins/workspace/IDE/open-source-pipeline/v1.3/src/cpp/session/postback/PostbackMain.cpp:47
#error: unable to read askpass response from 'rpostback-askpass'
#Username for 'https://github.com': FredFMA
#03 Nov 2020 12:44:49 [rpostback] ERROR system error 111 (Connection refused); OCCURRED AT void rstudio::core::http::TcpIpAsyncConnector::handleConnect(const rstudio_boost::system::error_code&, rstudio_boost::asio::ip::basic_resolver<rstudio_boost::asio::ip::tcp>::iterator) /var/lib/jenkins/workspace/IDE/open-source-pipeline/v1.3/src/cpp/core/include/core/http/TcpIpAsyncConnector.hpp:210; LOGGED FROM: int exitFailure(const rstudio::core::Error&) /var/lib/jenkins/workspace/IDE/open-source-pipeline/v1.3/src/cpp/session/postback/PostbackMain.cpp:47
#error: unable to read askpass response from 'rpostback-askpass'
#Password for 'https://FredFMA@github.com': 
#  Branch 'master' set up to track remote branch 'master' from 'origin'.
#Everything up-to-date