# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

def import_pods
  pod 'GRDB.swift/SQLCipher'
  pod 'SQLCipher', '4.3.0'
end

target 'GRDB-Builder' do
	use_frameworks!
    platform :ios, '10.0'
    import_pods
end

target 'GRDB-Builder-mac' do
	use_frameworks!
    platform :osx, '10.12'
    import_pods
end