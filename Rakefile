def markdown source, target
  sh "markdown #{source} > #{target}"
end

rule 'index.html' => 'README.md' do |t|
  markdown t.source, t.name
end
rule ".html" => ".md" do |t|
  markdown t.source, t.name
end

sources = Dir.glob('*.md') - ['README.md']

task :default => ['index.html'] + sources.map {|file| file.sub /.md$/, '.html' }

