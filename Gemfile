source ENV['GEM_SOURCE'] || 'https://rubygems.org'

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion, :require => false
else
  gem 'puppet', :require => false
end

gem 'rake'
gem 'metadata-json-lint',                               :require => false
gem 'rspec-puppet',                                     :require => false
gem 'puppetlabs_spec_helper',                           :require => false
gem 'puppet-lint',                                      :require => false
gem 'puppet-lint-absolute_classname-check',             :require => false
gem 'puppet-lint-alias-check',                          :require => false
gem 'puppet-lint-empty_string-check',                   :require => false
gem 'puppet-lint-file_ensure-check',                    :require => false
gem 'puppet-lint-file_source_rights-check',             :require => false
gem 'puppet-lint-leading_zero-check',                   :require => false
gem 'puppet-lint-spaceship_operator_without_tag-check', :require => false
gem 'puppet-lint-trailing_comma-check',                 :require => false
gem 'puppet-lint-undef_in_function-check',              :require => false
gem 'puppet-lint-unquoted_string-check',                :require => false
gem 'puppet-lint-variable_contains_upcase',             :require => false

group :documentation do
  gem 'puppet-strings', require: false
end
