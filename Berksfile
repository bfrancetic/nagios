source 'https://supermarket.chef.io'

metadata

cookbook 'chef_nginx'
cookbook 'nginx_simplecgi', git: 'https://github.com/bfrancetic/nginx_simplecgi'

group :integration do
  cookbook 'yum'
  cookbook 'apt'
  cookbook 'freebsd'
  cookbook 'nagios_test', path: './test/fixtures/cookbooks/nagios_test'
end
