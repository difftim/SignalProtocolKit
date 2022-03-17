platform :ios, '10.0'

use_frameworks!

target 'AxolotlKit' do
  pod 'AxolotlKit', path: '.'
  pod 'Curve25519Kit', git: 'https://github.com/WhisperSystems/25519.git', branch: 'mkirk/framework-friendly'
  pod 'HKDFKit', git: 'https://github.com/WhisperSystems/HKDFKit.git'
  pod 'SignalCoreKit', git: 'https://github.com/signalapp/SignalCoreKit.git'

  target 'AxolotlKitTests' do
    inherit! :search_paths
  end
end

