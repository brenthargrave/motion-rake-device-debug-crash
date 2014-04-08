# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'motion-rake-debug-crash'
  app.sdk_version = "7.1" # build against the latest-and-greatest
  app.deployment_target = "7.0" # minimum SDK we support (require autolayout)
end
