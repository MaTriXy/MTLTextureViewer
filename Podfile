platform :macos, '10.15'

source 'https://cdn.cocoapods.org/'

install! 'cocoapods', :disable_input_output_paths => true

use_frameworks!
inhibit_all_warnings!

def common_pods
  pod 'Alloy/Shaders'
  pod 'SwiftMath'
end

target 'MTLTextureViewer' do
  common_pods
end

target 'QuickLookPreviewExtension' do
  common_pods
end
