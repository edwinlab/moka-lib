require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('moka-lib', '0.1.0') do |p|
  p.description    = "Generate a unique token with Active Record."
  p.url            = "http://github.com/edwinlab/moka-lib"
  p.author         = "Edwin Andrianto"
  p.email          = "edwinuad@gmail.com"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }