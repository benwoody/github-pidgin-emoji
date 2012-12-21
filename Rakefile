desc "Cop github emoticons to Pidgin"
task :install do
  puts "Copying github emoticons to ~/.purple/smileys"
  purple = ENV['HOME'] + "/.purple/smileys"
  FileUtils.cp_r('./github-emoji', purple)
end
