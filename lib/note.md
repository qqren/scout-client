
    3 ./scout/version.rb
    15 ./scout.rb
    18 ./scout/scout_logger.rb
    24 ./scout/environment.rb
    24 ./scout/http.rb
    49 ./scout/data_file.rb
    58 ./scout/streamer_daemon.rb
    62 ./scout/command/test.rb
    81 ./scout/command/run.rb
    87 ./scout/command/sign.rb
    90 ./scout/plugin_options.rb
    97 ./scout/server_base.rb
    122 ./scout/command/install.rb
    136 ./scout/command/troubleshoot.rb
    201 ./scout/streamer.rb
    215 ./scout/daemon_spawn.rb
    247 ./scout/plugin.rb
    302 ./scout/command.rb
    626 ./scout/server.rb
    2457 总用量

### ./scout/server.rb

### /home/coremail/.rvm/gems/ruby-1.9.3-p385/bin/scout: 

```ruby
gem 'scout', version
load Gem.bin_path('scout', 'scout', version) #=> load "/home/coremail/.rvm/gems/ruby-1.9.3-p385/gems/scout-5.7.1/bin/scout"
```
#### /home/coremail/.rvm/gems/ruby-1.9.3-p385/gems/scout-5.7.1/bin/scout

```ruby
$LOAD_PATH << File.join(File.dirname(__FILE__), *%w[.. lib]) #=> /home/coremail/.rvm/gems/ruby-1.9.3-p385/gems/scout-5.7.1/bin/../lib/
  require "scout"

  Scout::Command.dispatch(ARGV) #=> ./scout/command.rb
```  

#### ./scout/command.rb

- 命令行解析 Scout::Command.dispatch(argv) => 

