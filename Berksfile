source 'https://supermarket.chef.io'

metadata

group :integration do
  cookbook 'apt'
  cookbook 'fqdn', git: 'https://github.com/drpebcak/fqdn-cookbook.git'
  cookbook 'pacman'
  cookbook 'yum'
  cookbook 'zypper'
end

cookbook 'apache2_test', path: 'test/cookbooks/apache2_test'
