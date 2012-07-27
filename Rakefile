# -*- ruby -*-

require 'rubygems'
require 'hoe'

Hoe.add_include_dirs("../../ruby_parser/dev/lib",
                     "../../RubyInline/dev/lib",
                     "../../sexp_processor/dev/lib",
                     "../../ZenTest/dev/lib",
                     "../../minitest/dev/lib",
                     "lib")

Hoe.plugin :seattlerb

Hoe.spec 'flog' do
  developer 'Ryan Davis', 'ryand-ruby@zenspider.com'

  self.rubyforge_name = 'seattlerb'

  extra_deps << ['sexp_processor', '~> 4.0']
  extra_deps << ['ruby_parser',    '~> 3.0.0.a4']
end

# vim: syntax=ruby
