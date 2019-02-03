
# Add Evident's pod repo
#
#source 'https://github.com/evidentidpublic/mobile-podspecs.git'
# source 'https://github.com/LuciesHuman/podspecs.git'
# source 'git@github.com:LuciesHuman/podspecs.git'
source 'git@github.com:LuciesHuman/mobile-podspecs.git'
source 'https://github.com/CocoaPods/Specs.git'

using_bundler = defined? Bundler
unless using_bundler
    puts "\nPlease re-run using:".red
    puts "  bundle exec pod install\n\n"
    exit(1)
end

platform :ios, '9.0'

inhibit_all_warnings!
use_frameworks!

project 'AssureSDK Demo/AssureSDK Demo.xcodeproj'

target 'AssureSDK Demo' do
    pod 'AssureSDK'
end

target 'AssureSDK DemoTests' do
end
