 Hi, I'm Priyanka Regmi 👋

- 🔭 I’m currently studying bachelor in Information Technology (BIT).
- 🌱 Meanwhile I'm learning Data Science,Java, and web-development
repo.languages.sort_by { |_, size| size }.reverse.each do |language, size|
  percentage = ((size / repo.size.to_f) * 100).round
  puts "%-4s %s" % ["#{percentage}%", language]
end
     
