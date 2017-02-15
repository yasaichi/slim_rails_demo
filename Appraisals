appraise 'repro the bug on sprockets3' do
  gem 'slim-rails', github: 'slim-template/slim-rails', tag: 'v3.1.2'
  gem 'sprockets', '~> 3.0'
end

appraise 'repro the bug on sprockets4' do
  gem 'slim-rails', github: 'slim-template/slim-rails', tag: 'v3.1.2'
  gem 'sprockets', '~> 4.0.0.beta4'
end

appraise 'fix the bug on sprockets3' do
  gem 'slim-rails', github: 'yasaichi/slim-rails', branch: 'use-register-transformer'
  gem 'sprockets', '~> 3.0'
end

appraise 'fix the bug on sprockets4' do
  gem 'slim-rails', github: 'yasaichi/slim-rails', branch: 'use-register-transformer'
  gem 'sprockets', '~> 4.0.0.beta4'
end
