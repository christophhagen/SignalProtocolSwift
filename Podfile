use_frameworks!

abstract_target 'SignalProtocolSwift' do

  # Pods for SignalProtocolSwift

  # Cryptographic functions powered by CommonCrypto
  pod 'CommonCryptoModule', '~> 1.0.2'

  # Protocol Buffers in Swift
  pod 'SwiftProtobuf'


  target 'SignalProtocolSwift-iOS' do
    platform :ios, '9.0'
    
    target 'SignalProtocolSwift-iOSTests' do
      inherit! :search_paths
      # Pods for testing
    end
  end

  target 'SignalProtocolSwift-macOS' do
    platform :osx, '10.9'
    # Pods for SignalProtocolSwift-macOS
  end

  target 'SignalProtocolSwift-tvOS' do
    platform :tvos, '9.0'
    # Pods for SignalProtocolSwift-tvOS
  end

  target 'SignalProtocolSwift-watchOS' do
    platform :watchos, '4.0'
    # Pods for SignalProtocolSwift-watchOS
  end
end
