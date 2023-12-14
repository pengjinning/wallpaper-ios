# Uncomment the next line to define a global platform for your project
platform :ios, '13.0'
#source 'https://github.com/CocoaPods/Specs.git'
source 'https://mirrors.tuna.tsinghua.edu.cn/git/CocoaPods/Specs.git'

use_frameworks!

def shared_pods
  pod 'Alamofire'
  pod 'RxSwift'
end

target 'wallpaperapp' do
  platform :ios, '13.0'
  shared_pods
  
  pod 'RxDataSources'
  pod 'Kingfisher'
  pod 'SnapKit'
end

target 'Watch Extension' do
  platform :watchos, '5.0'
  shared_pods
end
