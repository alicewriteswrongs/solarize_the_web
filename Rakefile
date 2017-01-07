task :default => [:clean, :zip]

task :clean do |t|
  sh "rm -rf *.zip"
end

task :zip do |t|
  sh "zip -r solarize_the_web.zip manifest.json css/*"
end
