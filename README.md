# MOODetail

MOODetail is a Single Page Application using JavaScript on the frontend and a Rails API backend. Use this app to detail prompts you notice to specific mood states. 

<img src="MOODetail_screenshot.png" alt="MOODetail screenshot" width="65%"/>

## Installation

For the Rails API, run the following code: 

```cd moodetail-api
bundle install
rails db:migrate
rails db:seed
rails s
```
For the JavaScript front end, open the following file in a browser: `moodetail-js-frontend/index.html`

## Usage

After seeding the database for the mood states, you can now enter descriptions of prompts to various moods.  Once entered, the descriptions will append to the appropriate "mood card" and will save to the database. 

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/maasa333/MOODetail. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the StorieZZZ project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/maasa333/MOODetail/blob/master/CODE_OF_CONDUCT.md).
