# -*- ruby -*-

require 'rubygems'
require 'hoe'
require './lib/spreadsheet.rb'

ENV['RDOCOPT'] = '-c utf8'

Hoe.new('spreadsheet', Spreadsheet::VERSION) do |p|
  # p.rubyforge_name = 'spreadsheetx' # if different than lowercase project name
   p.developer('Hannes Wyss', 'hannes.wyss@gmail.com')
   p.remote_rdoc_dir = ''
   p.extra_deps << ['ruby-ole', ">= 1.2.11.1"]
end

# vim: syntax=Ruby
