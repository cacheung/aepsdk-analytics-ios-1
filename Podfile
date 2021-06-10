# Uncomment the next line to define a global platform for your project
platform :ios, '10.0'
use_frameworks!

project 'AEPAnalytics.xcodeproj'

target 'AEPAnalytics' do
  pod 'AEPCore'
  pod 'AEPServices'
  pod 'AEPRulesEngine'
end

target 'AEPAnalyticsUnitTests' do
  pod 'AEPCore'
  pod 'AEPServices'
  pod 'AEPRulesEngine'
end

target 'AEPAnalyticsFunctionalTests' do
  pod 'AEPCore'
  pod 'AEPServices'
  pod 'AEPRulesEngine'
end

target 'AnalyticsSampleApp' do
  pod 'AEPCore'
  pod 'AEPServices'
  pod 'AEPIdentity'
  pod 'AEPRulesEngine'
 #currently, we still need ACPCore for Assurance. Can be removed with thh future AEPAssurance release  
  pod 'ACPCore', :git => 'https://github.com/adobe/aepsdk-compatibility-ios.git', :branch => 'main'
  pod 'AEPAssurance'
end
