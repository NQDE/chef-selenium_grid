source 'https://supermarket.chef.io'

metadata

cookbook "selenium", git: "https://github.com/NQDE/chef-selenium.git", branch: "master"

group :solo do
  cookbook 'selenium_grid_test', path: 'test/fixtures/cookbooks/selenium_grid_test'
end
