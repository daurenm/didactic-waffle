# Uncomment the next line to define a global platform for your project
platform :ios, '12.0'

def common_pods
  pod 'SnapKit'
  pod 'SwiftyAttributes'
  pod 'ChameleonFramework/Swift', :git => 'https://github.com/ViccAlexander/Chameleon.git', :inhibit_warnings => true
end

target 'didactic-waffle' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for didactic-waffle
  common_pods

  target 'didactic-waffleUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end
