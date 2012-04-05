# -*- ruby -*-

require 'rubygems'
require 'hoe'

path = ENV['PATH'].split(File::PATH_SEPARATOR)
unless path.include? '/sbin'
  ENV['PATH'] = "#{ENV['PATH']}#{File::PATH_SEPARATOR}/sbin"
end

Hoe.plugin :perforce

Hoe.spec 'UPnP' do
  self.rubyforge_name = 'seattlerb'
  developer 'Eric Hodel', 'drbrain@segment7.net'

  extra_deps << ['nokogiri', '~> 1.3']
  extra_deps << ['soap4r']
end

# vim: syntax=Ruby
