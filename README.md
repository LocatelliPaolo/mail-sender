this goes in config/environments/development.rb

config.action_mailer.default_url_options = { host: '0.0.0.0:8080' }

  config.action_mailer.delivery_method = :smtp
  config.action_mailer.smtp_settings = {
    address: 'data',
    port: data,
    enable_starttls_auto: data,
    user_name: 'data',
    password: 'data',
    authentication: 'data'
}