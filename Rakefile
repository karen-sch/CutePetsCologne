require 'dotenv'
Dotenv.load

require_relative 'lib/cuties_in_cologne'

desc "Tweet random pet."
task :twitter do
  #Twit.new(AdoptAPet.random).tweet
  puts Twit.new(AdoptAPet.random).tweet.inspect
end

task :default => :twitter
