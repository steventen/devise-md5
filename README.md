## Steps

1. Include `gem 'devise-encryptable'` in Gemfile

2. Add `config.encryptor = :md5` into `config/initializers/devise.rb`
 
3. Create `md5.rb` file in `lib/devise/encryptors/` directory.

4. Append `:encryptable` after `devise` method in User model

5. Add `attr_accessor :password_salt` in User model
