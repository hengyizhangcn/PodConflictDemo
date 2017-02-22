platform :ios, '8.0'

source 'https://github.com/CocoaPods/Specs.git'
inhibit_all_warnings!

# 多个target共用一套pod的写法
abstract_target 'CommonPods' do

pod 'AlipayCopy', :git => 'https://github.com/hengyizhangcn/AlipayCopy.git'
pod 'EZOpenSDKCopy', :git => 'https://github.com/hengyizhangcn/EZOpenSDKCopy.git'
target 'PodConflictDemo' do
end
end
