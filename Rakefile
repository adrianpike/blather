require 'echoe'
require 'hanna/rdoctask'

Echoe.new('blather') do |p|
  p.author = 'Jeff Smick'
  p.email = 'sprsquish@gmail.com'
  p.url = 'http://github.com/sprsquish/blather/tree/master'

  p.project = 'squishtech'
  p.summary = 'An evented XMPP library written on EventMachine and libxml-ruby'

  p.runtime_dependencies = ['eventmachine', 'libxml-ruby >=0.9.2']
  p.rdoc_options += %w[-S -T hanna --main README.rdoc --exclude autotest]

  p.test_pattern = 'spec/**/*_spec.rb'
  p.rcov_options = ['--exclude \/Library\/Ruby\/Gems,spec\/', '--xrefs']
end