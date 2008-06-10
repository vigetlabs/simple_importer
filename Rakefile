# Look in the tasks/setup.rb file for the various options that can be
# configured in this Rakefile. The .rake files in the tasks directory
# are where the options are used.

load 'tasks/setup.rb'

ensure_in_path 'lib'
require 'simple_importer'

task :default => 'spec:run'

PROJ.name = 'simple_importer'
PROJ.authors = 'Justin Marney'
PROJ.email = 'justin.marney@viget.com'
PROJ.url = 'FIXME (project homepage)'
PROJ.rubyforge_name = 'simple_importer'

PROJ.spec_opts << '--color'
PROJ.version = SimpleImporter::VERSION

# EOF
