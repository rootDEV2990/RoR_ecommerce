# Ruby on Rails eCommerce

Built to play with Solidus and try to build a CMS solution. Check it out the power of Rails ;). Newest work is in my feature branch...ya know..#gitflow

## Guide
1. Add solidus to ./Gemfile
    gem 'solidus'
    gem 'solidus_auth_devise'
    gem 'bourbon', '< 5.0.0'
2. Open terminal inside project folder and type:
    bundle install
3. Install Spree to install Soludus on top of later
    bin/rails g spree:
    *will ask you for an admin user and pw during install*
4. Generate the solidus authicatin install
    bin/rails generate solidus:auth:install
5. Migrate the Database 
    rails db:migrate    
6. Run rails server, got o localhost:3000 on your computer after running the following in terminal
    rails s

### Prerequisites

Ruby and Rails...click link for more.

https://github.com/rootDEV2990/rails_arch_linux

## Authors

👤 **Miguel Angel Enciso Sanchez**

- Github: [@rootDEV2990](https://github.com/rootDEV2990)
- Twitter: [@m29902](https://twitter.com/m29902)
- Linkedin: [linkedin](https://www.linkedin.com/in/miguel-enciso-6474741a1/)
- Medium: [medium](https://medium.com/@website.dev)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](issues/).

## Show your support

Give a ⭐️ if you like this project!

Bitcoin donations accepted ;)

1AD5ANtHmqemTZ2Qmv5UqJAMijTNyCAH8D 🚀