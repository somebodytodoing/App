target 'Demo' do
  use_frameworks!
  pod 'YTKNetwork'
  pod 'YYCache', '1.0.4', :configurations => ['Debug']
  pod 'YYModel', git: 'https://github.com/ibireme/YYModel.git', branch: 'master'
  pod 'PodA', :path => '../PodA'
  pod 'PodB', :path => '../PodB'
  pod 'PodC', :path => '../PodC', :subspecs => ['PodCSubspec1', 'PodCSubspec2', 'PodCSubspec2/PodCSubspec2Subspec1']
end
