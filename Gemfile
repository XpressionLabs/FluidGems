source 'https://rubygems.org'

ruby '2.0.0'

group :development, :test, :production do
  # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
  gem 'rails', '4.2.6'

  # https://github.com/galetahub/ckeditor
  gem 'ckeditor', '4.0.11'

  # Use sqlite3 as the database for Active Record
  gem 'mysql2', '0.3.20' #0.4 geeft problemen met rails 4.0

  # Use SCSS for stylesheets
  gem 'sass-rails', '~> 4.0.3'
  gem 'bootstrap-sass', '~> 3.1.1'

  # Voor de mooie icons
  gem 'font-awesome-rails', '4.4'

  # Use jquery as the JavaScript library
  gem 'jquery-rails', "3.1.4"

  # doc http://rubydoc.info/gems/jquery-ui-rails/4.2.0/frames
  gem 'jquery-ui-rails', '~> 5.0.3'

  #https://github.com/russfrisch/modernizr-rails
  gem 'modernizr-rails', "2.7.1"

  # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
  gem 'jbuilder', '~> 1.2'

  # Use unicorn as the app server
  gem 'puma',"2.11" #afgeleid van productie
  gem 'passenger',"5.0.13" #afgeleid van productie

  #sessies opslaan in de database
  gem 'activerecord-session_store','0.1.1'

  #provides Ruby language bindings for GNOME's Libxml2
  #wordt gebruikt in XM engine
  gem 'libxml-ruby','2.8.0'

  #encryptie van passwords
  gem 'bcrypt-ruby','3.1.5'

  #Datepicker voor bootstrap
  gem 'bootstrap-datepicker-rails', '~> 1.4.0'

  #creates attribute accessors for all database table columns in each model
  #gebruikt in o.a. de auditlogs
  gem 'safe_attributes','1.0.10'

  #gem 'rspec'
  gem 'will_paginate-bootstrap','1.0.1'

  #truncate_html cuts off a string of HTML and takes care of closing any lingering open tags
  gem 'truncate_html','0.9.3'

  #Rails jQuery file uploads via standard Rails "remote: true" forms
  gem 'remotipart', '~> 1.2'

  #templating systeem
  gem 'liquid','3.0.3'

  #verplichte js interpreter, alternatief voor nodejs
  gem 'therubyracer','0.12.2'

  #wat het zegt, doet het ook
  gem 'exception_notification','4.1.1'

  #backend voor activejob
  gem 'delayed_job_active_record'

  #nodig voor starten queueu van delayed_job
  gem 'daemons'

  #excel sheets
  gem 'roo','2.0.1'
  gem 'roo-xls','1.0.0' #xls legacy support -nv

  gem 'nokogiri','1.6.6.2'

  gem 'loofah','2.0.3' #sanitzer voor html -pm

  #voor het wegscrhijven van Excel bestanden (exports dus), kan niet met Roo
  gem 'spreadsheet','1.0.1'

  #deze gem zorgt dat je zaken zoals responds_to :xls etc kunt doen
  #tot voorkort was dit onderdeel van rails
  gem 'responders','2.1.0'

  gem 'barby', '0.6.2' #barcode generator
  gem 'rqrcode', '0.10.1' #qrcode generator, dependency van barby
  #https://rubygems.org/gems/touchpunch-rails/versions/1.0.3
  gem 'touchpunch-rails', '~> 1.0.3'

  #sso surf
  gem 'ruby-saml', '~> 1.0.0'
end
