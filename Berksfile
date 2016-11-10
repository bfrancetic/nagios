source 'https://supermarket.chef.io'

metadata

cookbook 'chef_nginx'

group :integration do
  cookbook 'yum'
  cookbook 'apt'
  cookbook 'freebsd'
  cookbook 'nagios_test', path: './test/fixtures/cookbooks/nagios_test'
end
